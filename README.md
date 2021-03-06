# VideoConference

A tutorial app for AngularJS and WebRTC.

## Installation

This "gem" is intended to be cloned and played with.

    git clone https://github.com/dugancathal/video_conference.git

## Usage

After cloning, you should just need to `bundle` and `rackup`.

    bundle install
    rackup -p 9292 -E production # You need the production for Faye

## Tags

There are a bunch of tags for the various steps of the tutorial.

### step0

The app boots ... that's about it

### step1

The app has a local video on the main page.

### step2

A signaler is born.

### step3

There isn't really a given commit for step 3. This step is more
infrastructure than anything else.

## Testing

The ruby stuff isn't tested (because that's not what this project is about), but all
the javascript tests can be found in `spec/javascripts`. The tests can be run
using the jasmine runner in either Chrome or Firefox by running:

    rake jasmine

Then, open a browser to the shown URL, usually localhost:8888.

## Contributing

1. Fork it ( https://github.com/dugancathal/video_conference/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
