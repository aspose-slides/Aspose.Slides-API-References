---
title: IParagraphFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iparagraphformat/
---


IParagraphFormat class

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](/slides/python-net/aspose.slides/iparagraphformateffectivedata), all properties of this class are writeable.

The IParagraphFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [bullet](/slides/python-net/aspose.slides/iparagraphformat/bullet/) | Returns bullet format of the paragraph.<br/>            Read-only [`IBulletFormat`](/slides/python-net/aspose.slides/ibulletformat). |
| [depth](/slides/python-net/aspose.slides/iparagraphformat/depth/) | Returns or sets depth of the paragraph.<br/>            Value 0 means undefined value.<br/>            Read/write .NET type System.Int16. |
| [alignment](/slides/python-net/aspose.slides/iparagraphformat/alignment/) | Returns or sets the text alignment in a paragraph with no inheritance.<br/>            Read/write [`TextAlignment`](/slides/python-net/aspose.slides/textalignment). |
| [space_within](/slides/python-net/aspose.slides/iparagraphformat/space_within/) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied.<br/>            Read/write .NET type System.Single. |
| [space_before](/slides/python-net/aspose.slides/iparagraphformat/space_before/) | Returns or sets the amount of space before the first line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write .NET type System.Single. |
| [space_after](/slides/python-net/aspose.slides/iparagraphformat/space_after/) | Returns or sets the amount of space after the last line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write .NET type System.Single. |
| [east_asian_line_break](/slides/python-net/aspose.slides/iparagraphformat/east_asian_line_break/) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [right_to_left](/slides/python-net/aspose.slides/iparagraphformat/right_to_left/) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [latin_line_break](/slides/python-net/aspose.slides/iparagraphformat/latin_line_break/) | Determines whether the Latin line break is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [hanging_punctuation](/slides/python-net/aspose.slides/iparagraphformat/hanging_punctuation/) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/aspose.slides/nullablebool). |
| [margin_left](/slides/python-net/aspose.slides/iparagraphformat/margin_left/) | Returns or sets the left margin in a paragraph with no inheritance.<br/>            Read/write .NET type System.Single. |
| [margin_right](/slides/python-net/aspose.slides/iparagraphformat/margin_right/) | Returns or sets the right margin in a paragraph with no inheritance.<br/>            Read/write .NET type System.Single. |
| [indent](/slides/python-net/aspose.slides/iparagraphformat/indent/) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values.<br/>            Read/write .NET type System.Single. |
| [default_tab_size](/slides/python-net/aspose.slides/iparagraphformat/default_tab_size/) | Returns or sets default tabulation size with no inheritance.<br/>            Read/write .NET type System.Single. |
| [tabs](/slides/python-net/aspose.slides/iparagraphformat/tabs/) | Returns tabulations of a paragraph. No inheritance applied.<br/>            Read-only [`ITabCollection`](/slides/python-net/aspose.slides/itabcollection). |
| [font_alignment](/slides/python-net/aspose.slides/iparagraphformat/font_alignment/) | Returns or sets a font alignment in a paragraph with no inheritance.<br/>            Read/write [`FontAlignment`](/slides/python-net/aspose.slides/fontalignment). |
| [default_portion_format](/slides/python-net/aspose.slides/iparagraphformat/default_portion_format/) | Returns default portion format of a paragraph. No inheritance applied.<br/>            Read-only [`IPortionFormat`](/slides/python-net/aspose.slides/iportionformat). |

## Methods

| Method | Description |
| :- | :- |
| [get_effective](/slides/python-net/aspose.slides/iparagraphformat/iparagraphformat/#/) | Gets effective paragraph formatting data with the inheritance applied. |


### Remarks

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use [`IParagraphFormat.get_effective`](/slides/python-net/aspose.slides/iparagraphformat/get_effective) method 
            which returns a [`IParagraphFormatEffectiveData`](/slides/python-net/aspose.slides/iparagraphformateffectivedata) instance.

