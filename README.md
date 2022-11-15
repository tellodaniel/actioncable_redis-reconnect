# ActioncableRedis::Reconnect

There's an issue with ActionCable and Redis described at https://github.com/rails/rails/pull/45478 that this gem fixes.

When the PR is finally fixed, this gem will be updated to remove the patch and warn you to remove the gem.

## Installation

Install the gem and add to the application's Gemfile by executing:

    $ bundle add actioncable_redis-reconnect

If bundler is not being used to manage dependencies, install the gem by executing:

    $ gem install actioncable_redis-reconnect

## Usage

Reboot your Rails app and that's it! Your application will be patched.

When Rails or ActionCable updates are released, you'll need to update this gem via:

```
bundle update actioncable_redis-reconnect
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/superfly/actioncable_redis-reconnect. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/superfly/actioncable_redis-reconnect/blob/main/CODE_OF_CONDUCT.md).

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the ActioncableRedis::Reconnect project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/superfly/actioncable_redis-reconnect/blob/main/CODE_OF_CONDUCT.md).
