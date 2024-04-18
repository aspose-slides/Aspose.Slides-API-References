---
title: ISlideCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidecollection/
---


## ISlideCollection class

Represents a collection of a slides.

The ISlideCollection type exposes the following members:

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/islidecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone/#islide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone/#islide-isection) | Adds a copy of a specified slide to the end of the specified section. |
| [`add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone/#islide-ilayoutslide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone`](/slides/python-net/aspose.slides/islidecollection/add_clone/#islide-imasterslide-bool) | Adds a copy of a specified source slide to the end of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [`insert_clone`](/slides/python-net/aspose.slides/islidecollection/insert_clone/#int-islide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone`](/slides/python-net/aspose.slides/islidecollection/insert_clone/#int-islide-ilayoutslide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone`](/slides/python-net/aspose.slides/islidecollection/insert_clone/#int-islide-imasterslide-bool) | Inserts a copy of a specified source slide to specified position of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [`to_array`](/slides/python-net/aspose.slides/islidecollection/to_array/#) | Creates and returns an array with all slides in it. |
| [`to_array`](/slides/python-net/aspose.slides/islidecollection/to_array/#int-int) | Creates and returns an array with all slides from the specified range in it. |
| [`reorder`](/slides/python-net/aspose.slides/islidecollection/reorder/#int-islide) | Moves slide from the collection to the specified position. |
| [`reorder`](/slides/python-net/aspose.slides/islidecollection/reorder/#int-listislide) | Moves slides from the collection to the specified position.<br/>            Slides will be placed starting from index in order they appear in list. |
| [`add_from_pdf`](/slides/python-net/aspose.slides/islidecollection/add_from_pdf/#str) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_pdf`](/slides/python-net/aspose.slides/islidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [`add_from_pdf`](/slides/python-net/aspose.slides/islidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_pdf`](/slides/python-net/aspose.slides/islidecollection/add_from_pdf/#iorawiobase) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_html`](/slides/python-net/aspose.slides/islidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html`](/slides/python-net/aspose.slides/islidecollection/add_from_html/#str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html`](/slides/python-net/aspose.slides/islidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html`](/slides/python-net/aspose.slides/islidecollection/add_from_html/#iorawiobase) | Creates slides from HTML text and adds them to the end of the collection. |
| [`insert_from_html`](/slides/python-net/aspose.slides/islidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html`](/slides/python-net/aspose.slides/islidecollection/insert_from_html/#int-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html`](/slides/python-net/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html`](/slides/python-net/aspose.slides/islidecollection/insert_from_html/#int-iorawiobase) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`add_empty_slide`](/slides/python-net/aspose.slides/islidecollection/add_empty_slide/#ilayoutslide) | Adds a new empty slide to the end of the collection. |
| [`insert_empty_slide`](/slides/python-net/aspose.slides/islidecollection/insert_empty_slide/#int-ilayoutslide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`remove`](/slides/python-net/aspose.slides/islidecollection/remove/#islide) | Removes the first occurrence of a specific object from the collection. |
| [`remove_at`](/slides/python-net/aspose.slides/islidecollection/remove_at/#int) | Removes the element at the specified index of the collection. |
| [`index_of`](/slides/python-net/aspose.slides/islidecollection/index_of/#islide) | Returns an index of the specified slide in the collection. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

