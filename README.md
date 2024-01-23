# Let Me Know (When You Finish)!
[![Open Source Starter Files](https://github.com/nrminor/letmeknow/actions/workflows/open-source-starter.yml/badge.svg)](https://github.com/nrminor/letmeknow/actions/workflows/open-source-starter.yml) [![Rust CI](https://github.com/nrminor/letmeknow/actions/workflows/rust-ci.yml/badge.svg)](https://github.com/nrminor/letmeknow/actions/workflows/rust-ci.yml)

Wrap any command with `lmk` to get notification banners emails, or texts on exit code 0 (Work in progress!)

### The vision
At minimum, the command line interface for `lmk` will look like:

```
lmk <ANY_COMMAND>
```

This will give you a local notification banner through the operating system.

For more advanced usage, the interface could look like this:

```
lmk \
--task-label "Let me know Test" \
--email <YOUR_EMAIL> \
--phone <YOUR_PHONE_NUMBER> \
--no-banner \
--track memory,cpu,time \
<YOUR_COMMAND>
```
