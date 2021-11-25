### Prerequies
 - [Install Ruby](https://www.ruby-lang.org/en/documentation/installation)
 - [Install the gems Bundler & Jekyll](https://jekyllrb.com)

### Install the project
`bundle install`

### Run the server locally
`bundle exec jekyll serve`

### Deploy the project
First checkout on gh-pages
`git co gh-pages`

Then rebase gh-pages on main branch
`git rebase main`

Finally push the change on the repo
`git push origin gh-pages`