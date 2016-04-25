# Import students

Importing students as users can be done if you have a .csv file with the following columns.

## Steps to import students

### Create the group

- Navigate to [groups](https://elevforeningen.vih.dk/groups)
- Click "Create group"
- Create the group with this notation, e.g. "15/16"
- Click edit on the group. Look in the address bar. See what number is here `node/**[GROUP_NUMBER]**/edit`

### Verify your CSV file

- Make sure your file is in UTF-8 encoding.

Verify that the structure is as this:

- NAME
- ADDRESS
- POSTAL
- CITY
- COUNTRY (with the country code - DK = Denmark, DE = Germany, IS = Island, GL = Grønland)
- PHONE
- MAIL
- GROUP (the id of the group you want people imported into - you need to manually create that column and fill it in with the **`GROUP_NUMBER`**)

Verify what the delimiter is (the character that separates the fields). Best with `,`.

### Import users

- Navigate to [import](http://elevforeningen.vih.dk/import)
- Choose "Student Import CSV"
- Choose the file you wish to upload.
- Click "Import"

### Verify that users are in the group

- Check that all the users has been approved, by navigating to https://elevforeningen.vih.dk/group/node/[GROUP_NUMBER]/admin/
