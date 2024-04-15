---
title: add_author method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/icommentauthorcollection/add_author/
weight: 10
---


## add_author {#string-string}
Add new author at the end of a collection.

### Returns

New [`ICommentAuthor`](/slides/python-net/aspose.slides/icommentauthor) object.



```python
def add_author(self, name, initials):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | string | Name of a new author. |
| initials | string | Initials of a new author. |

## Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception) | Thrown if author with the same name and initials is already added. |



### See Also
* class [`ICommentAuthor`](/slides/python-net/aspose.slides/icommentauthor)
* class [`ICommentAuthorCollection`](/slides/python-net/aspose.slides/icommentauthorcollection)
* class [`PptxEditException`](/slides/python-net/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
