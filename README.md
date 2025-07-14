# Gettysburg College ArchivesSpace PUI Plugin
This plugin applies the following modifications:
* `/public/assets/custom.css`: Updates H1-H6 to Montserrat and all other to Noto Sans, aligns header left, makes additional color and branding updates
* `/assets/views/welcome/show.html.erb`: Removes digital objects from Limit by record type dropdown
* `/public/views/_welcome_addition.html.erb`: Adds information below the search box on the home page (called in `/assets/views/welcome/show.html.erb`)
* `/public/views/_header.html.erb`: Removes columns from the header
* `/public/views/layout_head.html.erb`: Calls custom.css
* `/public/views/repositories/_full_repo.html.erb`: Changes email to link to contact page (Ask an Archivist)
Tested with ArchivesSpace 4.0 and above.
