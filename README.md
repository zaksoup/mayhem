# Mayhem

Text data making too much sense? Unleash Mayhem on it!

## Installation

Add this line to your application's Gemfile:

    gem 'mayhem'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install mayhem

A thesaurus file is necessary for Mayhem to do its business. Download the [Moby Thesaurus](http://icon.shef.ac.uk/Moby/mthes.html "the Moby Thesaurus") and move mobythes.aur to the gem's lib/data directory.

## Usage

First off, require Mayhem:

    require 'mayhem'

Now, when you want to synonymize a string, just pass it through Mayhem's synonymizer:

    Mayhem.synonymize(your_string)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
