﻿---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iportion/
---


## IPortion class

Represents a portion of text inside a text paragraph.

The IPortion type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/aspose.slides/iportion/portion_format/) | Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied.<br/>            Read-only [`IPortionFormat`](/slides/python-net/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/aspose.slides/iportion/text/) | Gets or sets the plain text of a portion.<br/>            Read/write **str**. |
| [`field`](/slides/python-net/aspose.slides/iportion/field/) | Returns a field of this portion.<br/>            Read-only [`IField`](/slides/python-net/aspose.slides/ifield). |
| [`slide`](/slides/python-net/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides/iportion/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_field`](/slides/python-net/aspose.slides/iportion/add_field/#ifieldtype) | Converts this portion to the automaticaly updated field. |
| [`add_field`](/slides/python-net/aspose.slides/iportion/add_field/#str) | Converts this portion to the automaticaly updated field. |
| [`remove_field`](/slides/python-net/aspose.slides/iportion/remove_field/#) | Converts this field portion to the simple portion. |
| [`get_rect`](/slides/python-net/aspose.slides/iportion/get_rect/#) | Get coordinates of rect that bounds portion. The rect includes all the lines of<br/>             text in portion, including empty ones. |
| [`get_coordinates`](/slides/python-net/aspose.slides/iportion/get_coordinates/#) | Get coordinates of the beginning of the portion. The X coordinate of point represents the <br/>            portion beginning from the first character including left side bearing. The Y coordinate <br/>            includes top side bearing. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

