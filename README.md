Scribble
========

Forked from https://github.com/muan/scribble


---

### Run it locally
```bash
git clone https://github.com/nickscript0/scribble.git
docker-compose up -d
# Go to http://hostname:4000/ in a web browser
```



### Options

When writing a post, there are 3 options you can add to the header.

1. **disqus: y**<br />
  If disqus is set to 'y', at the end of the post there will be a disqus thread, just like this one. To use disqus, you MUST [set up your own disqus account](http://disqus.com/).

2. **share: y**<br />
  An option for showing tweet and like button under a post.

3. **date**: 2013-05-06 18:07:17<br />
  Date is not a required header since Jekyll reads the file name for date, this was added in only for the **signoff time**. (as shown at the end of this post) If you don't want the signoff time, go into `/includes/signoff.html` remove the `<span>`, and remove `{% include signoff.html %}` from `/layouts/post.html`.
