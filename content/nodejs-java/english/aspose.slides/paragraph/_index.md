---
title: Paragraph
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraph/
---

## Paragraph class

 Represents a paragraph of text.
 
### Paragraph {#Paragraph}

| Name | Description |
| --- | --- |
| Paragraph() | Initializes a new instance of the Paragraph class with default properties. |

 **Result:**
Paragraph


---


### Paragraph {#Paragraph}

| Name | Description |
| --- | --- |
| Paragraph([Paragraph](../paragraph)) | Copy function that initializes a new instance of a Paragraph class. |

 **Result:**
Paragraph


---


### getEndParagraphPortionFormat {#getEndParagraphPortionFormat}

| Name | Description |
| --- | --- |
| getEndParagraphPortionFormat () | Specifies the portion properties that are to be used if another portion is inserted after the last one. |

 **Result:**
[PortionFormat](../portionformat)


---


### getLinesCount {#getLinesCount}

| Name | Description |
| --- | --- |
| getLinesCount () | Get number of lines in a paragraph. |

 **Result:**
int


---


### getParagraphFormat {#getParagraphFormat}

| Name | Description |
| --- | --- |
| getParagraphFormat () | Returns the formatting object for this paragraph. Read-only IParagraphFormat. The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied. In order to get the effective values including inherited ones use the ParagraphFormat#getEffective function. |

 **Result:**
[ParagraphFormat](../paragraphformat)


---


### getPortions {#getPortions}

| Name | Description |
| --- | --- |
| getPortions () | Returns the collection of a text portions. Read-only IPortionCollection. |

 **Result:**
[PortionCollection](../portioncollection)


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a paragraph. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRect {#getRect}

| Name | Description |
| --- | --- |
| getRect () | Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones. |

 **Result:**
Rectangle2D.Float


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a paragraph. Read-only BaseSlide. |

 **Result:**
[NotesSlide](../notesslide), [MasterHandoutSlide](../masterhandoutslide), [LayoutSlide](../layoutslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [Slide](../slide)


---


### getText {#getText}

| Name | Description |
| --- | --- |
| getText () | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |

 **Result:**
String


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting. |


---


### setEndParagraphPortionFormat {#setEndParagraphPortionFormat}

| Name | Description |
| --- | --- |
| setEndParagraphPortionFormat ([PortionFormat](../portionformat)) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |


---


### setText {#setText}

| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |


---


