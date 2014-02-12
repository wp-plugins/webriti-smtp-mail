=== Webriti SMTP Mail ===
Contributors:harimaliya,priyanshu.mittal
Tags:email, gmail, mail, mail smtp, outgoing mail, phpmailer, privacy, security, sendmail, smtp, ssl, tls, wordpress smtp, wp smtp, wp-phpmailer, wp_mail

Stable tag: 1.0.1
Requires at least: 3.3+
Tested up to: 3.8.1
License: GPLv2 or later

License URI: http://www.gnu.org/licenses/gpl-2.0.html

Now send Emails from your WordPress Blog using your preferred SMTP Server. Webriti Smtp Mail plugins helps us to 
send mails via Smtp instead of php mail() function. No need to write any code just configure it and ready to go.

== Description ==

Webriti SMTP Mail can help us to send emails via SMTP instead of the PHP mail() function. It adds a settings page to "Dashboard"->"Settings"->"Webriti SMTP Email" where you can configure the email settings.

This plugin reconfigure's the wp_mail() function to send SMTP Mails. But you have to make sure that leaving Smtp Host name blank will not reconfigure the WordPress wp_mail() function.

The Practical use of this plugins comes when theme have a contact page, which on submit, shows you the successful message, but, still admin did not receive any email, here comes this smtp plugin which will makes your contact form workable. 

Webriti Smtp Mail Plugin has following settings.

a)  General Settings

The general settings section consists of the following options

From Email Address: The email address that was sending emails to users.
From Name: Specify your name which you want to show in the Email Headers.
SMTP Host: Your outgoing mail server (example: smtp.gmail.com)
SMTP Port: The port that will be used to relay outbound mail to your mail server (example: 465)
SMTP Authentication: Yes 
Username: Enter your mail server username.
Password: Enter password you use to login to the mail server.

b) You can always check weither the specified SMTP Details are correct or not with the help of Test Mail Utility present.



== Installation ==
1. Download
2. Upload to your `/wp-contents/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress and Enjoy.

== Screenshots ==

1. Configure SMTP Settings.
2. Help and support.


== Frequently Asked Questions ==

1. How to use gmail as smtp server?
 

For  using Gmail Smtp Server with this plugin then set the following details
Smtp Host mail.gmail.com
Smtp Port usually 465
Username: Your gmail username
Password: Your gmail password
SSL :On

== Changelog ==
@version 1.0

Webriti Smtp Mail Plugin Released

== Upgrade Notice ==
Always try to use latest version on repository.