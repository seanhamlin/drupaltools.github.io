# DrupalTools

[Drupaltools.com](http://drupaltools.com), a list of open-source tools used for Drupal development and other Drupal related tasks.

## Contributing

Missing a tool here? Just fork the repo and add your tool as a `<name>.md` in the `_data/projects` folder.

Make sure to follow the following rules:

 - **Open Source:** The generator must have a public repository on Github that we can link to and pull in stats from.
 - **Stick to the format:** Fill out all the same fields as the other tools in `source/projects`.
 - **Short description:** Keep all the details for the body text, keep the description for the overview page short and sweet.

## Running locally

Drupaltools is built with Jekyll. To install and run locally:

```
git clone https://github.com/theodorosploumis/drupaltools.git
cd drupaltools
bundle install (requires ruby 2.1.2 to work w/o errors)
bundle exec jekyll serve
```

## License
This project is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Drupal is a [registered trademark](http://drupal.com/trademark) of [Dries Buytaert](http://buytaert.net/).