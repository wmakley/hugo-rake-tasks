# Netlify::Rake::Tasks

Rake tasks for Hugo sites.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'hugo-rake-tasks'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install hugo-rake-tasks

## Usage

In your Rakefile:

```rake
require 'hugo_rake_tasks/tasks'

# If you want just running "rake" to build the site:
task :default => :build
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

