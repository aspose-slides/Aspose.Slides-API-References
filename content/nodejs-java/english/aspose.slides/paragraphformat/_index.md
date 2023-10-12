---
title: ParagraphFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/paragraphformat/
---

## ParagraphFormat class

 This class contains the paragraph formatting properties. Unlike  IParagraphFormatEffectiveData, all properties of this class are writeable.
 This class is used to return and manipulate paragraph formatting properties defined for the particular paragraph. This means that
 no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".
 In order to get the effective formatting parameter values including inherited you need to use  ParagraphFormat#getEffective method 
 which returns a  IParagraphFormatEffectiveData instance.
| Name | Description |
| --- | --- |
| ParagraphFormat() | Initializes a new instance of ParagraphFormat class. |

### Result
ParagraphFormat


---


| Name | Description |
| --- | --- |
| getAlignment () | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

### Result
int


---


| Name | Description |
| --- | --- |
| getBullet () | Returns bullet format of the paragraph. Read-only IBulletFormat. |

### Result
BulletFormat(../../bulletformat)


---


| Name | Description |
| --- | --- |
| getDefaultPortionFormat () | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |

### Result
PortionFormat(../../portionformat)


---


| Name | Description |
| --- | --- |
| getDefaultTabSize () | Returns or sets default tabulation size with no inheritance. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getDepth () | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

### Result
short


---


| Name | Description |
| --- | --- |
| getEastAsianLineBreak () | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getEffective () | Gets effective paragraph formatting data with the inheritance applied. |

### Result
ParagraphFormatEffectiveData


---


| Name | Description |
| --- | --- |
| getFontAlignment () | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

### Result
int


---


| Name | Description |
| --- | --- |
| getHangingPunctuation () | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getIndent () | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getLatinLineBreak () | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getSpaceAfter () | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getSpaceBefore () | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getSpaceWithin () | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

### Result
float


---


| Name | Description |
| --- | --- |
| getTabs () | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |

### Result
TabCollection(../../tabcollection)


---


| Name | Description |
| --- | --- |
| getVersion () |  |

### Result
long


---


| Name | Description |
| --- | --- |
| setAlignment (int) | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |


---


| Name | Description |
| --- | --- |
| setDefaultTabSize (float) | Returns or sets default tabulation size with no inheritance. Read/write float. |


---


| Name | Description |
| --- | --- |
| setDepth (short) | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |


---


| Name | Description |
| --- | --- |
| setEastAsianLineBreak (byte) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| Name | Description |
| --- | --- |
| setFontAlignment (int) | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |


---


| Name | Description |
| --- | --- |
| setHangingPunctuation (byte) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| Name | Description |
| --- | --- |
| setIndent (float) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |


---


| Name | Description |
| --- | --- |
| setLatinLineBreak (byte) | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| Name | Description |
| --- | --- |
| setMarginLeft (float) | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |


---


| Name | Description |
| --- | --- |
| setMarginRight (float) | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |


---


| Name | Description |
| --- | --- |
| setRightToLeft (byte) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


| Name | Description |
| --- | --- |
| setSpaceAfter (float) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


| Name | Description |
| --- | --- |
| setSpaceBefore (float) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


| Name | Description |
| --- | --- |
| setSpaceWithin (float) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |


---


