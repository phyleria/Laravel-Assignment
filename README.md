# Laravel-Assignment
### Write a Laravel application for a simple registration and login system for a web based software.
The registration system should demonstrate end to end use of a Laravel PHP framework by letting the
registration request go though the following stages:
1. The view (Create a registration form on the view files using blade templating engine)
2. Routing file – The form created in part 1 should submit its data to a an endpoint (in the route file)
3. Create a controller called RegistrationController using php artisan command (with resource option so
as to also create the CRUD methods within the controller in one go).
4. The endpoint in part 2 to map the request data from the form in part 1 to a RegistrationController,
into a method called store() within the RegistrationController class.
5. Also use php artisan command, to create a model called Register
6. Import the model created in section 4 into the controller class (RegistrationController in this case).
7. Also import the Laravel Eloquent class into the RegistrationController class.
8. Use the eloquent syntax in the store method to insert the registration data into a database table.
### NB:
Where possible, validate that the registration data are valid by using validation rules in the Registration
Model
Preferably use php artisan migration to create the database tables
Also create an interface for the user to be able to edit registration details.
The registration module comes shipped with Laravel so this exercise is just for practice of end to end
request flow in Laravel.
