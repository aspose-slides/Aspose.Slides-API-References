---
title: ICommentCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/icommentcollection/
---


## ICommentCollection class

Represents a collection of comments of one author.

The ICommentCollection type exposes the following members:

Gets the element at the specified index.
            Read-only [`IComment`](/slides/python-net/aspose.slides/icomment).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/icommentcollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`to_array(self)`](/slides/python-net/aspose.slides/icommentcollection/to_array/#) | Creates and returns an array with all comments. |
| [`to_array(self, start_index, count)`](/slides/python-net/aspose.slides/icommentcollection/to_array/#int-int) | Creates and returns an array with all comments from the specified range. |
| [`add_comment(self, text, slide, position, creation_time)`](/slides/python-net/aspose.slides/icommentcollection/add_comment/#str-islide-asposepydrawingpointf-datetime) | Add new comment at the end of a collection. |
| [`add_modern_comment(self, text, slide, shape, position, creation_time)`](/slides/python-net/aspose.slides/icommentcollection/add_modern_comment/#str-islide-ishape-asposepydrawingpointf-datetime) | Add new modern comment at the end of a collection. |
| [`insert_comment(self, index, text, slide, position, creation_time)`](/slides/python-net/aspose.slides/icommentcollection/insert_comment/#int-str-islide-asposepydrawingpointf-datetime) | Insert new comment to a collection at the specified index. |
| [`insert_modern_comment(self, index, text, slide, shape, position, creation_time)`](/slides/python-net/aspose.slides/icommentcollection/insert_modern_comment/#int-str-islide-ishape-asposepydrawingpointf-datetime) | Insert new modern comment to a collection at the specified index. |
| [`remove_at(self, index)`](/slides/python-net/aspose.slides/icommentcollection/remove_at/#int) | Removes the element at the specified index in a collection. |
| [`remove(self, comment)`](/slides/python-net/aspose.slides/icommentcollection/remove/#icomment) | Removes the first occurrence of the specified comment in a collection. |
| [`clear(self)`](/slides/python-net/aspose.slides/icommentcollection/clear/#) | Removes all comments from a collection. |


### See Also
* class [`IComment`](/slides/python-net/aspose.slides/icomment)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

