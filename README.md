## UBC Button Link Field Formatter


This module provides a custom field formatter that allows you to render link fields as UBC CLF buttons.

This module works by rendering a Link Field's <a> tag with the addition of CLF button classes. It does not provide any CSS.

## To use this module

* Activate in modules in UBC IT Web Services package
* Only available for Link fields


# Applying the field format to your field

1. While editing content type to can apply UBC CLF Button field formatting to your Link Field in the Manage Display
2. When adding Link field to view - you can apply UBC CLF Button field formatting in the field setting

# Using Field Formatter

There are 3 settings for the formatter
* Select list that provides basic list of out-of-the-box button styles, plus 1 external link option
* Text field to add your own class, these can be added in addition to any class you have selected from the select list
* Select list for target options

Default button styles provided are

       Primary =>       'btn btn-primary'
       Info =>          'btn btn-info'
       Success =>       'btn btn-success'
       Warning =>       'btn btn-warning'
       Danger =>        'btn btn-danger'
       Inverse =>       'btn btn-inverse'
       Link =>          'btn btn-link'
       External Link =>  'icon-external-link'