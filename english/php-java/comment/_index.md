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
| [getAuthor](/slides/php-java/comment/getauthor/)() | ICommentAuthor | Returns the author of a comment. Read-only ICommentAuthor. |
| [getCreatedTime](/slides/php-java/comment/getcreatedtime/)() | Date | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |
| [getParentComment](/slides/php-java/comment/getparentcomment/)() | IComment | Gets or sets parent comment. Read/write IComment. |
| [getPosition](/slides/php-java/comment/getposition/)() | Float | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |
| [getSlide](/slides/php-java/comment/getslide/)() | ISlide | Returns or sets the parent slide of a comment. Read-only ISlide. |
| [getText](/slides/php-java/comment/gettext/)() | String | Returns or sets the plain text of a slide comment. Read/write String. |
| [remove](/slides/php-java/comment/remove/)() | void | Removes comment and all its replies from the parent collection. |
| [setCreatedTime](/slides/php-java/comment/setcreatedtime/)(Date) | void | Returns or sets the time of a comment creation. Setting this property to java.util.Date(Long.MIN_VALUE) means no comment time is set. Read/write java.util.Date. Comment time is an optional parameter. |
| [setParentComment](/slides/php-java/comment/setparentcomment/)(IComment) | void | Gets or sets parent comment. Read/write IComment. |
| [setPosition](/slides/php-java/comment/setposition/)(Point2D.Float) | void | Returns or sets the position of a comment on a slide. Read/write java.awt.geom.Point2D.Float. |
| [setText](/slides/php-java/comment/settext/)(String) | void | Returns or sets the plain text of a slide comment. Read/write String. |
