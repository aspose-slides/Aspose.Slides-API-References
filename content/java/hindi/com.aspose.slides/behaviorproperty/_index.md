---
title: BehaviorProperty
second_title: Aspose.Slides for Java API संदर्भ
description: एनिमेशन व्यवहार के लिए प्रॉपर्टी प्रकारों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/behaviorproperty/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)  
```
public class BehaviorProperty implements IBehaviorProperty
```

ऐनिमेशन व्यवहार के लिए प्रॉपर्टी प्रकारों का प्रतिनिधित्व करता है। यह https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx और https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx से प्रॉपर्टी की सूची का अनुसरण करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getValue()](#getValue--) | प्रॉपर्टी का मान |
| [isCustom()](#isCustom--) | दिखाता है कि यह प्रॉपर्टी निर्दिष्ट सूची में नहीं है: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | ‘ppt_x’ प्रॉपर्टी को दर्शाता है |
| [getPptY()](#getPptY--) | ‘ppt_y’ प्रॉपर्टी को दर्शाता है |
| [getPptW()](#getPptW--) | ‘ppt_w’ प्रॉपर्टी को दर्शाता है |
| [getPptH()](#getPptH--) | ‘ppt_h’ प्रॉपर्टी को दर्शाता है |
| [getPptC()](#getPptC--) | ‘ppt_c’ प्रॉपर्टी को दर्शाता है |
| [getPptR()](#getPptR--) | ‘ppt_r’ प्रॉपर्टी को दर्शाता है |
| [getXShear()](#getXShear--) | ‘xshear’ प्रॉपर्टी को दर्शाता है |
| [getYShear()](#getYShear--) | ‘yshear’ प्रॉपर्टी को दर्शाता है |
| [getImage()](#getImage--) | ‘image’ प्रॉपर्टी को दर्शाता है |
| [getScaleX()](#getScaleX--) | ‘ScaleX’ प्रॉपर्टी को दर्शाता है |
| [getScaleY()](#getScaleY--) | ‘ScaleY’ प्रॉपर्टी को दर्शाता है |
| [getR()](#getR--) | ‘r’ प्रॉपर्टी को दर्शाता है |
| [getFillColor()](#getFillColor--) | ‘fillcolor’ प्रॉपर्टी को दर्शाता है |
| [getStyleOpacity()](#getStyleOpacity--) | ‘style.opacity’ प्रॉपर्टी को दर्शाता है |
| [getStyleRotation()](#getStyleRotation--) | ‘style.rotation’ प्रॉपर्टी को दर्शाता है |
| [getStyleVisibility()](#getStyleVisibility--) | ‘style.visibility’ प्रॉपर्टी को दर्शाता है |
| [getStyleColor()](#getStyleColor--) | ‘style.color’ प्रॉपर्टी को दर्शाता है |
| [getStyleFontSize()](#getStyleFontSize--) | ‘style.fontSize’ प्रॉपर्टी को दर्शाता है |
| [getStyleFontWeight()](#getStyleFontWeight--) | ‘style.fontWeight’ प्रॉपर्टी को दर्शाता है |
| [getStyleFontStyle()](#getStyleFontStyle--) | ‘style.fontStyle’ प्रॉपर्टी को दर्शाता है |
| [getStyleFontFamily()](#getStyleFontFamily--) | ‘style.fontFamily’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | ‘style.textEffectEmboss’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextShadow()](#getStyleTextShadow--) | ‘style.textShadow’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextTransform()](#getStyleTextTransform--) | ‘style.textTransform’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | ‘style.textDecorationUnderline’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | ‘style.textEffectOutline’ प्रॉपर्टी को दर्शाता है |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | ‘style.textDecorationLineThrough’ प्रॉपर्टी को दर्शाता है |
| [getStyleSRotation()](#getStyleSRotation--) | ‘style.sRotation’ प्रॉपर्टी को दर्शाता है |
| [getImageDataCropTop()](#getImageDataCropTop--) | ‘imageData.cropTop’ प्रॉपर्टी को दर्शाता है |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | ‘imageData.cropBottom’ प्रॉपर्टी को दर्शाता है |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | ‘imageData.cropLeft’ प्रॉपर्टी को दर्शाता है |
| [getImageDataCropRight()](#getImageDataCropRight--) | ‘imageData.cropRight’ प्रॉपर्टी को दर्शाता है |
| [getImageDataGain()](#getImageDataGain--) | ‘imageData.gain’ प्रॉपर्टी को दर्शाता है |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | ‘imageData.blacklevel’ प्रॉपर्टी को दर्शाता है |
| [getImageDataGamma()](#getImageDataGamma--) | ‘imageData.gamma’ प्रॉपर्टी को दर्शाता है |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | ‘imageData.grayscale’ प्रॉपर्टी को दर्शाता है |
| [getImageDataChromakey()](#getImageDataChromakey--) | ‘imageData.chromakey’ प्रॉपर्टी को दर्शाता है |
| [getFillOn()](#getFillOn--) | ‘fill.on’ प्रॉपर्टी को दर्शाता है |
| [getFillType()](#getFillType--) | ‘fill.type’ प्रॉपर्टी को दर्शाता है |
| [getFill_Color()](#getFill-Color--) | ‘fill.color’ प्रॉपर्टी को दर्शाता है |
| [getFillOpacity()](#getFillOpacity--) | ‘fill.opacity’ प्रॉपर्टी को दर्शाता है |
| [getFillColor2()](#getFillColor2--) | ‘fill.color2’ प्रॉपर्टी को दर्शाता है |
| [getFillMethod()](#getFillMethod--) | ‘fill.method’ प्रॉपर्टी को दर्शाता है |
| [getFillOpacity2()](#getFillOpacity2--) | ‘fill.opacity2’ प्रॉपर्टी को दर्शाता है |
| [getFillAngle()](#getFillAngle--) | ‘fill.angle’ प्रॉपर्टी को दर्शाता है |
| [getFillFocus()](#getFillFocus--) | ‘fill.focus’ प्रॉपर्टी को दर्शाता है |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | ‘fill.focusposition.x’ प्रॉपर्टी को दर्शाता है |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | ‘fill.focusposition.y’ प्रॉपर्टी को दर्शाता है |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | ‘fill.focussize.x’ प्रॉपर्टी को दर्शाता है |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | ‘fill.focussize.y’ प्रॉपर्टी को दर्शाता है |
| [getStrokeOn()](#getStrokeOn--) | ‘stroke.on’ प्रॉपर्टी को दर्शाता है |
| [getStrokeColor()](#getStrokeColor--) | ‘stroke.color’ प्रॉपर्टी को दर्शाता है |
| [getStrokeWeight()](#getStrokeWeight--) | ‘stroke.weight’ प्रॉपर्टी को दर्शाता है |
| [getStrokeOpacity()](#getStrokeOpacity--) | ‘stroke.opacity’ प्रॉपर्टी को दर्शाता है |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | ‘stroke.linestyle’ प्रॉपर्टी को दर्शाता है |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | ‘stroke.dashstyle’ प्रॉपर्टी को दर्शाता है |
| [getStrokeFillType()](#getStrokeFillType--) | ‘stroke.filltype’ प्रॉपर्टी को दर्शाता है |
| [getStrokeSrc()](#getStrokeSrc--) | ‘stroke.src’ प्रॉपर्टी को दर्शाता है |
| [getStrokeColor2()](#getStrokeColor2--) | ‘stroke.color2’ प्रॉपर्टी को दर्शाता है |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | ‘stroke.imagesize.x’ प्रॉपर्टी को दर्शाता है |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | ‘stroke.imagesize.y’ प्रॉपर्टी को दर्शाता है |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | ‘stroke.startArrow’ प्रॉपर्टी को दर्शाता है |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | ‘stroke.endArrow’ प्रॉपर्टी को दर्शाता है |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | ‘stroke.startArrowWidth’ प्रॉपर्टी को दर्शाता है |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | ‘stroke.startArrowLength’ प्रॉपर्टी को दर्शाता है |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | ‘stroke.endArrowWidth’ प्रॉपर्टी को दर्शाता है |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | ‘stroke.endArrowLength’ प्रॉपर्टी को दर्शाता है |
| [getShadowOn()](#getShadowOn--) | ‘shadow.on’ प्रॉपर्टी को दर्शाता है |
| [getShadowType()](#getShadowType--) | ‘shadow.type’ प्रॉपर्टी को दर्शाता है |
| [getShadowColor()](#getShadowColor--) | ‘shadow.color’ प्रॉपर्टी को दर्शाता है |
| [getShadowColor2()](#getShadowColor2--) | ‘shadow.color2’ प्रॉपर्टी को दर्शाता है |
| [getShadowOpacity()](#getShadowOpacity--) | ‘shadow.opacity’ प्रॉपर्टी को दर्शाता है |
| [getShadowOffsetX()](#getShadowOffsetX--) | ‘shadow.offset.x’ प्रॉपर्टी को दर्शाता है |
| [getShadowOffsetY()](#getShadowOffsetY--) | ‘shadow.offset.y’ प्रॉपर्टी को दर्शाता है |
| [getShadowOffset2X()](#getShadowOffset2X--) | ‘shadow.offset2.x’ प्रॉपर्टी को दर्शाता है |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | ‘shadow.offset2.y’ प्रॉपर्टी को दर्शाता है |
| [getShadowOriginX()](#getShadowOriginX--) | ‘shadow.origin.x’ प्रॉपर्टी को दर्शाता है |
| [getShadowOriginY()](#getShadowOriginY--) | ‘shadow.origin.y’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | ‘shadow.matrix.xtox’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | ‘shadow.matrix.xtoy’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | ‘shadow.matrix.ytox’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | ‘shadow.matrix.ytoy’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | ‘shadow.matrix.perspectiveX’ प्रॉपर्टी को दर्शाता है |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | ‘shadow.matrix.perspectiveY’ प्रॉपर्टी को दर्शाता है |
| [getSkewOn()](#getSkewOn--) | ‘skew.on’ प्रॉपर्टी को दर्शाता है |
| [getSkewOffsetX()](#getSkewOffsetX--) | ‘skew.offset.x’ प्रॉपर्टी को दर्शाता है |
| [getSkewOffsetY()](#getSkewOffsetY--) | ‘skew.offset.y’ प्रॉपर्टी को दर्शाता है |
| [getSkewOriginX()](#getSkewOriginX--) | ‘skew.origin.x’ प्रॉपर्टी को दर्शाता है |
| [getSkewOriginY()](#getSkewOriginY--) | ‘skew.origin.y’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | ‘skew.matrix.xtox’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | ‘skew.matrix.xtoy’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | ‘skew.matrix.ytox’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | ‘skew.matrix.ytoy’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | ‘skew.matrix.perspectiveX’ प्रॉपर्टी को दर्शाता है |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | ‘skew.matrix.perspectiveY’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionOn()](#getExtrusionOn--) | ‘extrusion.on’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionType()](#getExtrusionType--) | ‘extrusion.type’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRender()](#getExtrusionRender--) | ‘extrusion.render’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | ‘extrusion.viewpointorigin.x’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | ‘extrusion.viewpointorigin.y’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | ‘extrusion.viewpoint.x’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | ‘extrusion.viewpoint.y’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | ‘extrusion.viewpoint.z’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionPlane()](#getExtrusionPlane--) | ‘extrusion.plane’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | ‘extrusion.skewangle’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | ‘extrusion.skewamt’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | ‘extrusion.backdepth’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | ‘extrusion.foredepth’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | ‘extrusion.orientation.x’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | ‘extrusion.orientation.y’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | ‘extrusion.orientation.z’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | ‘extrusion.orientationangle’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionColor()](#getExtrusionColor--) | ‘extrusion.color’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | ‘extrusion.rotationangle.x’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | ‘extrusion.rotationangle.y’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | ‘extrusion.lockrotationcenter’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | ‘extrusion.autorotationcenter’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | ‘extrusion.rotationcenter.x’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | ‘extrusion.rotationcenter.y’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | ‘extrusion.rotationcenter.z’ प्रॉपर्टी को दर्शाता है |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | ‘extrusion.colormode’ प्रॉपर्टी को दर्शाता है |
| [equals(Object obj)](#equals-java.lang.Object-) | जांचता है कि यह ऑब्जेक्ट दूसरे के बराबर है या नहीं |
| [hashCode()](#hashCode--) | (\#getValue.getValue) प्रॉपर्टी के आधार पर हैश कोड की गणना करता है और लौटाता है |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | मौजूदा व्यवहार प्रॉपर्टी को मान द्वारा खोजता है या निर्दिष्ट मान के साथ नया कस्टम बनाता है |

### getValue() {#getValue--}
```
public final String getValue()
```

प्रॉपर्टी का मान

**रिटर्न वैल्यू:**  
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

दिखाता है कि यह प्रॉपर्टी निर्दिष्ट सूची में नहीं है: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**रिटर्न वैल्यू:**  
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

‘ppt_x’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

‘ppt_y’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

‘ppt_w’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

‘ppt_h’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

‘ppt_c’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

‘ppt_r’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

‘xshear’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

‘yshear’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

‘image’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

‘ScaleX’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

‘ScaleY’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

‘r’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

‘fillcolor’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

‘style.opacity’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

‘style.rotation’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

‘style.visibility’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

‘style.color’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

‘style.fontSize’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

‘style.fontWeight’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

‘style.fontStyle’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

‘style.fontFamily’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

‘style.textEffectEmboss’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

‘style.textShadow’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

‘style.textTransform’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

‘style.textDecorationUnderline’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

‘style.textEffectOutline’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

‘style.textDecorationLineThrough’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

‘style.sRotation’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

‘imageData.cropTop’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

‘imageData.cropBottom’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

‘imageData.cropLeft’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

‘imageData.cropRight’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

‘imageData.gain’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

‘imageData.blacklevel’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

‘imageData.gamma’ प्रॉपर्टी को दर्शाता है

**रिटर्न वैल्यू:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


प्रदर्शित करता है 'imageData.grayscale' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


प्रदर्शित करता है 'imageData.chromakey' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


प्रदर्शित करता है 'fill.on' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


प्रदर्शित करता है 'fill.type' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


प्रदर्शित करता है 'fill.color' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


प्रदर्शित करता है 'fill.opacity' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


प्रदर्शित करता है 'fill.color2' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


प्रदर्शित करता है 'fill.method' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


प्रदर्शित करता है 'fill.opacity2' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


प्रदर्शित करता है 'fill.angle' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


प्रदर्शित करता है 'fill.focus' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


प्रदर्शित करता है 'fill.focusposition.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


प्रदर्शित करता है 'fill.focusposition.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


प्रदर्शित करता है 'fill.focussize.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


प्रदर्शित करता है 'fill.focussize.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


प्रदर्शित करता है 'stroke.on' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


प्रदर्शित करता है 'stroke.color' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


प्रदर्शित करता है 'stroke.weight' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


प्रदर्शित करता है 'stroke.opacity' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


प्रदर्शित करता है 'stroke.linestyle' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


प्रदर्शित करता है 'stroke.dashstyle' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


प्रदर्शित करता है 'stroke.filltype' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


प्रदर्शित करता है 'stroke.src' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


प्रदर्शित करता है 'stroke.color2' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


प्रदर्शित करता है 'stroke.imagesize.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


प्रदर्शित करता है 'stroke.imagesize.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


प्रदर्शित करता है 'stroke.startArrow' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


प्रदर्शित करता है 'stroke.endArrow' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


प्रदर्शित करता है 'stroke.startArrowWidth' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


प्रदर्शित करता है 'stroke.startArrowLength' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


प्रदर्शित करता है 'stroke.endArrowWidth' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


प्रदर्शित करता है 'stroke.endArrowLength' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


प्रदर्शित करता है 'shadow.on' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


प्रदर्शित करता है 'shadow.type' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


प्रदर्शित करता है 'shadow.color' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


प्रदर्शित करता है 'shadow.color2' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


प्रदर्शित करता है 'shadow.opacity' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


प्रदर्शित करता है 'shadow.offset.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


प्रदर्शित करता है 'shadow.offset.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


प्रदर्शित करता है 'shadow.offset2.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


प्रदर्शित करता है 'shadow.offset2.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


प्रदर्शित करता है 'shadow.origin.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


प्रदर्शित करता है 'shadow.origin.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


प्रदर्शित करता है 'shadow.matrix.xtox' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


प्रदर्शित करता है 'shadow.matrix.xtoy' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


प्रदर्शित करता है 'shadow.matrix.ytox' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


प्रदर्शित करता है 'shadow.matrix.ytoy' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


प्रदर्शित करता है 'shadow.matrix.perspectiveX' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


प्रदर्शित करता है 'shadow.matrix.perspectiveY' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


प्रदर्शित करता है 'skew.on' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


प्रदर्शित करता है 'skew.offset.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


प्रदर्शित करता है 'skew.offset.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


प्रदर्शित करता है 'skew.origin.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


प्रदर्शित करता है 'skew.origin.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


प्रदर्शित करता है 'skew.matrix.xtox' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


प्रदर्शित करता है 'skew.matrix.xtoy' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


प्रदर्शित करता है 'skew.matrix.ytox' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


प्रदर्शित करता है 'skew.matrix.ytoy' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


प्रदर्शित करता है 'skew.matrix.perspectiveX' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


प्रदर्शित करता है 'skew.matrix.perspectiveY' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


प्रदर्शित करता है 'extrusion.on' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionOn()
```


प्रदर्शित करता है 'extrusion.type' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


प्रदर्शित करता है 'extrusion.render' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


प्रदर्शित करता है 'extrusion.viewpointorigin.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


प्रदर्शित करता है 'extrusion.viewpointorigin.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


प्रदर्शित करता है 'extrusion.viewpoint.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


प्रदर्शित करता है 'extrusion.viewpoint.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


प्रदर्शित करता है 'extrusion.viewpoint.z' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


प्रदर्शित करता है 'extrusion.plane' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


प्रदर्शित करता है 'extrusion.skewangle' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


प्रदर्शित करता है 'extrusion.skewamt' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


प्रदर्शित करता है 'extrusion.backdepth' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


प्रदर्शित करता है 'extrusion.foredepth' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


प्रदर्शित करता है 'extrusion.orientation.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


प्रदर्शित करता है 'extrusion.orientation.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


प्रदर्शित करता है 'extrusion.orientation.z' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


प्रदर्शित करता है 'extrusion.orientationangle' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


प्रदर्शित करता है 'extrusion.color' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


प्रदर्शित करता है 'extrusion.rotationangle.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


प्रदर्शित करता है 'extrusion.rotationangle.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


प्रदर्शित करता है 'extrusion.lockrotationcenter' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


प्रदर्शित करता है 'extrusion.autorotationcenter' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


प्रदर्शित करता है 'extrusion.rotationcenter.x' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


प्रदर्शित करता है 'extrusion.rotationcenter.y' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


प्रदर्शित करता है 'extrusion.rotationcenter.z' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


प्रदर्शित करता है 'extrusion.colormode' प्रॉपर्टी

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जांचता है कि यह ऑब्जेक्ट किसी अन्य ऑब्जेक्ट के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने वाला ऑब्जेक्ट। |

**रिटर्न:**
boolean - सही यदि ऑब्जेक्ट समान हैं।
### hashCode() {#hashCode--}
```
public int hashCode()
```


(\#getValue.getValue) प्रॉपर्टी के आधार पर हाश कोड की गणना करता है और लौटाता है

**रिटर्न:**
int - इस ऑब्जेक्ट के लिए हाश कोड लौटाता है
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


निर्दिष्ट मान द्वारा मौजूदा व्यवहार प्रॉपर्टी खोजता है या निर्दिष्ट मान के साथ नई कस्टम प्रॉपर्टी बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का मान |

**रिटर्न:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty का उदाहरण