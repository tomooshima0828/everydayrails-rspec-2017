# *Everyday Rails Testing with RSpec* sample application (2017 edition)

Refer to the [Everyday Rails] blog for news on this edition of the book. You
can find sample source for earlier editions in the [everydayrails
organization] on GitHub. Thanks!

---

Sample Rails 5.1 application for *[Everyday Rails Testing with RSpec]: A
Practical Approach to Test-driven Development* by Aaron Sumner. This
repository demonstrates incremental testing of an existing application,
starting with an untested codebase and working through model, controller,
feature, and request specs.

Each chapter's progress has a specific branch in this repository. See chapter
1 of the book for details.

Using Git, you can check out each version by name. See details in the book.

If you're not comfortable with Git, you can also use GitHub's handy branch/tag
filter to select a specific tag and browse the source code online. To learn
more about Git, I recommend the free resources [Git Immersion] or [Try Git].

[Everyday Rails]: https://everydayrails.com
[everydayrails organization]: https://github.com/everydayrails
[Everyday Rails Testing with RSpec]: https://leanpub.com/everydayrailsrspec
[Git Immersion]: http://gitimmersion.com/
[Try Git]: http://www.codeschool.com/courses/try-git

M2 MacBook Air 2022-11-13
Ruby 2.6.8, Rails 5.1.7 動作を確認
M2でRuby2.6.8をインストールするときにエラーが発生
解決 https://kenzoblog.vercel.app/posts/m1-chip
RUBY_CFLAGS="-w" rbenv install 2.6.8

# RSpecコマンド
bin/rspec
