# scrapy-random-fake-ua
Random User-Agent middleware

Installation
-------------

The simplest way is to install it via `pip`:

    pip install scrapy-random-fake-ua

Configuration
-------------

settings.py

    DOWNLOADER_MIDDLEWARES = {
        'scrapy_random_fake_ua.middleware.RandomUserAgentMiddleware': 400,
    }


