﻿---
title: ModernComment class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/moderncomment/
---


## ModernComment class

Represents a comment on a slide.

**Inheritance:**[`ModernComment`](/slides/python-net/aspose.slides/moderncomment) → [`Comment`](/slides/python-net/aspose.slides/comment)

The ModernComment type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`text`](/slides/python-net/aspose.slides/moderncomment/text/) | Returns or sets the plain text of a slide comment.<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/aspose.slides/moderncomment/created_time/) | Returns or sets the time of a comment creation.<br/>            Setting this property to **System.DateTime** means no comment time is set.<br/>            Read/write **System.DateTime**. |
| [`slide`](/slides/python-net/aspose.slides/moderncomment/slide/) | Returns or sets the parent slide of a comment.<br/>            Read-only [`ISlide`](/slides/python-net/aspose.slides/islide). |
| [`author`](/slides/python-net/aspose.slides/moderncomment/author/) | Returns the author of a comment.<br/>            Read-only [`ICommentAuthor`](/slides/python-net/aspose.slides/icommentauthor). |
| [`position`](/slides/python-net/aspose.slides/moderncomment/position/) | Returns or sets the position of a comment on a slide.<br/>            Read/write **aspose.pydrawing.PointF**. |
| [`parent_comment`](/slides/python-net/aspose.slides/moderncomment/parent_comment/) | Gets or sets parent comment.<br/>            Read/write [`IComment`](/slides/python-net/aspose.slides/icomment). |
| [`shape`](/slides/python-net/aspose.slides/moderncomment/shape/) | Returns a shape associated with the comment.<br/>            Read-only [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`text_selection_start`](/slides/python-net/aspose.slides/moderncomment/text_selection_start/) | Gets or sets starting position of text selection in text frame if the comment associated with AutoShape.<br/>            Read/write **int**. |
| [`text_selection_length`](/slides/python-net/aspose.slides/moderncomment/text_selection_length/) | Gets or sets text selection length in text frame if the comment associated with AutoShape.<br/>            Read/write **int**. |
| [`status`](/slides/python-net/aspose.slides/moderncomment/status/) | Gets or sets the status of the comment.<br/>            Read/write [`ModernCommentStatus`](/slides/python-net/aspose.slides/moderncommentstatus). |

## Methods

| Method | Description |
| :- | :- |
| [`remove`](/slides/python-net/aspose.slides/moderncomment/remove/#) | Removes comment and all its replies from the parent collection. |


### See Also
* class [`Comment`](/slides/python-net/aspose.slides/comment)
* class [`ModernComment`](/slides/python-net/aspose.slides/moderncomment)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

