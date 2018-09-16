# openf1.github.io

[![Build Status](https://travis-ci.org/openf1/openf1.github.io.svg?branch=master)](https://travis-ci.org/openf1/openf1.github.io)

Home of openf1.github.io

## Development

To set up your environment to contribute to this site:

1. Clone the repository:

    ```
    $ git clone https://github.com/openf1/openf1.github.io.git
    ```

2. `cd` into the repo's directory
3. Run `script/bootstrap` to install the necessary dependencies
4. Run `bundle exec jekyll serve` to start the preview server
5. Visit `localhost:4000` in your browser to preview the theme

Add pages, documents, data, etc. As you make modifications to your content, your site will regenerate and you should see the changes in the browser after a refresh.

To add sections to the main page, create a new html file under the collections directory `_sections`. See theme [doc](https://github.com/openf1/openf1-jekyll-theme) for more information.

### Running Tests

The theme contains a minimal test suite. To run the tests, simply type:

    $ script/cibuild

You'll need to run `script/bootstrap` once before the test script will work.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

