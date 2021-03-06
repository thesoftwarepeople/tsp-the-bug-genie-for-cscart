The Bug Genie for CS-Cart
-------
The Bug Genie for CS-Cart is an addon integration with The Bug Genie project management and 
issue tracking software. Excellent for CS-Cart installations that sell software and wish to 
integrate issue tracking into their market place.

For up-to-date installation and setup notes, visit the FAQ:
[http://lab.thesoftwarepeople.com/tracker/wiki/Cscart-tbg:MainPage](http://lab.thesoftwarepeople.com/tracker/wiki/Cscart-tbg:MainPage)


*GENERAL INSTALLATION NOTES*

- Download from repository
- Unzip the zip file in the directory where CS-Cart runs
- If the zip creates a new directory called `tsp-the-bug-genie-for-cscart` you will need to run the install script, else you are done
- If `tsp-the-bug-genie-for-cscart` folder created by zip, Navigate to the folder. Update the $target_loc in the install.php and run its. Command: php install.php
- Open CS-Cart Administration Control Panel
- Navigate to Addons -> Manage Addons
- Find the "The Software People: The Bug Genie for CS-Cart" addon and click "Install" (If you don't see it make sure "All Stores" is selected at the top of the screen)
- After Install, from the Addons listing click on Settings for "The Software People: Appointments"
- Update the database settings for The Bug Genie database
- Update The Bug Genie settings

*USING THE MODULE*

- Find a product that you wish to integrate with The The Bug Genie by clicking on Products -> Products from
  the Administration Control Panel
- Once the product is opened, click on the Addons tab
- Find the section "The Software People: The Bug Genie for CS-Cart"
- In this initial release you are able to do the following:
-- Include a link to the product's home page in The Bug Genie
-- Include a link to the product's Wiki in The Bug Genie
-- Report Issues in The Bug Genie
-- View Open Issues in the Bug Genie
- If this product is a type of issue, you can submit the issue to The Bug Genie database by supplying product options
  that will be used to populate an issue to submit to The Bug Genie database (the product MUST have a list of Options)
-- Select the project that this product request will be submitted to
-- Decide the type of issue to create (required if product selected)
-- Select an Issue Name (If none available you will need to add an Input type field to the product's options)
-- Enter in the details of the issue, you can leave this blank and only the product options key and value will
   be added to the database

*REPORTING ISSUES*

Thank you for downloading the The Bug Genie for CS-Cart 1.0
If you find any issues, please report them in the issue tracker on our website:
[http://lab.thesoftwarepeople.com/tracker/cscart-tbg](http://lab.thesoftwarepeople.com/tracker/cscart-tbg)

*COPYRIGHT AND LICENSE*

Copyright 2013 The Software People, LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
