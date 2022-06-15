---
title: Portion
type: docs
weight: 0
url: /php-java/portion/
---

# Portion class

 Represents a portion of text inside a text paragraph.
 

## Constructors

| name | description |
| --- | --- |
| [Portion](/slides/php-java/portion/portion/)() | Initializes a new instance of the Portion class. |
| [Portion](/slides/php-java/portion/portion/)(String) | Initializes a new instance of the Portion class. |
| [Portion](/slides/php-java/portion/portion/)(Portion) | Initializes a new instance of the Portion class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [addField](/slides/php-java/portion/addfield/)(IFieldType) | void | Converts this portion to the automaticaly updated field. |
| [addField](/slides/php-java/portion/addfield/)(String) | void | Converts this portion to the automaticaly updated field. |
| [getCoordinates](/slides/php-java/portion/getcoordinates/)() | Float | Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing. |
| [getField](/slides/php-java/portion/getfield/)() | IField | Returns a field of this portion. Read-only IField. |
| [getPortionFormat](/slides/php-java/portion/getportionformat/)() | IPortionFormat | Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only IPortionFormat. The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied. In order to get the effective values including inherited ones use the PortionFormat#getEffective method. |
| [getPresentation](/slides/php-java/portion/getpresentation/)() | IPresentation | Returns the parent presentation of a text. Read-only IPresentation. |
| [getRect](/slides/php-java/portion/getrect/)() | Float | Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones. |
| [getSlide](/slides/php-java/portion/getslide/)() | IBaseSlide | Returns the parent slide of a text. Read-only BaseSlide. |
| [getText](/slides/php-java/portion/gettext/)() | String | Gets or sets the plain text of a portion. Read/write String. Value: The text. |
| [removeField](/slides/php-java/portion/removefield/)() | void | Converts this field portion to the simple portion. |
| [setText](/slides/php-java/portion/settext/)(String) | void | Gets or sets the plain text of a portion. Read/write String. Value: The text. |
