# Fred's List Evolved

## Description
While the original Fred's List works it still needs many enhancements.  Its original counterpart 
in real life has no api and this needs to rectified.  

## Normal Mode

### New features
* On the user account page display the current api token for the user as well as a button to regenerate it
* Create a search feature on the post list page that will search the title and description for any posts containing the words

### API
* Implement a restful api using Django Rest Framework for all models in the system.
* Ensure that users can only update and edit their own information
* Use filters with the api to implement the search feature on the post list


## Hard Mode

* Create a notification feature that will allow users to:
	* Add/Remove notifications based on keywords to look for in title and description
	* Will use signals to send a notification when a new post is updated with the search criteria
* Implement Sendgrid to handle all outgoing transactional emails

### Sendgrid
This is a transactional email sender that will provide detailed reporting on emails sent.  To get going:
* Sign up for an account (it's free)
* Click your name drop down on the dashboard
* Look for the API keys option
* Add a new key (Don't forget to copy it down)
* Now read through the documentation for your options:
	* Official SendGrid Python Library: https://github.com/sendgrid/sendgrid-python#example
	* DJango Library: https://github.com/elbuo8/sendgrid-django
	* WebV2 API: https://sendgrid.com/docs/API_Reference/Web_API/index.html

## External Links
* [DRF Class Based Views](http://www.django-rest-framework.org/tutorial/3-class-based-views/)
* [DRF Auth and Permissions](http://www.django-rest-framework.org/tutorial/4-authentication-and-permissions/)
* [DRF Generic Views](http://www.django-rest-framework.org/api-guide/generic-views/)
