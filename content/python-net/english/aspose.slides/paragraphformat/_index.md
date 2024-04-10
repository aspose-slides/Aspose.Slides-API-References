---
title: ParagraphFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/paragraphformat/
---


ParagraphFormat class

This class contains the paragraph formatting properties. Unlike :py:class:`aspose.slides.IParagraphFormatEffectiveData`, all properties of this class are writeable.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/aspose.slides/pviobject)

The ParagraphFormat type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/paragraphformat/paragraphformat/#/) | Initializes a new instance of :py:class:`aspose.slides.ParagraphFormat` class. |

## Properties

| Property | Description |
| :- | :- |
| [as_i_presentation_component](/slides/python-net/aspose.slides/paragraphformat/as_i_presentation_component/) | Allows to get base IPresentationComponent interface.<br/>            Read-only :py:class:`aspose.slides.IPresentationComponent`. |
| [alignment](/slides/python-net/aspose.slides/paragraphformat/alignment/) | Returns or sets the text alignment in a paragraph with no inheritance.<br/>            Read/write :py:enum:`aspose.slides.TextAlignment`. |
| [space_within](/slides/python-net/aspose.slides/paragraphformat/space_within/) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied.<br/>            Read/write :py:class:`float`. |
| [space_before](/slides/python-net/aspose.slides/paragraphformat/space_before/) | Returns or sets the amount of space before the first line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write :py:class:`float`. |
| [space_after](/slides/python-net/aspose.slides/paragraphformat/space_after/) | Returns or sets the amount of space after the last line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write :py:class:`float`. |
| [east_asian_line_break](/slides/python-net/aspose.slides/paragraphformat/east_asian_line_break/) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [right_to_left](/slides/python-net/aspose.slides/paragraphformat/right_to_left/) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [latin_line_break](/slides/python-net/aspose.slides/paragraphformat/latin_line_break/) | Determines whether the Latin line break is used in a paragraph. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [hanging_punctuation](/slides/python-net/aspose.slides/paragraphformat/hanging_punctuation/) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [margin_left](/slides/python-net/aspose.slides/paragraphformat/margin_left/) | Returns or sets the left margin in a paragraph with no inheritance.<br/>            Read/write :py:class:`float`. |
| [margin_right](/slides/python-net/aspose.slides/paragraphformat/margin_right/) | Returns or sets the right margin in a paragraph with no inheritance.<br/>            Read/write :py:class:`float`. |
| [indent](/slides/python-net/aspose.slides/paragraphformat/indent/) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values.<br/>            Read/write :py:class:`float`. |
| [default_tab_size](/slides/python-net/aspose.slides/paragraphformat/default_tab_size/) | Returns or sets default tabulation size with no inheritance.<br/>            Read/write :py:class:`float`. |
| [tabs](/slides/python-net/aspose.slides/paragraphformat/tabs/) | Returns tabulations of a paragraph. No inheritance applied.<br/>            Read-only :py:class:`aspose.slides.ITabCollection`. |
| [font_alignment](/slides/python-net/aspose.slides/paragraphformat/font_alignment/) | Returns or sets a font alignment in a paragraph with no inheritance.<br/>            Read/write :py:enum:`aspose.slides.FontAlignment`. |
| [slide](/slides/python-net/aspose.slides/paragraphformat/slide/) |  |
| [presentation](/slides/python-net/aspose.slides/paragraphformat/presentation/) |  |
| [bullet](/slides/python-net/aspose.slides/paragraphformat/bullet/) |  |
| [depth](/slides/python-net/aspose.slides/paragraphformat/depth/) |  |
| [default_portion_format](/slides/python-net/aspose.slides/paragraphformat/default_portion_format/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_effective](/slides/python-net/aspose.slides/paragraphformat/paragraphformat/#/) | Gets effective paragraph formatting data with the inheritance applied. |


### Remarks


This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use 
 method 
            which returns a 
 instance.



