# GOVUK Elements Snippets

A set of snippets to include govuk-elements in your visual code editor.

---

## `ATTENTION`

`With the introduction of govuk-element-sass 3.0, the markup on radio buttons and 
checkboxes has changed. For now, both the new and old versions are available and 
suffixed accordingly with [NEW] and [OLD]. The old ones will be removed in a 
future release now that they're depricated.`

---

![Demo](https://github.com/abbott567/govuk-elements-snippets/raw/master/images/demo.gif)

## Commands

## Layout
Nunjucks page template  
`govuk-page`  

## Form elements
Form group  
`govuk-form-group`

Input fields  
`govuk-input`  
`govuk-input-helptext`  
`govuk-input-date`  
`govuk-file-upload`

Dropdown  
`govuk-dropdown`

Radio buttons  
`govuk-radio-buttons`  
`govuk-radio-buttons-stacked`
`govuk-radio-buttons-hidden`  

Checkboxes  
`govuk-checkboxes`  
`govuk-checkbox-disclaimer`  
`govuk-checkboxes-hidden-field`

Buttons  
`govuk-button-regular`  
`govuk-button-start`  
`govuk-button-disabled`  

## Typography
Headings  
`govuk-heading-xlarge`  
`govuk-heading-large`  
`govuk-heading-medium`  
`govuk-heading-small`  

Inset text  
`govuk-inset-text-narrow`  
`govuk-inset-text-wide`

Legal text  
`govuk-legal-text`

Hidden text  
`govuk-hidden-text`

## Contributing

GitHub Repo: [https://github.com/abbott567/govuk-elements-snippets](https://github.com/abbott567/govuk-elements-snippets)

Feel free to fork this repo and add any snippets you think would be useful. Any pull requests that are merged will be updated into the extension on the Visual Studio Code market place will full credits listed in the change log.

## To do

- Split elements up into multiple JSON files to keep things cleaner
- Split layouts so .html and .njk can include different layout files
- Add validation elements