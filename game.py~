import webapp2
from google.appengine.ext.webapp import template

class MainPage(webapp2.RequestHandler):
  def get(self):
      self.response.out.write(template.render("test.html",{}));
      #self.response.headers['Content-Type'] = 'text/plain'
      #self.response.write('Hello, webapp2 World!')

app = webapp2.WSGIApplication([('/', MainPage)],
                              debug=True)
