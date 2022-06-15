---
title: Comment
type: docs
weight: 0
url: /php-java/comment/
---

# Comment class

 Represents a comment on a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAuthor](/php-java/comment/getauthor/)() | ICommentAuthor | Returns the author of a comment. Read-only ICommentAuthor. |
| [getCreatedTime](/php-java/comment/getcreatedtime/)() | Date | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |
| [getParentComment](/php-java/comment/getparentcomment/)() | IComment | Gets or sets parent comment. Read/write IComment. |
| [getPosition](/php-java/comment/getposition/)() | Float | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |
| [getSlide](/php-java/comment/getslide/)() | ISlide | Returns or sets the parent slide of a comment. Read-only ISlide. |
| [getText](/php-java/comment/gettext/)() | String | Returns or sets the plain text of a slide comment. Read/write String. |
| [remove](/php-java/comment/remove/)() | void | Removes comment and all its replies from the parent collection. |
| [setCreatedTime](/php-java/comment/setcreatedtime/)(Date) | void | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |
| [setParentComment](/php-java/comment/setparentcomment/)(IComment) | void | Gets or sets parent comment. Read/write IComment. |
| [setPosition](/php-java/comment/setposition/)(Point2D.Float) | void | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |
| [setText](/php-java/comment/settext/)(String) | void | Returns or sets the plain text of a slide comment. Read/write String. |
