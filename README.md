# TypeScript for Rails ![Travis Build State](https://travis-ci.org/klaustopher/typescript-rails.png)

**I know that there is a bug that doesn't allow you to use any `/// reference`-Statements. I'm going to fix this asap, when the RailsRumble is over and I have some time.**

This is a wrapper for the [TypeScript](http://www.typescriptlang.org/) JavaScript superset language by Microsoft.

It enables you to use the `.ts` extension in the Asset Pipeline and also in ActionView Templates.

This gem uses the [typescript-ruby](https://github.com/TimothyKlim/typescript-ruby) library by Timothy Klim for all the nasty "passing things to JS and parsing it. 

The credit for the overall structure and the tests goes to the people that wrote the [coffee-rails](https://github.com/rails/coffee-rails) Gem, since I shamelessly copy&pasted some of their code.

## Installation

Add this line to your application's Gemfile:

    gem 'typescript-rails'

And then execute:

    $ bundle

## Usage

Just add a `.js.ts` file in your `app/assets/javascripts` directory and include it just like you are used to do.

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
