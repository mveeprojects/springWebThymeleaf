# springWebThymeleaf
Simplest means I've found so far of building a spring web app with html frontend (rather than REST interface)

Originally built using [this Maven tutorial](https://spring.io/guides/gs/serving-web-content/), since updated to Gradle using `gradle init`.

**HomeController.java:**

 - Maps requests from /greeting to the greeting.html file (_return "greeting"_)
 - Uses _Model_ to pass values into the greeting.html view

**greeting.html:**

 - thymeleaf dependency declared in _<html>_ tag
 - Values passed in through the _Model_ variable in HomeController.java are referenced using _'${var_name}'_ inside the html

### Links
- [Original write up on mveeprojects.wordpress.com](https://mveeprojects.wordpress.com/2017/11/11/good-thymes-with-spring-boot/).
