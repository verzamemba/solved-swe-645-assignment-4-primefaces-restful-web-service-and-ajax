Download Link: https://assignmentchef.com/product/solved-swe-645-assignment-4-primefaces-restful-web-service-and-ajax
<br>
<strong>Application Overview: </strong>

This assignment is an extension of the application you developed in previous assignment. In this case, you will re-implement all .xhtml files where you will replace <strong>&lt;h: </strong>tags by <strong>&lt;p: </strong>tags, to the extent possible, using <strong>PrimeFaces UI library</strong>. This includes using the look and feel of <strong>default theme </strong>of PrimeFaces. You are more than welcome to use any other PrimeFaces theme if you so prefer. In addition, you will develop <strong>RESTful web services </strong>that returns city and state given a zipcode. An asynchronous call to the RESTful web service should be used to automatically populate city and state based on zipcode entered by the user. The homepage of the application will have menu with links from the previous assignment: 1) Student Survey, which allows a prospective student to fill out a survey form, and 2) List All Surveys, which allows a user to view all surveys done to date. You can try other features of PrimeFaces, such as tabs.




You should continue to use the Amazon EC2 with a Tomcat server (which you provisioned in previous homework) to deploy your application. Also, please add a hyperlink of HW4 solution on your homepage on Amazon S3.




The following are more specific requirements of this application.

<strong> </strong>

<strong>Requirements: </strong>




For this assignment, you will be extending the Student survey web based application with PriceFaces and RESTful web services as specified below:




<u>Student Survey Client (User Interface):</u>




You will continue to use the student survey user interface that you developed for the last assignment to create new records, except as follows:

<ul>

 <li>Re-implement all .xhtml files by replacing &lt;h: tags to &lt;p: tags to the extent possible using PrimeFaces.</li>

 <li>Replace dropdown list by auto-complete</li>

 <li>Telephone number should use input mask (999) 999-9999</li>

 <li>Date fields should have popup calendar</li>

 <li>Replace h:messages or h:message (depending on how you implemented in the last assignment) with p:messages or p:message</li>

 <li>Add another date field on the form that will be used by the surveyor to provide a possible start date of the semester when the student gets admission. Implement a validation rule to ensure that the semester start date is not less than the survey date</li>

</ul>







<ul>

 <li>City and state should be automatically populated based on zip code. This should be implemented using JSF’s built-in ajax support with &lt;f:ajax ………&gt; and related tags.</li>

 <li>Implement a RESTful web service that returns city and state given a zipcode. You can limit the following zipcode, city, and state combination for implementation and testing.</li>

</ul>




zip: 22312, city: Alexandria, state: VA  zip: 22030, city: Fairfax, state: VA  zip: 22301, city: Tysons Corner, state: MD  zip: 20148, city: Ashburn, state: VA

<strong> </strong>

<strong>Note</strong>: Here is a blog on JAX-RS Web Services deployment on Tomcat using Jersey that you might find useful.




<a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">https://java2blog.com/create</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">–</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">restful</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">–</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">web</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">–</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">servicesjax</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">–</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">rs</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">–</a><a href="https://java2blog.com/create-restful-web-servicesjax-rs-using/">using/</a>

and a useful youtube link:

<a href="https://www.youtube.com/watch?v=AWrKBJ8mHz0">https://www.youtube.com/watch?v=AWrKBJ8mHz0</a>


