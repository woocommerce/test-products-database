# Test Products Database
This repository contains products that was pre-generated using Smooth Generator allowing for getting a site going with lots of products quicker.

## Usage instructions
In order to make use of this database you will require WP-CLI

1. Clone/Download this repository to your local machine
2. Unzip the uploads folder and replace your site's uploads folder with the unzipped version, it contains all the product images.
3. Unzip the `performance-database.sql.sql.zip` file and then copy the `performance-database.sql` file somewhere in the root folder of the site you wish to restore this on.
4. Using command line go to the location the sql file was placed and run the following WP-CLI command `wp db import performance-database.sql`
