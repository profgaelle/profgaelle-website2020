---
title: How to link Zotero with Box
subtitle: ""
date: 2020-10-06T06:45:09.385Z
summary: This is a test summary.
draft: true
featured: false
authors:
  - gaelle-vallee-tourangeau
categories:
  - Blog
image:
  filename: david-travis-wc6mj0krzgw-unsplash.jpg
  focal_point: Smart
  preview_only: false
  caption: Photo by David Travis on Unsplash
---
If you have a large library of articles, you may find the Zotero storage space is too limited. Meanwhile, if you work at a university, you may find that you have unlimited Box storage. Wouldn't it be great if the two could be combined?

Well, there is a way although the service has been deprecated so who knows how long it will last. Long enough I hope because I find it very useful!

You need to do two things to sync your Zotero library with Box.

1. In Box, click on your id icon (top right) and go to *Account Settings*. 
2. Enter a linked email address in the section *Login and Email Addresses*.
3. Set up a password under the section *Authentication* (make a note of it!).
4. In the home of your Box space, create a folder named **zotero** (no uppercase!)
5. In Zotero, go to Preferences... > Sync
6. Under File Syncing, check Sync attachment files in My library using **WebDAV**
7. In the box below, enter the URL: as https://*dav.box.com/dav*
8. Enter your Box linked email address and Password (from steps 2. and 3. above).
9. Check all is in order by clicking Verify Server

Voilà! When you attach a .pdf to your reference, it should now be saved in your zotero folder in Box.

{{% callout warning %}}
The Webdav connection is [no longer officially supported by Box](https://support.box.com/hc/en-us/articles/360043696414-WebDAV-with-Box). I'm not sure what this means, other than this solution might not work well. 
{{% /callout %}}
