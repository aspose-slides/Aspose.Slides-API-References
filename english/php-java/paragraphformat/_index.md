---
title: ParagraphFormat
type: docs
weight: 0
url: /php-java/paragraphformat/
---

# ParagraphFormat class

 This class contains the paragraph formatting properties. Unlike  IParagraphFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  ParagraphFormat#getEffective method 
 which returns a  IParagraphFormatEffectiveData instance.

## Constructors

| name | description |
| --- | --- |
| [ParagraphFormat](/slides/php-java/paragraphformat/paragraphformat/)() | Initializes a new instance of ParagraphFormat class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAlignment](/slides/php-java/paragraphformat/getalignment/)() | int | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |
| [getBullet](/slides/php-java/paragraphformat/getbullet/)() | IBulletFormat | Returns bullet format of the paragraph. Read-only IBulletFormat. |
| [getDefaultPortionFormat](/slides/php-java/paragraphformat/getdefaultportionformat/)() | IPortionFormat | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |
| [getDefaultTabSize](/slides/php-java/paragraphformat/getdefaulttabsize/)() | float | Returns or sets default tabulation size with no inheritance. Read/write float. |
| [getDepth](/slides/php-java/paragraphformat/getdepth/)() | short | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |
| [getEastAsianLineBreak](/slides/php-java/paragraphformat/geteastasianlinebreak/)() | byte | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getEffective](/slides/php-java/paragraphformat/geteffective/)() | IParagraphFormatEffectiveData | Gets effective paragraph formatting data with the inheritance applied. |
| [getFontAlignment](/slides/php-java/paragraphformat/getfontalignment/)() | int | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |
| [getHangingPunctuation](/slides/php-java/paragraphformat/gethangingpunctuation/)() | byte | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getIndent](/slides/php-java/paragraphformat/getindent/)() | float | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |
| [getLatinLineBreak](/slides/php-java/paragraphformat/getlatinlinebreak/)() | byte | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getMarginLeft](/slides/php-java/paragraphformat/getmarginleft/)() | float | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |
| [getMarginRight](/slides/php-java/paragraphformat/getmarginright/)() | float | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |
| [getRightToLeft](/slides/php-java/paragraphformat/getrighttoleft/)() | byte | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [getSpaceAfter](/slides/php-java/paragraphformat/getspaceafter/)() | float | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [getSpaceBefore](/slides/php-java/paragraphformat/getspacebefore/)() | float | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [getSpaceWithin](/slides/php-java/paragraphformat/getspacewithin/)() | float | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |
| [getTabs](/slides/php-java/paragraphformat/gettabs/)() | ITabCollection | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |
| [getVersion](/slides/php-java/paragraphformat/getversion/)() | long |  |
| [setAlignment](/slides/php-java/paragraphformat/setalignment/)(int) | void | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |
| [setDefaultTabSize](/slides/php-java/paragraphformat/setdefaulttabsize/)(float) | void | Returns or sets default tabulation size with no inheritance. Read/write float. |
| [setDepth](/slides/php-java/paragraphformat/setdepth/)(short) | void | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |
| [setEastAsianLineBreak](/slides/php-java/paragraphformat/seteastasianlinebreak/)(byte) | void | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setFontAlignment](/slides/php-java/paragraphformat/setfontalignment/)(int) | void | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |
| [setHangingPunctuation](/slides/php-java/paragraphformat/sethangingpunctuation/)(byte) | void | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setIndent](/slides/php-java/paragraphformat/setindent/)(float) | void | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |
| [setLatinLineBreak](/slides/php-java/paragraphformat/setlatinlinebreak/)(byte) | void | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setMarginLeft](/slides/php-java/paragraphformat/setmarginleft/)(float) | void | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |
| [setMarginRight](/slides/php-java/paragraphformat/setmarginright/)(float) | void | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |
| [setRightToLeft](/slides/php-java/paragraphformat/setrighttoleft/)(byte) | void | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |
| [setSpaceAfter](/slides/php-java/paragraphformat/setspaceafter/)(float) | void | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [setSpaceBefore](/slides/php-java/paragraphformat/setspacebefore/)(float) | void | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |
| [setSpaceWithin](/slides/php-java/paragraphformat/setspacewithin/)(float) | void | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |
