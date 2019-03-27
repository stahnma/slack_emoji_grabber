
# Grab you slack team's emojis

Do you ever wish you could grab the emojis from one slack team and keep them? Maybe you'd put them in another team? Well now you can. This simple little golang CLI will grab all the emojis and put them in ./emojis.

# Setup

You need one module that isn't in the stdlib.

`go get -u github.com/nlopes/slack`

# Build

`go build slack_emoji_grabber.go`

# Configure
To run the `slack_emoji_grabber` you need your `SLACK_TOKEN` environment variable set. If you don't have it set, it won't work.

# Run
`./slack_emoji_grabber`


# License
WTFPL (c) 2019 Michael Stahnke
