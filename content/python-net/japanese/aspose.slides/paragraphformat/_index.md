---
title: ParagraphFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraphformat/
---
## ParagraphFormat クラス

This class contains the paragraph formatting properties. Unlike [`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata), all properties of this class are writeable.

**Inheritance:**[`ParagraphFormat`](/slides/python-net/ja/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

The ParagraphFormat type exposes the following members:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/paragraphformat/__init__/#) | Initializes a new instance of [`ParagraphFormat`](/slides/python-net/ja/aspose.slides/paragraphformat) class. |

## プロパティ

| Property | Description |
| :- | :- |
| [`alignment`](/slides/python-net/ja/aspose.slides/paragraphformat/alignment/) | Returns or sets the text alignment in a paragraph with no inheritance.<br/>            Read/write [`TextAlignment`](/slides/python-net/ja/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/ja/aspose.slides/paragraphformat/space_within/) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied.<br/>            Read/write **float**. |
| [`space_before`](/slides/python-net/ja/aspose.slides/paragraphformat/space_before/) | Returns or sets the amount of space before the first line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write **float**. |
| [`space_after`](/slides/python-net/ja/aspose.slides/paragraphformat/space_after/) | Returns or sets the amount of space after the last line in a paragraph with no inheritance.<br/>            A positive value specifies the percentage of the font size that the white space should be.<br/>            A negative value specifies the size of the white space in point size.<br/>            Read/write **float**. |
| [`east_asian_line_break`](/slides/python-net/ja/aspose.slides/paragraphformat/east_asian_line_break/) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/ja/aspose.slides/paragraphformat/right_to_left/) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/ja/aspose.slides/paragraphformat/latin_line_break/) | Determines whether the Latin line break is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/ja/aspose.slides/paragraphformat/hanging_punctuation/) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied.<br/>            Read/write [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/ja/aspose.slides/paragraphformat/margin_left/) | Returns or sets the left margin in a paragraph with no inheritance.<br/>            Read/write **float**. |
| [`margin_right`](/slides/python-net/ja/aspose.slides/paragraphformat/margin_right/) | Returns or sets the right margin in a paragraph with no inheritance.<br/>            Read/write **float**. |
| [`indent`](/slides/python-net/ja/aspose.slides/paragraphformat/indent/) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values.<br/>            Read/write **float**. |
| [`default_tab_size`](/slides/python-net/ja/aspose.slides/paragraphformat/default_tab_size/) | Returns or sets default tabulation size with no inheritance.<br/>            Read/write **float**. |
| [`tabs`](/slides/python-net/ja/aspose.slides/paragraphformat/tabs/) | Returns tabulations of a paragraph. No inheritance applied.<br/>            Read-only [`ITabCollection`](/slides/python-net/ja/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/ja/aspose.slides/paragraphformat/font_alignment/) | Returns or sets a font alignment in a paragraph with no inheritance.<br/>            Read/write [`FontAlignment`](/slides/python-net/ja/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/ja/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/ja/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/ja/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/ja/aspose.slides/paragraphformat/default_portion_format/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/paragraphformat/get_effective/#) | Gets effective paragraph formatting data with the inheritance applied. |

### 備考

This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [`ParagraphFormat.get_effective`](/slides/python-net/ja/aspose.slides/paragraphformat/get_effective) method 
            which returns a [`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata) instance.

### 参照
* クラス [`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata)
* クラス [`ParagraphFormat`](/slides/python-net/ja/aspose.slides/paragraphformat)
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)