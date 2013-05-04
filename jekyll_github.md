#JekyllBoolstrap setup on github.

- Make a repository named <username/organization>.github.io
- Clone the repo
- Make branch 'source' for source code as the 'master' branch will be used to store the jekyll output files (content of _site). 
  - git checkout -b source
  - git push -u origin source 
- To fetch the JekyllBootstrap and keep track of original repo : Add a remote branch 
  - git remote add jekyll-bootstrap https://github.com/plusjade/jekyll-bootstrap.git
  - git fetch jekyll-bootstrap
  - git merge jekyll-bootstrap/master
- Add Jekyll and RedCloth to Gemfile.
  - gem "jekyll"
  - gem "RedCloth", "~> 4.2.9"
- Try running jekyll locally, visit http://localhost:4000
  - bundle exec jekyll --server
  - visit http://localhost:4000



