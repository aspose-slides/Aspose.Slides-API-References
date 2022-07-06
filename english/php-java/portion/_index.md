---
title: Portion
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/portion/
---

## Portion class

 Represents a portion of text inside a text paragraph.
 

## Constructors

| Name | Description |
| --- | --- |
| [Portion](portion)() | Initializes a new instance of the Portion class. |
| [Portion](portion)(String) | Initializes a new instance of the Portion class. |
| [Portion](portion)(Portion) | Initializes a new instance of the Portion class. |

## Methods

| Name | Description |
| --- | --- |
| [addField](addfield)([FieldType](../FieldType)) | Converts this portion to the automaticaly updated field. |
| [addField](addfield)(String) | Converts this portion to the automaticaly updated field. |
| [getCoordinates](getcoordinates)() | Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing. |
| [getField](getfield)() | Returns a field of this portion. Read-only IField. |
| [getPortionFormat](getportionformat)() | Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only IPortionFormat. The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied. In order to get the effective values including inherited ones use the PortionFormat#getEffective method. |
| [getPresentation](getpresentation)() | Returns the parent presentation of a text. Read-only IPresentation. |
| [getRect](getrect)() | Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones. |
| [getSlide](getslide)() | Returns the parent slide of a text. Read-only BaseSlide. |
| [getText](gettext)() | Gets or sets the plain text of a portion. Read/write String. Value: The text. |
| [removeField](removefield)() | Converts this field portion to the simple portion. |
| [setText](settext)(String) | Gets or sets the plain text of a portion. Read/write String. Value: The text. |
