# Drupal 8 webform mailchimp subscription example
Plugin to easily subscribe to Mailchimp via a drupal 8 webform. Read about it here: [Mailchimp subscription with webform in drupal 8 (Video)](https://stefvanlooveren.me/blog/how-create-mailchimp-subscription-drupal-8-webform-module).
## How to
Download and install the example:
`drush en webform_mailchimp_example`

Fill in the required parameters inside:
 `webform_mailchimp_example/src/Plugin/WebformHandler/newsletterSubscription.php` (more info inside this file)

Create a webform, go to settings and then emails / handlers (`/admin/structure/webform/manage/<webform_id>/handlers`). Add the handler here. Make sure the webform has these fields:
`first_name`
`last_name`
`e_mail`

