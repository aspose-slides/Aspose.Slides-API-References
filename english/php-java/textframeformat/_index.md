---
title: TextFrameFormat
type: docs
weight: 0
url: /php-java/textframeformat/
---

# TextFrameFormat class

  Contains the TextFrame's formatTextFrameFormatting properties.
 

## Constructors

| name | description |
| --- | --- |
| [TextFrameFormat](/php-java/textframeformat/textframeformat/)() | Initializes a new instance of TextFrameFormat class. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getAnchoringType](/php-java/textframeformat/getanchoringtype/)() | byte | Returns or sets vertical anchor text in a TextFrameEx. Read/write TextAnchorType. |
| [getAutofitType](/php-java/textframeformat/getautofittype/)() | byte | Returns or sets text's autofit mode. Read/write TextAutofitType. |
| [getCenterText](/php-java/textframeformat/getcentertext/)() | byte | If NullableBool.True then text should be centered in box horizontally. Read/write NullableBool. |
| [getColumnCount](/php-java/textframeformat/getcolumncount/)() | int | Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int. |
| [getColumnSpacing](/php-java/textframeformat/getcolumnspacing/)() | double | Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double. |
| [getEffective](/php-java/textframeformat/geteffective/)() | ITextFrameFormatEffectiveData | Gets effective text frame formatting data with the inheritance applied. |
| [getKeepTextFlat](/php-java/textframeformat/getkeeptextflat/)() | boolean | Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean. |
| [getMarginBottom](/php-java/textframeformat/getmarginbottom/)() | double | Returns or sets the bottom margin (points) in a TextFrame. Read/write double. |
| [getMarginLeft](/php-java/textframeformat/getmarginleft/)() | double | Returns or sets the left margin (points) in a TextFrame. Read/write double. |
| [getMarginRight](/php-java/textframeformat/getmarginright/)() | double | Returns or sets the right margin (points) in a TextFrame. Read/write double. |
| [getMarginTop](/php-java/textframeformat/getmargintop/)() | double | Returns or sets the top margin (points) in a TextFrame. Read/write double. |
| [getRotationAngle](/php-java/textframeformat/getrotationangle/)() | float | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float. |
| [getTextStyle](/php-java/textframeformat/gettextstyle/)() | ITextStyle | Returns text's style. Read-only ITextStyle. |
| [getTextVerticalType](/php-java/textframeformat/gettextverticaltype/)() | byte | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write TextVerticalType. |
| [getThreeDFormat](/php-java/textframeformat/getthreedformat/)() | IThreeDFormat | Returns the ThreeDFormat object that represents 3d effect properties for a text. Read-only IThreeDFormat. |
| [getTransform](/php-java/textframeformat/gettransform/)() | byte | Gets or sets text wrapping shape. Read/write TextShapeType. |
| [getWrapText](/php-java/textframeformat/getwraptext/)() | byte | True if text is wrapped at TextFrame's margins. Read/write NullableBool. |
| [setAnchoringType](/php-java/textframeformat/setanchoringtype/)(byte) | void | Returns or sets vertical anchor text in a TextFrameEx. Read/write TextAnchorType. |
| [setAutofitType](/php-java/textframeformat/setautofittype/)(byte) | void | Returns or sets text's autofit mode. Read/write TextAutofitType. |
| [setCenterText](/php-java/textframeformat/setcentertext/)(byte) | void | If NullableBool.True then text should be centered in box horizontally. Read/write NullableBool. |
| [setColumnCount](/php-java/textframeformat/setcolumncount/)(int) | void | Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int. |
| [setColumnSpacing](/php-java/textframeformat/setcolumnspacing/)(double) | void | Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double. |
| [setKeepTextFlat](/php-java/textframeformat/setkeeptextflat/)(boolean) | void | Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean. |
| [setMarginBottom](/php-java/textframeformat/setmarginbottom/)(double) | void | Returns or sets the bottom margin (points) in a TextFrame. Read/write double. |
| [setMarginLeft](/php-java/textframeformat/setmarginleft/)(double) | void | Returns or sets the left margin (points) in a TextFrame. Read/write double. |
| [setMarginRight](/php-java/textframeformat/setmarginright/)(double) | void | Returns or sets the right margin (points) in a TextFrame. Read/write double. |
| [setMarginTop](/php-java/textframeformat/setmargintop/)(double) | void | Returns or sets the top margin (points) in a TextFrame. Read/write double. |
| [setRotationAngle](/php-java/textframeformat/setrotationangle/)(float) | void | Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float. |
| [setTextVerticalType](/php-java/textframeformat/settextverticaltype/)(byte) | void | Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write TextVerticalType. |
| [setTransform](/php-java/textframeformat/settransform/)(byte) | void | Gets or sets text wrapping shape. Read/write TextShapeType. |
| [setWrapText](/php-java/textframeformat/setwraptext/)(byte) | void | True if text is wrapped at TextFrame's margins. Read/write NullableBool. |