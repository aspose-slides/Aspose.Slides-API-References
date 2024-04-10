---
title: ISlideCollection
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidecollection/
---


ISlideCollection class

Represents a collection of a slides.

The ISlideCollection type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [as_i_collection](/slides/python-net/aspose.slides/islidecollection/as_i_collection/) |  |
| [as_i_enumerable](/slides/python-net/aspose.slides/islidecollection/as_i_enumerable/) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |

## Methods

| Method | Description |
| :- | :- |
| [add_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide/) | Adds a copy of a specified slide to the end of the collection. |
| [add_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide-ISection/) | Adds a copy of a specified slide to the end of the specified section. |
| [add_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide-ILayoutSlide/) | Adds a copy of a specified slide to the end of the collection. |
| [add_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide-IMasterSlide-bool/) | Adds a copy of a specified source slide to the end of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [insert_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-ISlide/) | Inserts a copy of a specified slide to specified position of the collection. |
| [insert_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-ISlide-ILayoutSlide/) | Inserts a copy of a specified slide to specified position of the collection. |
| [insert_clone](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-ISlide-IMasterSlide-bool/) | Inserts a copy of a specified source slide to specified position of the collection.<br/>            Appropriate layout will be selected automatically from the specified <br/>            master (appropriate layout is the layout with the same Type or Name as <br/>            of layout of the source slide). If there is no appropriate layout then<br/>            layout of the source slide will be cloned (if allowCloneMissingLayout <br/>            is true) or PptxEditException will be thrown (if allowCloneMissingLayout<br/>            is false). |
| [to_array](/slides/python-net/aspose.slides/islidecollection/islidecollection/#/) | Creates and returns an array with all slides in it. |
| [to_array](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-int/) | Creates and returns an array with all slides from the specified range in it. |
| [reorder](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-ISlide/) | Moves slide from the collection to the specified position. |
| [reorder](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-List[ISlide]/) | Moves slides from the collection to the specified position.<br/>            Slides will be placed starting from index in order they appear in list. |
| [add_from_pdf](/slides/python-net/aspose.slides/islidecollection/islidecollection/#string/) | Creates slides from the PDF document and adds them to the end of the collection. |
| [add_from_pdf](/slides/python-net/aspose.slides/islidecollection/islidecollection/#string-aspose.slides.importing.PdfImportOptions/) | Creates slides from the PDF document and adds them to the end of the collection considering the pdf import options. |
| [add_from_pdf](/slides/python-net/aspose.slides/islidecollection/islidecollection/#System.IO.Stream-aspose.slides.importing.PdfImportOptions/) | Creates slides from the PDF document and adds them to the end of the collection. |
| [add_from_pdf](/slides/python-net/aspose.slides/islidecollection/islidecollection/#System.IO.Stream/) | Creates slides from the PDF document and adds them to the end of the collection. |
| [add_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#string-aspose.slides.importing.IExternalResourceResolver-string/) | Creates slides from HTML text and adds them to the end of the collection. |
| [add_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#string/) | Creates slides from HTML text and adds them to the end of the collection. |
| [add_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#System.IO.Stream-aspose.slides.importing.IExternalResourceResolver-string/) | Creates slides from HTML text and adds them to the end of the collection. |
| [add_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#System.IO.Stream/) | Creates slides from HTML text and adds them to the end of the collection. |
| [insert_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-string-aspose.slides.importing.IExternalResourceResolver-string/) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insert_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-string/) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insert_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-System.IO.Stream-aspose.slides.importing.IExternalResourceResolver-string/) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [insert_from_html](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-System.IO.Stream/) | Creates slides from HTML text and inserts them to the collection at the specified position. |
| [add_empty_slide](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ILayoutSlide/) | Adds a new empty slide to the end of the collection. |
| [insert_empty_slide](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int-ILayoutSlide/) | Inserts a copy of a specified slide to specified position of the collection. |
| [remove](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide/) | Removes the first occurrence of a specific object from the collection. |
| [remove_at](/slides/python-net/aspose.slides/islidecollection/islidecollection/#int/) | Removes the element at the specified index of the collection. |
| [index_of](/slides/python-net/aspose.slides/islidecollection/islidecollection/#ISlide/) | Returns an index of the specified slide in the collection. |

