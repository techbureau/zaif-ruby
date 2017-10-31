This repo is forked from [palon7/zaif-ruby](https://github.com/palon7/zaif-ruby)

# Zaif

Zaif API wrapper for ruby.

## Installation

Add this line to your application's Gemfile:

    gem 'zaif4ruby', github: "techbureau/zaif-ruby"

And then execute:

    $ bundle

## Usage

```ruby
require 'zaif'

api = Zaif::API.new(:api_key => ZAIF_KEY, :api_secret => ZAIF_SECRET)
api.bid("btc", 30760, 0.0001)
api.ask("btc", 30320, 0.0001)

api.get_info
```

## Contributing

1. Fork it ( https://github.com/palon7/zaif-ruby/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
