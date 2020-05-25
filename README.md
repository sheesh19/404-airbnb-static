# README


Review:

* Controllers: `rails generate controller controller_name` ; Controller has Actions / Methods
* Routes: link url to our controller methods `verb "address", to: "controller#action"`
* Views: displays information from controller actions

* Instance variables are defined in our controllers; we use them in the views
* Params: passed via the form & in the url; params are a hash!

User Stories:


- `rails generate controller flats`

* A home page listing flats

- Make a route from the Home Page: `get "home", to: "flats#index"`
- Controller method: "index"
- View: "index.html.erb"


* A dynamic show page for a specific flat

- Make a route for the Specific Page: `get "flat/:id", to: "flats#show"`
- Controller method: "show"
- View: "show.html.erb"
