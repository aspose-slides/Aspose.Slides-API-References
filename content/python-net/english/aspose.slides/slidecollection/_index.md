---
title: SlideCollection class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidecollection/
---


## SlideCollection class

Represents a collection of a slides.

The SlideCollection type exposes the following members:

Gets the element at the specified index.
            Read-only [`Slide`](/slides/python-net/aspose.slides/slide).

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/aspose.slides/slidecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_clone(self, source_slide)`](/slides/python-net/aspose.slides/slidecollection/add_clone/#islide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone(self, source_slide, section)`](/slides/python-net/aspose.slides/slidecollection/add_clone/#islide-isection) | Adds a copy of a specified slide to the end of the specified section. |
| [`add_clone(self, source_slide, dest_layout)`](/slides/python-net/aspose.slides/slidecollection/add_clone/#islide-ilayoutslide) | Adds a copy of a specified slide to the end of the collection. |
| [`add_clone(self, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/aspose.slides/slidecollection/add_clone/#islide-imasterslide-bool) | Adds a copy of a specified source slide to the end of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [`insert_clone(self, index, source_slide)`](/slides/python-net/aspose.slides/slidecollection/insert_clone/#int-islide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone(self, index, source_slide, dest_layout)`](/slides/python-net/aspose.slides/slidecollection/insert_clone/#int-islide-ilayoutslide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout)`](/slides/python-net/aspose.slides/slidecollection/insert_clone/#int-islide-imasterslide-bool) | Inserts a copy of a specified source slide to specified position of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [`to_array(self)`](/slides/python-net/aspose.slides/slidecollection/to_array/#) | Creates and returns an array with all slides in it. |
| [`to_array(self, start_index, count)`](/slides/python-net/aspose.slides/slidecollection/to_array/#int-int) | Creates and returns an array with all slides from the specified range in it.<br/>            An index of a first slide to add.A number of slides to add. |
| [`reorder(self, index, slide)`](/slides/python-net/aspose.slides/slidecollection/reorder/#int-islide) | Moves slide from the collection to the specified position. |
| [`reorder(self, index, slides)`](/slides/python-net/aspose.slides/slidecollection/reorder/#int-listislide) | Moves slides from the collection to the specified position.<br/>            Slides will be placed starting from index in order they appear in list. |
| [`add_from_pdf(self, path)`](/slides/python-net/aspose.slides/slidecollection/add_from_pdf/#str) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_pdf(self, path, pdf_import_options)`](/slides/python-net/aspose.slides/slidecollection/add_from_pdf/#str-asposeslidesimportingpdfimportoptions) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [`add_from_pdf(self, pdf_stream)`](/slides/python-net/aspose.slides/slidecollection/add_from_pdf/#iorawiobase) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_pdf(self, pdf_stream, pdf_import_options)`](/slides/python-net/aspose.slides/slidecollection/add_from_pdf/#iorawiobase-asposeslidesimportingpdfimportoptions) | Creates slides from the PDF document and adds them to the end of the collection. |
| [`add_from_html(self, html_text, resolver, uri)`](/slides/python-net/aspose.slides/slidecollection/add_from_html/#str-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html(self, html_text)`](/slides/python-net/aspose.slides/slidecollection/add_from_html/#str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html(self, html_stream, resolver, uri)`](/slides/python-net/aspose.slides/slidecollection/add_from_html/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and adds them to the end of the collection. |
| [`add_from_html(self, html_stream)`](/slides/python-net/aspose.slides/slidecollection/add_from_html/#iorawiobase) | Creates slides from HTML text and adds them to the end of the collection. |
| [`insert_from_html(self, index, html_text, resolver, uri)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-str-asposeslidesimportingiexternalresourceresolver-str-bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_text)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_text, use_slide_with_index_as_start)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-str-bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_stream, resolver, uri)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_stream)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`insert_from_html(self, index, html_stream, use_slide_with_index_as_start)`](/slides/python-net/aspose.slides/slidecollection/insert_from_html/#int-iorawiobase-bool) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [`add_empty_slide(self, layout)`](/slides/python-net/aspose.slides/slidecollection/add_empty_slide/#ilayoutslide) | Adds a new empty slide to the end of the collection. |
| [`insert_empty_slide(self, index, layout)`](/slides/python-net/aspose.slides/slidecollection/insert_empty_slide/#int-ilayoutslide) | Inserts a copy of a specified slide to specified position of the collection. |
| [`remove(self, value)`](/slides/python-net/aspose.slides/slidecollection/remove/#islide) | Removes the first occurrence of a specific object from the collection. |
| [`remove_at(self, index)`](/slides/python-net/aspose.slides/slidecollection/remove_at/#int) | Removes the element at the specified index of the collection. |
| [`index_of(self, slide)`](/slides/python-net/aspose.slides/slidecollection/index_of/#islide) | Returns an index of the specified slide in the collection. |


### See Also
* class [`Slide`](/slides/python-net/aspose.slides/slide)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

