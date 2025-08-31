---
title: ITextFrame class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/itextframe/
---


## ITextFrame class

Represents a TextFrame.

The ITextFrame type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/aspose.slides/itextframe/paragraphs/) | Returns the list of all paragraphs in a frame.<br/>            Read-only [`IParagraphCollection`](/slides/python-net/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/aspose.slides/itextframe/text/) | Gets or sets the plain text for a TextFrame.<br/>            Read/write **str**. |
| [`text_frame_format`](/slides/python-net/aspose.slides/itextframe/text_frame_format/) | Returns the formatting object for this TextFrame object.<br/>            Read-only [`ITextFrameFormat`](/slides/python-net/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/aspose.slides/itextframe/hyperlink_queries/) | Provides easy access to contained hyperlinks.<br/>            Read-only [`IHyperlinkQueries`](/slides/python-net/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/aspose.slides/itextframe/parent_shape/) | Returns the parent shape or None if the parent object does not implement the IShape interface<br/>            Read-only [`IShape`](/slides/python-net/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/aspose.slides/itextframe/parent_cell/) | Returns the parent cell or None if the parent object does not implement the ICell interface.<br/>            Read-only [`ICell`](/slides/python-net/aspose.slides/icell). |

## Methods

| Method | Description |
| :- | :- |
| [`highlight_text`](/slides/python-net/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text`](/slides/python-net/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-asposeslidesitexthighlightingoptions) | Highlights all matches of the sample text with the specified color. |
| [`highlight_text`](/slides/python-net/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-asposeslidesitextsearchoptions-asposeslidesifindresultcallback) | Highlights all matches of the sample text with the specified color. |
| [`highlight_regex`](/slides/python-net/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) |  |
| [`highlight_regex`](/slides/python-net/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-asposeslidesitexthighlightingoptions) | Highlights all matches of the regular expression with the specified color. |
| [`join_portions_with_same_formatting`](/slides/python-net/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Joins runs with same formatting in all paragraphs. |
| [`split_text_by_columns`](/slides/python-net/aspose.slides/itextframe/split_text_by_columns/#) | Splits the text content of the [`ITextFrame`](/slides/python-net/aspose.slides/itextframe) into an array of strings,  <br/>            where each element corresponds to a separate text column within the frame. |
| [`replace_text`](/slides/python-net/aspose.slides/itextframe/replace_text/#str-str-asposeslidesitextsearchoptions-asposeslidesifindresultcallback) | Replaces all occurrences of the specified text with another specified text. |
| [`replace_regex`](/slides/python-net/aspose.slides/itextframe/replace_regex/#str-str) |  |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

