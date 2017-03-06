# Linker

Linker is a cross-browser jQuery [plugin](http://jquery.gr/linker/) by Michalis Tzikas & Vasilis Lolos. This is a great technique to transform urls to links. This is just a ruby wrapper to use it with Rails.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'linker', :git => 'git://github.com/rahuldstiwari/linker.git'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install linker

## Usage

Put class "linker" on your HTML wrapper link and all your urls will be converted into links.

```html
<pre>
    <div class="linker">www.jquery.gr/linker</div>
</pre>
```



## Usage

Need to put (Optional) Settings like target, className, rel.


## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/rahuldstiwari/linker. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

