Software Carpentry Slideshows
=============================
To navigate slideshows, use arrow keys
(<kbd>←</kbd><kbd>→</kbd> or <kbd>↓</kbd><kbd>↑</kbd>).

#### Ideas

*  [Introducing Software Carpentry](http://swcarpentry.github.io/slideshows/introducing-software-carpentry/index.html)
*  [Software Carpentry: Lessons Learned](http://swcarpentry.github.io/slideshows/lessons-learned/index.html)
*  [Best Practices for Scientific Computing](http://swcarpentry.github.io/slideshows/best-practices/index.html)

#### Tutorials

*  [Creating a Workshop Website](http://swcarpentry.github.io/slideshows/creating-website/index.html)
*  [Creating a Lesson](http://swcarpentry.github.io/slideshows/creating-lesson/index.html)

#### 대한민국 소프트웨어 카펜트리 

- 소프트웨어 카펜트리 교재
*  [GitHub 저장소](https://github.com/statkclee/xwmooc-sc)
*  [xwMOOC 소프트웨어 카펜트리](http://xwmooc.net/swcarpentry/)
- 소프트웨어 카펜트리 워크샵
*  [한국전파진흥협회(RAPA)](http://statkclee.github.io/2015-02-25-seoul/)
*  [경기콘텐츠코리아랩](http://statkclee.github.io/2015-04-29-pangyo/)
*  [연세대학교](http://statkclee.github.io/2015-06-29-yonsei/)
*  [나노종합기술원 대전창조경제혁신센터](http://statkclee.github.io/2015-08-20-daejeon/)
- [소프트웨어 카펜트리 1년...](./korea/index.html)



Visualizing Presentations Locally
---------------------------------

If you get a popup message mentioning that the timing file could not be loaded,
the problem may be your browser refusing to dynamically load files
(such as the timing file)
from the local filesystem.
The solution is to start a webserver and access the presentation through it:

1.  Go to the root of the repository.
2.  Run `python -m SimpleHTTPServer 7777` (or with Python 3: `python3 -m http.server 7777`).
3.  View the presentations at `http://localhost:7777`.

Alternatively, if you are using Google Chrome, start it with `chrome --disable-web-security`.
**Warning:** for security reasons, you should not navigate the open web with this option enabled.
