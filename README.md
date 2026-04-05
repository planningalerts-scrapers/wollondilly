Wollondilly now has a custom web application which has an API. So, we're using that.

This is a scraper that runs on [Morph](https://morph.io). To get started [see the documentation](https://morph.io/documentation)

Add any issues to https://github.com/planningalerts-scrapers/issues/issues

## Expected Output

    Storing S68/2026/29/1 - 2 Jan Street PICTON NSW
    Storing S68/2026/30/1 - 350 Spring Creek Road MOUNT HUNTER NSW
    ...
    Storing CDC/2026/158/1 - 50 Koolahs Street APPIN NSW
    Storing CDC/2026/161/1 - 4 Joseph Lane WILTON NSW
    Finished - processed 133 records

Expected runtime: ~ 10 seconds

## To run the scraper

    bundle exec ruby scraper.rb

## To run style and coding checks

    bundle exec rubocop

## To check for security updates

    gem install bundler-audit
    bundle-audit
