## v0.3.2 (2017-02-22)
* Added
  * SelectAssoc
    * multiple_select support
  * Select
    * Validation if value sent by user exists in the generated select

## v0.3.1 (2017-02-18)
* Added
  * `Formex.Template.add_class`

## v0.3.0 (2017-02-17)
* Added
  * Ability to create a custom templates
  * Templates
    * Bootstrap horizontal
    * Bootstrap vertical
* Changed
  * Extracted repo functions from a `Formex.Builder` to a `Formex.Repo`.
  * `web/web.ex` - You have to `use Formex.Controller` instead of
    `import Formex.Builder` from now on.

* Removed
  * `formex_row_horizontal` and `formex_rows_horizontal`.
    You have to use a horizontal template from now on.

## v0.2.3 (2017-02-12)

* Added
  * Select Assoc
    * `group_by` option

## v0.2.2 (2017-02-09)

* Added
  * Select Assoc
    * `query` option
* Changed
  * Select Assoc
    * renamed `choice_name` to `choice_label`

## v0.2.1 (2017-02-07)

* Added
  * tests

## v0.2.0 (2017-01-28)

* Added
  * custom fields