# Just Read

**Copy and paste URL to get just the text content of that site.**


This is a really simple parser based off [Rodrigo's data extraction code](http://rodp.me/2015/how-to-extract-data-from-the-web.html). If you are like me and tired of seeing ads, images, links, videos, weird text - then you should try this. 

[Try it out here](http://justread.duckdns.org)


# Requirements

- Python 2.7+

# Setup

Install using

```bash
pip install -r requirements.txt
```

To run just use

```bash
python justread.py
```

or 

```bash
gunicorn -w 4 -b 127.0.0.1:8009 justread:app
```

# Todo

- Add "Share this" link

# Known Issues

- Code snippets filtered out
- Formatting removed
- Leftover bits (Image Caption, Advertisement keywords)

# Features

- Similar to Pocket, but without the use of Pocket!
- Don't need to save anything
- Hackable
- FAST (roughly 200-600 ms to load any page)
