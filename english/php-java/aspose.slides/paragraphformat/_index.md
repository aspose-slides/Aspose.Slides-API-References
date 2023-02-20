---
title: ParagraphFormat
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/paragraphformat/
---

## ParagraphFormat class

 This class contains the paragraph formatting properties. Unlike  IParagraphFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  ParagraphFormat#getEffective method 
 which returns a  IParagraphFormatEffectiveData instance.

## Constructors

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Initializes a new instance of ParagraphFormat class. |

## Methods

| Name | Description |
| --- | --- |
| [getAlignment](getalignment)() | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |
| [getBullet](getbullet)() | Returns bullet format of the paragraph. Read-only IBulletFormat. |
| [getDefaultPortionFormat](getdefaultportionformat)() | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |
| [getDefaultTabSize](getdefaulttabsize)() | Returns or sets default tabulation size with no inheritance. Read/write float. |
| [getDepth](getdepth)() | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |
| [getEastAsianLineBreak](geteastasianlinebreak)() | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getEffective](geteffective)() | Gets effective paragraph formatting data with the inheritance applied. |
| [getFontAlignment](getfontalignment)() | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |
| [getHangingPunctuation](gethangingpunctuation)() | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getIndent](getindent)() | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |
| [getLatinLineBreak](getlatinlinebreak)() | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getMarginLeft](getmarginleft)() | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |
| [getMarginRight](getmarginright)() | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |
| [getRightToLeft](getrighttoleft)() | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getSpaceAfter](getspaceafter)() | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [getSpaceBefore](getspacebefore)() | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [getSpaceWithin](getspacewithin)() | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |
| [getTabs](gettabs)() | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |
| [getVersion](getversion)() |  |
| [setAlignment](setalignment)(int) | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |
| [setDefaultTabSize](setdefaulttabsize)(float) | Returns or sets default tabulation size with no inheritance. Read/write float. |
| [setDepth](setdepth)(short) | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |
| [setEastAsianLineBreak](seteastasianlinebreak)(byte) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setFontAlignment](setfontalignment)(int) | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |
| [setHangingPunctuation](sethangingpunctuation)(byte) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setIndent](setindent)(float) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |
| [setLatinLineBreak](setlatinlinebreak)(byte) | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setMarginLeft](setmarginleft)(float) | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |
| [setMarginRight](setmarginright)(float) | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |
| [setRightToLeft](setrighttoleft)(byte) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setSpaceAfter](setspaceafter)(float) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [setSpaceBefore](setspacebefore)(float) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [setSpaceWithin](setspacewithin)(float) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |
