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
### ParagraphFormat {#ParagraphFormat}

| Name | Description |
| --- | --- |
| ParagraphFormat() | Initializes a new instance of ParagraphFormat class. |

 **Result**
ParagraphFormat


---


### getAlignment {#getAlignment}

| Name | Description |
| --- | --- |
| getAlignment () | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

 **Result**
int


---


### getBullet {#getBullet}

| Name | Description |
| --- | --- |
| getBullet () | Returns bullet format of the paragraph. Read-only IBulletFormat. |

 **Result**
[BulletFormat](../bulletformat)


---


### getDefaultPortionFormat {#getDefaultPortionFormat}

| Name | Description |
| --- | --- |
| getDefaultPortionFormat () | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |

 **Result**
[PortionFormat](../portionformat)


---


### getDefaultTabSize {#getDefaultTabSize}

| Name | Description |
| --- | --- |
| getDefaultTabSize () | Returns or sets default tabulation size with no inheritance. Read/write float. |

 **Result**
float


---


### getDepth {#getDepth}

| Name | Description |
| --- | --- |
| getDepth () | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

 **Result**
short


---


### getEastAsianLineBreak {#getEastAsianLineBreak}

| Name | Description |
| --- | --- |
| getEastAsianLineBreak () | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result**
byte


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective paragraph formatting data with the inheritance applied. |

 **Result**
ParagraphFormatEffectiveData


---


### getFontAlignment {#getFontAlignment}

| Name | Description |
| --- | --- |
| getFontAlignment () | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

 **Result**
int


---


### getHangingPunctuation {#getHangingPunctuation}

| Name | Description |
| --- | --- |
| getHangingPunctuation () | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result**
byte


---


### getIndent {#getIndent}

| Name | Description |
| --- | --- |
| getIndent () | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

 **Result**
float


---


### getLatinLineBreak {#getLatinLineBreak}

| Name | Description |
| --- | --- |
| getLatinLineBreak () | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result**
byte


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

 **Result**
float


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

 **Result**
float


---


### getRightToLeft {#getRightToLeft}

| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Result**
byte


---


### getSpaceAfter {#getSpaceAfter}

| Name | Description |
| --- | --- |
| getSpaceAfter () | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Result**
float


---


### getSpaceBefore {#getSpaceBefore}

| Name | Description |
| --- | --- |
| getSpaceBefore () | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Result**
float


---


### getSpaceWithin {#getSpaceWithin}

| Name | Description |
| --- | --- |
| getSpaceWithin () | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

 **Result**
float


---


### getTabs {#getTabs}

| Name | Description |
| --- | --- |
| getTabs () | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |

 **Result**
[TabCollection](../tabcollection)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Result**
long


---


### setAlignment {#setAlignment}

| Name | Description |
| --- | --- |
| setAlignment (int) | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |


---


### setDefaultTabSize {#setDefaultTabSize}

| Name | Description |
| --- | --- |
| setDefaultTabSize (float) | Returns or sets default tabulation size with no inheritance. Read/write float. |


---


### setDepth {#setDepth}

| Name | Description |
| --- | --- |
| setDepth (short) | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |


---


### setEastAsianLineBreak {#setEastAsianLineBreak}

| Name | Description |
| --- | --- |
| setEastAsianLineBreak (byte) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setFontAlignment {#setFontAlignment}

| Name | Description |
| --- | --- |
| setFontAlignment (int) | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |


---


### setHangingPunctuation {#setHangingPunctuation}

| Name | Description |
| --- | --- |
| setHangingPunctuation (byte) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setIndent {#setIndent}

| Name | Description |
| --- | --- |
| setIndent (float) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |


---


### setLatinLineBreak {#setLatinLineBreak}

| Name | Description |
| --- | --- |
| setLatinLineBreak (byte) | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (float) | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (float) | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |


---


### setRightToLeft {#setRightToLeft}

| Name | Description |
| --- | --- |
| setRightToLeft (byte) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |


---


### setSpaceAfter {#setSpaceAfter}

| Name | Description |
| --- | --- |
| setSpaceAfter (float) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


### setSpaceBefore {#setSpaceBefore}

| Name | Description |
| --- | --- |
| setSpaceBefore (float) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |


---


### setSpaceWithin {#setSpaceWithin}

| Name | Description |
| --- | --- |
| setSpaceWithin (float) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |


---


