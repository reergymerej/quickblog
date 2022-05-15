# quickblog

Use this to quickly add a blog entry.


## Setup

Install node tool.
```
   npm i -g getfrontmatter
```

Add the path to your blog in `.env`


## Usage

./main source-file.md


This will show a couple prompts then create the file, commit, and publish.

If you're lazy, make `blog` available from everywhere.

```sh
ln -s (realpath main) /usr/local/bin/blog
```
