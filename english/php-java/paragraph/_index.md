---
title: Paragraph
type: docs
weight: 0
url: /php-java/paragraph/
---

# Paragraph class

 Represents a paragraph of text.
 

## Constructors

| name | description |
| --- | --- |
| [Paragraph](/php-java/paragraph/paragraph/)() | Initializes a new instance of the Paragraph class with default properties. |
| [Paragraph](/php-java/paragraph/paragraph/)(Paragraph) | Copy constructor that initializes a new instance of a Paragraph class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getEndParagraphPortionFormat](/php-java/paragraph/getendparagraphportionformat/)() | IPortionFormat | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [getParagraphFormat](/php-java/paragraph/getparagraphformat/)() | IParagraphFormat | Returns the formatting object for this paragraph. Read-only IParagraphFormat. The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied. In order to get the effective values including inherited ones use the ParagraphFormat#getEffective method. |
| [getPortions](/php-java/paragraph/getportions/)() | IPortionCollection | Returns the collection of a text portions. Read-only IPortionCollection. |
| [getPresentation](/php-java/paragraph/getpresentation/)() | IPresentation | Returns the parent presentation of a paragraph. Read-only IPresentation. |
| [getRect](/php-java/paragraph/getrect/)() | Float | Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones. |
| [getSlide](/php-java/paragraph/getslide/)() | IBaseSlide | Returns the parent slide of a paragraph. Read-only BaseSlide. |
| [getText](/php-java/paragraph/gettext/)() | String | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |
| [joinPortionsWithSameFormatting](/php-java/paragraph/joinportionswithsameformatting/)() | void | Joins runs with same formatting. |
| [setEndParagraphPortionFormat](/php-java/paragraph/setendparagraphportionformat/)(IPortionFormat) | void | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setText](/php-java/paragraph/settext/)(String) | void | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |
