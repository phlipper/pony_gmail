Pony Gmail
================================

A simple helper library to send email through Gmail or Google Apps via [Pony](http://github.com/benprew/pony). I put this together because I needed to run it both on [Heroku](http://heroku.com/), which uses Ruby 1.8.6, as well as my local development environment running 1.8.7. I also wanted to have a single location to find it next time I need it.

Based on code from the following sources:

* This [blog post](http://blog.jpoz.net/2009/09/02/gmail-heroku-sinatra.html) from [James Pozdena](http://jpoz.github.com/)
* [This Gist](http://gist.github.com/179967) from the post above
* The smtp_tls patch for Ruby 1.8.7 from [this blog post](http://filiptepper.com/2009/02/11/hint-fixing-smtp_tlsrb-for-ruby-187/)

Many thanks to the above sources for making this possible, and to Heroku for providing a great platform for running Ruby web applications.