# logback-db

As of version 1.2.8, logback no longer ships with `DBAppender`.

The logback-db project remedies this omission by providing `DBAppender` for `logback-classic` and `logback-access`.

More specifically, the `logback-classic-db` module contains `DBAppender` for `logback-classic` whereas the `logback-access-db` module contains `DBAppender` for `logback-access`. Both modules require `logback-core-db` module as a prerequisite.

Here are the Maven coordinates for the aforementioned  components:

  `ch.qos.logback.db:logback-core-db:VERSION`  
  `ch.qos.logback.db:logback-classic-db:VERSION`  
  `ch.qos.logback.db:logback-access-db:VERSION`
 
As of 2022-04-20, *1.2.11.1* was the latest release version.

See also https://logback.qos.ch/news.html for the latest available release version.
