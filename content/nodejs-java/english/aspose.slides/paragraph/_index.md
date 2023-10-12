---
title: Paragraph
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraph/
---

## Paragraph class

 Represents a paragraph of text.
 
| Name | Description |
| --- | --- |
| Paragraph() | Initializes a new instance of the Paragraph class with default properties. |

### Result
Paragraph


---


| Name | Description |
| --- | --- |
| Paragraph(Paragraph(../paragraph)) | Copy function that initializes a new instance of a Paragraph class. |

### Result
Paragraph


---


| Name | Description |
| --- | --- |
| getEndParagraphPortionFormat () | Specifies the portion properties that are to be used if another portion is inserted after the last one. |

### Result
PortionFormat(../../portionformat)


---


| Name | Description |
| --- | --- |
| getParagraphFormat () | Returns the formatting object for this paragraph. Read-only IParagraphFormat. The formatting object contains the formatting parameters defined for the current paragraph only, inherited data is not applied. In order to get the effective values including inherited ones use the ParagraphFormat#getEffective function. |

### Result
ParagraphFormat(../../paragraphformat)


---


| Name | Description |
| --- | --- |
| getPortions () | Returns the collection of a text portions. Read-only IPortionCollection. |

### Result
PortionCollection(../../portioncollection)


---


| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a paragraph. Read-only IPresentation. |

### Result
Presentation(../../presentation)


---


| Name | Description |
| --- | --- |
| getRect () | Get coordinates of rect that bounds paragraph. The rect includes all the lines of text in paragraph, including empty ones. |

### Result
Rectangle2D.Float


---


| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a paragraph. Read-only BaseSlide. |

### Result
MasterNotesSlide(../../masternotesslide), MasterHandoutSlide(../../masterhandoutslide), BaseSlide(../../baseslide), NotesSlide(../../notesslide), LayoutSlide(../../layoutslide), Slide(../../slide), MasterSlide(../../masterslide)


---


| Name | Description |
| --- | --- |
| getText () | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |

### Result
String


---


| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | Joins runs with same formatting. |


---


| Name | Description |
| --- | --- |
| setEndParagraphPortionFormat (PortionFormat(../portionformat)) | Specifies the portion properties that are to be used if another portion is inserted after the last one. |


---


| Name | Description |
| --- | --- |
| setText (String) | Gets or sets the the plain text of a paragraph. Read/write String. Value: The text. |


---


