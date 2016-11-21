## PHPServer4ODK (Beta)
Php server for ODK Collect
- Its under developemnet but runnable

###Requirement

- PHP Version >= 5.5
- MYSQL Database
- Uploadable directory for uploading xforms

### INSTALLATION
- use odk.sql to setup database
- set url of your website in 'required/odk/server/0.1/components/app/\_params.php' ['url' => 'yourwebsite url' ]
- configure database by editing 'required/odk/server/0.1/components/database/\_params.php'
- make sure directory 'public_html/uploads/xforms' is writablle for uploading forms

### Components Configuration
Component configuartion is located in directories

 - required/odk/server/0.1/components
 - required/odk/0.1/app/config/components  

Change them as your application requirement


###Usage

- Admin Login
	- user: odkadmin
	- pass: odkadmin

- Use empty/any credentials on odk collect
