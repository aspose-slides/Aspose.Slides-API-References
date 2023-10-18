---
title: ParagraphFormat
second_title: Aspose.Sildes for PHP via Java API Reference
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

 **Result:**
ParagraphFormat


---


### getAlignment {#getAlignment}

| Name | Description |
| --- | --- |
| getAlignment () | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

 **Returns:**
int


---


### getBullet {#getBullet}

| Name | Description |
| --- | --- |
| getBullet () | Returns bullet format of the paragraph. Read-only IBulletFormat. |

 **Returns:**
[BulletFormat](../bulletformat)


---


### getDefaultPortionFormat {#getDefaultPortionFormat}

| Name | Description |
| --- | --- |
| getDefaultPortionFormat () | Returns default portion format of a paragraph. No inheritance applied. Read-only IPortionFormat. |

 **Returns:**
[PortionFormat](../portionformat)


---


### getDefaultTabSize {#getDefaultTabSize}

| Name | Description |
| --- | --- |
| getDefaultTabSize () | Returns or sets default tabulation size with no inheritance. Read/write float. |

 **Returns:**
float


---


### getDepth {#getDepth}

| Name | Description |
| --- | --- |
| getDepth () | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

 **Returns:**
short


---


### getEastAsianLineBreak {#getEastAsianLineBreak}

| Name | Description |
| --- | --- |
| getEastAsianLineBreak () | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective paragraph formatting data with the inheritance applied. |

 **Returns:**
ParagraphFormatEffectiveData


---


### getFontAlignment {#getFontAlignment}

| Name | Description |
| --- | --- |
| getFontAlignment () | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

 **Returns:**
int


---


### getHangingPunctuation {#getHangingPunctuation}

| Name | Description |
| --- | --- |
| getHangingPunctuation () | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getIndent {#getIndent}

| Name | Description |
| --- | --- |
| getIndent () | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

 **Returns:**
float


---


### getLatinLineBreak {#getLatinLineBreak}

| Name | Description |
| --- | --- |
| getLatinLineBreak () | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

 **Returns:**
float


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

 **Returns:**
float


---


### getRightToLeft {#getRightToLeft}

| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
byte


---


### getSpaceAfter {#getSpaceAfter}

| Name | Description |
| --- | --- |
| getSpaceAfter () | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Returns:**
float


---


### getSpaceBefore {#getSpaceBefore}

| Name | Description |
| --- | --- |
| getSpaceBefore () | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Returns:**
float


---


### getSpaceWithin {#getSpaceWithin}

| Name | Description |
| --- | --- |
| getSpaceWithin () | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

 **Returns:**
float


---


### getTabs {#getTabs}

| Name | Description |
| --- | --- |
| getTabs () | Returns tabulations of a paragraph. No inheritance applied. Read-only ITabCollection. |

 **Returns:**
[TabCollection](../tabcollection)


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### setAlignment {#setAlignment}

| Name | Description |
| --- | --- |
| setAlignment (int) | Returns or sets the text alignment in a paragraph with no inheritance. Read/write TextAlignment. |

 **Returns:**
void


---


### setDefaultTabSize {#setDefaultTabSize}

| Name | Description |
| --- | --- |
| setDefaultTabSize (float) | Returns or sets default tabulation size with no inheritance. Read/write float. |

 **Returns:**
void


---


### setDepth {#setDepth}

| Name | Description |
| --- | --- |
| setDepth (short) | Returns or sets depth of the paragraph. Value 0 means undefined value. Read/write short. |

 **Returns:**
void


---


### setEastAsianLineBreak {#setEastAsianLineBreak}

| Name | Description |
| --- | --- |
| setEastAsianLineBreak (byte) | Determines whether the East Asian line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
void


---


### setFontAlignment {#setFontAlignment}

| Name | Description |
| --- | --- |
| setFontAlignment (int) | Returns or sets a font alignment in a paragraph with no inheritance. Read/write FontAlignment. |

 **Returns:**
void


---


### setHangingPunctuation {#setHangingPunctuation}

| Name | Description |
| --- | --- |
| setHangingPunctuation (byte) | Determines whether the hanging punctuation is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
void


---


### setIndent {#setIndent}

| Name | Description |
| --- | --- |
| setIndent (float) | Returns or sets paragraph First Line Indent/Hanging Indent with no inheritance. Hanging Indent can be defined with negative values. Read/write float. |

 **Returns:**
void


---


### setLatinLineBreak {#setLatinLineBreak}

| Name | Description |
| --- | --- |
| setLatinLineBreak (byte) | Determines whether the Latin line break is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
void


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (float) | Returns or sets the left margin in a paragraph with no inheritance. Read/write float. |

 **Returns:**
void


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (float) | Returns or sets the right margin in a paragraph with no inheritance. Read/write float. |

 **Returns:**
void


---


### setRightToLeft {#setRightToLeft}

| Name | Description |
| --- | --- |
| setRightToLeft (byte) | Determines whether the Right to Left writing is used in a paragraph. No inheritance applied. Read/write NullableBool. |

 **Returns:**
void


---


### setSpaceAfter {#setSpaceAfter}

| Name | Description |
| --- | --- |
| setSpaceAfter (float) | Returns or sets the amount of space after the last line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Returns:**
void


---


### setSpaceBefore {#setSpaceBefore}

| Name | Description |
| --- | --- |
| setSpaceBefore (float) | Returns or sets the amount of space before the first line in a paragraph with no inheritance. A positive value specifies the percentage of the font size that the white space should be. A negative value specifies the size of the white space in point size. Read/write float. |

 **Returns:**
void


---


### setSpaceWithin {#setSpaceWithin}

| Name | Description |
| --- | --- |
| setSpaceWithin (float) | Returns or sets the amount of space between base lines in a paragraph. Positive value means percentage, negative - size in points. No inheritance applied. Read/write float. |

 **Returns:**
void


---


