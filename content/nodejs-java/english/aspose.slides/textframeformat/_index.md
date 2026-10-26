---
title: TextFrameFormat
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/textframeformat/
---

## TextFrameFormat class

  Contains the TextFrame's formatTextFrameFormatting properties.
 
### TextFrameFormat {#TextFrameFormat}

| Name | Description |
| --- | --- |
| TextFrameFormat() | Initializes a new instance of TextFrameFormat class. |

 **Returns:**
TextFrameFormat


---


### getAnchoringType {#getAnchoringType}

| Name | Description |
| --- | --- |
| getAnchoringType () | Returns or sets vertical anchor text in a TextFrame. Read/write TextAnchorType. |

 **Returns:**
byte


---


### getAutofitType {#getAutofitType}

| Name | Description |
| --- | --- |
| getAutofitType () | Returns or sets text's autofit mode. Read/write TextAutofitType. |

 **Returns:**
byte


---


### getCenterText {#getCenterText}

| Name | Description |
| --- | --- |
| getCenterText () | If NullableBool.True then text should be centered in box horizontally. Read/write NullableBool. |

 **Returns:**
byte


---


### getColumnCount {#getColumnCount}

| Name | Description |
| --- | --- |
| getColumnCount () | Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int. |

 **Returns:**
int


---


### getColumnSpacing {#getColumnSpacing}

| Name | Description |
| --- | --- |
| getColumnSpacing () | Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double. |

 **Returns:**
double


---


### getEffective {#getEffective}

| Name | Description |
| --- | --- |
| getEffective () | Gets effective text frame formatting data with the inheritance applied. |

 **Returns:**
TextFrameFormatEffectiveData


---


### getKeepTextFlat {#getKeepTextFlat}

| Name | Description |
| --- | --- |
| getKeepTextFlat () | Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean. |

 **Returns:**
boolean


---


### getMarginBottom {#getMarginBottom}

| Name | Description |
| --- | --- |
| getMarginBottom () | Returns or sets the bottom margin (points) in a TextFrame. Read/write double. |

 **Returns:**
double


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin (points) in a TextFrame. Read/write double. |

 **Returns:**
double


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin (points) in a TextFrame. Read/write double. |

 **Returns:**
double


---


### getMarginTop {#getMarginTop}

| Name | Description |
| --- | --- |
| getMarginTop () | Returns or sets the top margin (points) in a TextFrame. Read/write double. |

 **Returns:**
double


---


### getRotationAngle {#getRotationAngle}

| Name | Description |
| --- | --- |
| getRotationAngle () | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float. |

 **Returns:**
float


---


### getTextStyle {#getTextStyle}

| Name | Description |
| --- | --- |
| getTextStyle () | Returns text's style. Read-only ITextStyle. |

 **Returns:**
[TextStyle](../textstyle)


---


### getTextVerticalType {#getTextVerticalType}

| Name | Description |
| --- | --- |
| getTextVerticalType () | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write TextVerticalType. |

 **Returns:**
byte


---


### getThreeDFormat {#getThreeDFormat}

| Name | Description |
| --- | --- |
| getThreeDFormat () | Returns the ThreeDFormat object that represents 3d effect properties for a text. Read-only IThreeDFormat. |

 **Returns:**
[ThreeDFormat](../threedformat)


---


### getTransform {#getTransform}

| Name | Description |
| --- | --- |
| getTransform () | Gets or sets text wrapping shape. Read/write TextShapeType. |

 **Returns:**
byte


---


### getVersion {#getVersion}

| Name | Description |
| --- | --- |
| getVersion () |  |

 **Returns:**
long


---


### getWrapText {#getWrapText}

| Name | Description |
| --- | --- |
| getWrapText () | True if text is wrapped at TextFrame's margins. Read/write NullableBool. |

 **Returns:**
byte


---


### setAnchoringType {#setAnchoringType}

| Name | Description |
| --- | --- |
| setAnchoringType (byte) | Returns or sets vertical anchor text in a TextFrame. Read/write TextAnchorType. |


---


### setAutofitType {#setAutofitType}

| Name | Description |
| --- | --- |
| setAutofitType (byte) | Returns or sets text's autofit mode. Read/write TextAutofitType. |


---


### setCenterText {#setCenterText}

| Name | Description |
| --- | --- |
| setCenterText (byte) | If NullableBool.True then text should be centered in box horizontally. Read/write NullableBool. |


---


### setColumnCount {#setColumnCount}

| Name | Description |
| --- | --- |
| setColumnCount (int) | Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int. |


---


### setColumnSpacing {#setColumnSpacing}

| Name | Description |
| --- | --- |
| setColumnSpacing (double) | Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double. |


---


### setKeepTextFlat {#setKeepTextFlat}

| Name | Description |
| --- | --- |
| setKeepTextFlat (boolean) | Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean. |


---


### setMarginBottom {#setMarginBottom}

| Name | Description |
| --- | --- |
| setMarginBottom (double) | Returns or sets the bottom margin (points) in a TextFrame. Read/write double. |


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (double) | Returns or sets the left margin (points) in a TextFrame. Read/write double. |


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (double) | Returns or sets the right margin (points) in a TextFrame. Read/write double. |


---


### setMarginTop {#setMarginTop}

| Name | Description |
| --- | --- |
| setMarginTop (double) | Returns or sets the top margin (points) in a TextFrame. Read/write double. |


---


### setRotationAngle {#setRotationAngle}

| Name | Description |
| --- | --- |
| setRotationAngle (float) | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float. |


---


### setTextVerticalType {#setTextVerticalType}

| Name | Description |
| --- | --- |
| setTextVerticalType (byte) | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write TextVerticalType. |


---


### setTransform {#setTransform}

| Name | Description |
| --- | --- |
| setTransform (byte) | Gets or sets text wrapping shape. Read/write TextShapeType. |


---


### setWrapText {#setWrapText}

| Name | Description |
| --- | --- |
| setWrapText (byte) | True if text is wrapped at TextFrame's margins. Read/write NullableBool. |


---


