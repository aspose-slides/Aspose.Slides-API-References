---
title: Paragraph
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraph/
---

## Paragraph class

 Represents a paragraph of text.
 

## Constructors

| Name | Description |
| --- | --- |
| [Paragraph](paragraph)() | Initializes a new instance of the Paragraph class with default properties. |
| [Paragraph](paragraph)([Paragraph](../paragraph)) | Copy constructor that initializes a new instance of a Paragraph class. |

## Methods

| Name | Description |
| --- | --- |
| [getEndParagraphPortionFormat](getendparagraphportionformat)() | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [getParagraphFormat](getparagraphformat)() | Returns the formatting object for this paragraph. Read-only IParagraphFormat. The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied. In order to get the effective values including inherited ones use the ParagraphFormat#getEffective method. |
| [getPortions](getportions)() | Returns the collection of a text portions. Read-only IPortionCollection. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a paragraph. Read-only IPresentation. |
| [getRect](getrect)() | Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones. |
| [getSlide](getslide)() | Returns the parent slide of a paragraph. Read-only BaseSlide. |
| [getText](gettext)() | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |
| [joinPortionsWithSameFormatting](joinportionswithsameformatting)() | Joins runs with same formatting. |
| [setEndParagraphPortionFormat](setendparagraphportionformat)([PortionFormat](../portionformat)) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |
| [setText](settext)(String) | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |
