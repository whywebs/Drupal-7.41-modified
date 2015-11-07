# Drupal-7.41-modified
Now with WhyWebs.Com New Version of Drupal 7.41 with all modules and libraries, no need to worry for any website, all what you need is to download install and that's it enjoy it .. to keep your website up to date be sure that you download our version by GitHub.com 

At the installation level you need to pick whywebs.com profile, which will install the most important 65 module you need with all their libraries.

 
To reproduce the issue
Open admin/modules.
At admin/reports/, open the Recent log messages, it will show the following notice:
Notice: Undefined index: distribution_name in drupal_install_profile_distribution_name() (line 207 of ...).
To solve
Adapt the table name if you use prefix and then execute the following SQL statement:

If you had this issue while you used the Whywebs profile just use this commands 

UPDATE `system` 
SET `status` = '1' 
WHERE `filename` = 'profiles/whywebs/whywebs.profile';

If you had this issue while you used the standard profile just use this commands 

UPDATE `system` 
SET `status` = '1' 
WHERE `filename` = 'profiles/standard/standard.profile';

Modules and libraries that included:
Extra Modules are ==>
addressfield
admin_menu
advanced_help
backup_migrate
calendar
captcha
cck
cck_blocks
ckeditor
conditional_fields
ctools
custom_search
data_export_import
date
devel
draggableviews
ds
elements
email
emfield
entity
extlink
features
feed_import
feeds
field_group
field_permissions
field_slideshow
file_entity
fivestar
flexslider
fontyourface
globalredirect
i18n
job_scheduler
jquery_update
libraries
link
location
media
metatag
multiupload_filefield_widget
node_export
nodequeue
oauth
page_theme
page_title
panels
pathauto
quicktabs
redirect
references
scheduler
search_api
search404
service_links
services
sharethis
superfish
token
uuid
variable
views
views_bulk_operations
views_data_export
views_slideshow
webform
xmlsitemap
Extra Libraries are ==>
ace
awssdk
awssdk2
backbone
ckeditor
colorbox
composer
easing
excanvas_r3
facebook-php-sdk
flexslider
galleria
geocoder
geoip
geoip-api-php
GeoIP2-php
getlocations
history
jquery
jquery.cycle
jquery.domwindow
jquery.easing
jquery.imagesloaded
jquery.jcarousel
jquery.localScroll
jquery.roundabout
jquery.scrollTo
json2
leaflet
masonry-docs
MediaElementjs
mep-feature-playlist
nivo-slider
PHPExcel
plupload
shadowbox
simplepie
superfish
tagcanvas
tinymce
underscore
video-js
whizzywig

To downlaod this version click here From the Source Whywebs.com


or By getting up to date version by Whywebs on GitHub  Click Here

 

Don't forget to do the one click module "WhyWebs.com Module" to make all modules work without checking all the boxes for them



Regards

Mutasem Elayyoub (Sam)

Drupal / PHP Senior Developer

Sam@whywebs.com

Alt:

M22386@live.com

M22386@hotmail.com

Ish6admin@whywebs.com

Whywebs@gmail.com

Support@ish6a.com

Info@mawajez.com
