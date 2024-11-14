---
title: Portion
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/portion/
---

## Portion class

 Represents a portion of text inside a text paragraph.
 
### Portion {#Portion}

| Name | Description |
| --- | --- |
| Portion() | Initializes a new instance of the Portion class. |

 **Returns:**
Portion


---


### Portion {#Portion}

| Name | Description |
| --- | --- |
| Portion(String) | Initializes a new instance of the Portion class. |

 **Returns:**
Portion


---


### Portion {#Portion}

| Name | Description |
| --- | --- |
| Portion([Portion](../portion)) | Initializes a new instance of the Portion class. |

 **Returns:**
Portion


---


### addField {#addField}

| Name | Description |
| --- | --- |
| addField ([FieldType](../fieldtype)) | Converts this portion to the automaticaly updated field. |


---


### addField {#addField}

| Name | Description |
| --- | --- |
| addField (String) | Converts this portion to the automaticaly updated field. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| internalString | String | Internal name of FieldType. |


---


### getCoordinates {#getCoordinates}

| Name | Description |
| --- | --- |
| getCoordinates () | Get coordinates of the beginning of the portion. The X coordinate of point represents the portion beginning from the first character including left side bearing. The Y coordinate includes top side bearing. |

 **Returns:**
Point2D.Float


---


### getField {#getField}

| Name | Description |
| --- | --- |
| getField () | Returns a field of this portion. Read-only IField. |

 **Returns:**
[Field](../field)


---


### getPortionFormat {#getPortionFormat}

| Name | Description |
| --- | --- |
| getPortionFormat () | Returns oformatting bject which contains explicitly set formatting properties of the text portion with no inheritance applied. Read-only IPortionFormat. The formatting object contains the formatting parameters defined for the current portion only, inherited data is not applied. In order to get the effective values including inherited ones use the PortionFormat#getEffective function. |

 **Returns:**
[PortionFormat](../portionformat)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a text. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getRect {#getRect}

| Name | Description |
| --- | --- |
| getRect () | Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones. |

 **Returns:**
Rectangle2D.Float


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a text. Read-only BaseSlide. |

 **Returns:**
[Slide](../slide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [NotesSlide](../notesslide), [BaseSlide](../baseslide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Gets or sets the plain text of a portion. Read/write String. Value: The text. |

 **Returns:**
String


---


### removeField {#removeField}

| Name | Description |
| --- | --- |
| removeField () | Converts this field portion to the simple portion. |


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the plain text of a portion. Read/write String. Value: The text. |


---


