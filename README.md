# WeAreNotWaiting

This page will act as a portal page to various WeAreNotWaiting projects. Stay tuned!

## Contributing

To suggest changes, fork this repository, edit the files, and submit your changes as a pull request.

The developer discussion of Nightscout happens on our Discord channel at https://discord.gg/zg7CvCQ

### Previewing Changes
To preview your work as you edit you must set up two python packages that are used to create this site using [MkDocs](http://www.mkdocs.org/). They are `mkdocs`, and `mkdocs-bootswatch`.

Review [Properly Installing Python](http://docs.python-guide.org/en/latest/starting/installation/) for help getting Python installed. MkDocs works with Python 2.7, 3.3+, and pypy.

* Install python modules

```bash
$ cd <nightscout docs location>
$ pip install -r requirements.txt
```

* Run mkdocs server locally
```bash
$ cd <nightscout docs location>
$ mkdocs serve
```

* Preview docs in browser. Most changes will update automatically as you edit. Configuration and navigation changes will require restarting the mkdocs server.
* Optionally, you can share the preview with others by uploading them to your repository's `gh-pages` branch
```bash
$ mkdocs gh-deploy
```
