---
layout: news_post
title: "Ruby 2.1.3 發佈"
author: "nagachika"
translator: "Juanito Fatas"
date: 2014-09-19 12:00:00 +0000
lang: zh_tw
---

很高興宣佈我們發佈了 Ruby 2.1.3。這是 2.1 穩定版的一次補丁發佈。

本次發佈對進行完整 GC 的時間點做了修正，以減少記憶體的使用量（參見 [Bug #9607](https://bugs.ruby-lang.org/issues/9607)，並修復了許多錯誤。

參考 [Tickets](https://bugs.ruby-lang.org/projects/ruby-21/issues?set_filter=1&amp;status_id=5)
以及 [ChangeLog](http://svn.ruby-lang.org/repos/ruby/tags/v2_1_3/ChangeLog) 來了解更多細節。

## 下載

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.bz2](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.bz2)

      SIZE:   11998074 bytes
      MD5:    02b7da3bb06037c777ca52e1194efccb
      SHA256: 36ce72f84ae4129f6cc66e33077a79d87b018ea7bf1dbc3d353604bf006f76d6
      SHA512: 9b48adb161e5e4550a71f61252c8edf59944affb82250babcb64240749af4b672e4a54ccd0feac5b36ea447a358b350b5080125ef2d4acf6e9e8b1ab82612f48

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.gz](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.gz)

      SIZE:   15129183 bytes
      MD5:    74a37b9ad90e4ea63c0eed32b9d5b18f
      SHA256: 0818beb7b10ce9a058cd21d85cfe1dcd233e98b7342d32e9a5d4bebe98347f01
      SHA512: 364c391f669a37917ab1ee0c01d8430763d0c958c6d06fe5c3632d6e81316cafcae8b392b680d64c1692744585ac9286cb6408d7514e8a1f4dbd88ee314be99e

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.xz](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.tar.xz)

      SIZE:   9358664 bytes
      MD5:    fbc50ae56e7ac74501c8955abc248d34
      SHA256: 28832f4c198f7ee3909ee01d30aac7a3ec4eb1968f8f2db22b0b052329c3075c
      SHA512: 87290ab55ff51bf48e8f8b419ab24170cef7eee458b8b684dc64ce60dceca8a1e9d527975b032e89c693880c22a57853d5fc93e247c38682320c8831006c48ca

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.zip](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.3.zip)

      SIZE:   16652733 bytes
      MD5:    06bcee40bb2da9408c41ac3e49918f1f
      SHA256: 855981e029d90092f56f540b0e32f27aaa788db53f6e554abfb24982bf537909
      SHA512: d6b06edcab5f6b70810f838ba942ec5072f7018c0b21709884126d997bbd06028ef74f4b2f7bf439255e165599ee6a94e097bcfc52b72d5cfbf16b2e4476316f


## 發佈記

這次的發行版要感謝許多提交者、測試者以及熱心回報錯誤的使用者的幫助，感謝他們的貢獻。
