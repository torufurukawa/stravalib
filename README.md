# stravalib


**IMPORTANT**
This is currently under active development.  Not even tested yet.

This is GAE compatible fork of [stravalib](https://github.com/hozn/stravalib) project, please check details therein.

GAE (Google App Engine) is incompatible with outgoing [SSL](http://stackoverflow.com/questions/9762685/using-the-requests-python-library-in-google-app-engine) connection done by [requests](http://docs.python-requests.org/en/latest/) version used by original stravalib. This fork uses [google.appengine.api.urlfetch](https://cloud.google.com/appengine/docs/python/urlfetch/) instead.
