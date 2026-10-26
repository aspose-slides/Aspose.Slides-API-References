---
title: BehaviorProperty
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एनिमेशन व्यवहार के लिए प्रॉपर्टी प्रकारों का प्रतिनिधित्व करता है।
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

एनिमेशन व्यवहार के लिए प्रॉपर्टी प्रकार का प्रतिनिधित्व करता है। यह सूची https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx और https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx से ली गई है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getValue()](#getValue--) | प्रॉपर्टी का मान |
| [isCustom()](#isCustom--) | यह दिखाता है कि यह प्रॉपर्टी स्पेसिफिकेशन में निर्धारित प्रॉपर्टी सूची में नहीं है: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | 'ppt\_x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getPptY()](#getPptY--) | 'ppt\_y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getPptW()](#getPptW--) | 'ppt\_w' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getPptH()](#getPptH--) | 'ppt\_h' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getPptC()](#getPptC--) | 'ppt\_c' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getPptR()](#getPptR--) | 'ppt\_r' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getXShear()](#getXShear--) | 'xshear' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getYShear()](#getYShear--) | 'yshear' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImage()](#getImage--) | 'image' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getScaleX()](#getScaleX--) | 'ScaleX' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getScaleY()](#getScaleY--) | 'ScaleY' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getR()](#getR--) | 'r' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillColor()](#getFillColor--) | 'fillcolor' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleOpacity()](#getStyleOpacity--) | 'style.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleRotation()](#getStyleRotation--) | 'style.rotation' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleVisibility()](#getStyleVisibility--) | 'style.visibility' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleColor()](#getStyleColor--) | 'style.color' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleFontSize()](#getStyleFontSize--) | 'style.fontSize' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleFontWeight()](#getStyleFontWeight--) | 'style.fontWeight' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleFontStyle()](#getStyleFontStyle--) | 'style.fontStyle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleFontFamily()](#getStyleFontFamily--) | 'style.fontFamily' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | 'style.textEffectEmboss' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextShadow()](#getStyleTextShadow--) | 'style.textShadow' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextTransform()](#getStyleTextTransform--) | 'style.textTransform' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | 'style.textDecorationUnderline' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | 'style.textEffectOutline' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | 'style.textDecorationLineThrough' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStyleSRotation()](#getStyleSRotation--) | 'style.sRotation' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataCropTop()](#getImageDataCropTop--) | 'imageData.cropTop' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | 'imageData.cropBottom' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | 'imageData.cropLeft' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataCropRight()](#getImageDataCropRight--) | 'imageData.cropRight' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataGain()](#getImageDataGain--) | 'imageData.gain' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | 'imageData.blacklevel' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataGamma()](#getImageDataGamma--) | 'imageData.gamma' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | 'imageData.grayscale' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getImageDataChromakey()](#getImageDataChromakey--) | 'imageData.chromakey' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillOn()](#getFillOn--) | 'fill.on' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillType()](#getFillType--) | 'fill.type' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFill_Color()](#getFill-Color--) | 'fill.color' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillOpacity()](#getFillOpacity--) | 'fill.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillColor2()](#getFillColor2--) | 'fill.color2' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillMethod()](#getFillMethod--) | 'fill.method' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillOpacity2()](#getFillOpacity2--) | 'fill.opacity2' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillAngle()](#getFillAngle--) | 'fill.angle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillFocus()](#getFillFocus--) | 'fill.focus' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | 'fill.focusposition.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | 'fill.focusposition.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | 'fill.focussize.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | 'fill.focussize.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeOn()](#getStrokeOn--) | 'stroke.on' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeColor()](#getStrokeColor--) | 'stroke.color' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeWeight()](#getStrokeWeight--) | 'stroke.weight' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeOpacity()](#getStrokeOpacity--) | 'stroke.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | 'stroke.linestyle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | 'stroke.dashstyle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeFillType()](#getStrokeFillType--) | 'stroke.filltype' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeSrc()](#getStrokeSrc--) | 'stroke.src' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeColor2()](#getStrokeColor2--) | 'stroke.color2' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | 'stroke.imagesize.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | 'stroke.imagesize.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | 'stroke.startArrow' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | 'stroke.endArrow' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | 'stroke.startArrowWidth' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | 'stroke.startArrowLength' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | 'stroke.endArrowWidth' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | 'stroke.endArrowLength' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOn()](#getShadowOn--) | 'shadow.on' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowType()](#getShadowType--) | 'shadow.type' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowColor()](#getShadowColor--) | 'shadow.color' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowColor2()](#getShadowColor2--) | 'shadow.color2' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOpacity()](#getShadowOpacity--) | 'shadow.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOffsetX()](#getShadowOffsetX--) | 'shadow.offset.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOffsetY()](#getShadowOffsetY--) | 'shadow.offset.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOffset2X()](#getShadowOffset2X--) | 'shadow.offset2.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | 'shadow.offset2.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOriginX()](#getShadowOriginX--) | 'shadow.origin.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowOriginY()](#getShadowOriginY--) | 'shadow.origin.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | 'shadow.matrix.xtox' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | 'shadow.matrix.xtoy' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | 'shadow.matrix.ytox' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | 'shadow.matrix.ytoy' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | 'shadow.matrix.perspectiveX' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | 'shadow.matrix.perspectiveY' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewOn()](#getSkewOn--) | 'skew.on' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewOffsetX()](#getSkewOffsetX--) | 'skew.offset.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewOffsetY()](#getSkewOffsetY--) | 'skew.offset.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewOriginX()](#getSkewOriginX--) | 'skew.origin.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewOriginY()](#getSkewOriginY--) | 'skew.origin.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | 'skew.matrix.xtox' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | 'skew.matrix.xtoy' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | 'skew.matrix.ytox' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | 'skew.matrix.ytoy' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | 'skew.matrix.perspectiveX' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | 'skew.matrix.perspectiveY' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionOn()](#getExtrusionOn--) | 'extrusion.on' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionType()](#getExtrusionType--) | 'extrusion.type' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRender()](#getExtrusionRender--) | 'extrusion.render' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | 'extrusion.viewpointorigin.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | 'extrusion.viewpointorigin.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | 'extrusion.viewpoint.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | 'extrusion.viewpoint.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | 'extrusion.viewpoint.z' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionPlane()](#getExtrusionPlane--) | 'extrusion.plane' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | 'extrusion.skewangle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | 'extrusion.skewamt' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | 'extrusion.backdepth' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | 'extrusion.foredepth' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | 'extrusion.orientation.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | 'extrusion.orientation.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | 'extrusion.orientation.z' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | 'extrusion.orientationangle' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionColor()](#getExtrusionColor--) | 'extrusion.color' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | 'extrusion.rotationangle.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | 'extrusion.rotationangle.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | 'extrusion.lockrotationcenter' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | 'extrusion.autorotationcenter' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | 'extrusion.rotationcenter.x' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | 'extrusion.rotationcenter.y' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | 'extrusion.rotationcenter.z' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | 'extrusion.colormode' प्रॉपर्टी का प्रतिनिधित्व करता है |
| [equals(Object obj)](#equals-java.lang.Object-) | इस ऑब्जेक्ट की समानता को जाँचता है |
| [hashCode()](#hashCode--) | (\#getValue.getValue) प्रॉपर्टी के आधार पर हैश कोड की गणना और वापसी करता है |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | वैल्यू द्वारा मौजूदा व्यवहार प्रॉपर्टी को खोजता है या निर्दिष्ट वैल्यू के साथ नया कस्टम बनाता है |

### getValue() {#getValue--}
```
public final String getValue()
```

प्रॉपर्टी का मान

**वापसी:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

यह दिखाता है कि यह प्रॉपर्टी स्पेसिफिकेशन में निर्धारित प्रॉपर्टी सूची में नहीं है: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**वापसी:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

'ppt\_x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

'ppt\_y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

'ppt\_w' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

'ppt\_h' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

'ppt\_c' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

'ppt\_r' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

'xshear' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

'yshear' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

'image' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

'ScaleX' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

'ScaleY' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

'r' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

'fillcolor' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

'style.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

'style.rotation' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

'style.visibility' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

'style.color' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

'style.fontSize' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

'style.fontWeight' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

'style.fontStyle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

'style.fontFamily' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

'style.textEffectEmboss' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

'style.textShadow' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

'style.textTransform' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

'style.textDecorationUnderline' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

'style.textEffectOutline' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

'style.textDecorationLineThrough' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

'style.sRotation' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

'imageData.cropTop' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

'imageData.cropBottom' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

'imageData.cropLeft' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

'imageData.cropRight' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

'imageData.gain' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

'imageData.blacklevel' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

'imageData.gamma' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

'imageData.grayscale' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

'imageData.chromakey' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

'fill.on' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public  static BehaviorProperty getFillType()
```

'fill.type' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

'fill.color' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

'fill.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

'fill.color2' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

'fill.method' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

'fill.opacity2' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

'fill.angle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

'fill.focus' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

'fill.focusposition.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

'fill.focusposition.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

'fill.focussize.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

'fill.focussize.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

'stroke.on' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

'stroke.color' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

'stroke.weight' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

'stroke.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

'stroke.linestyle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

'stroke.dashstyle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

'stroke.filltype' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

'stroke.src' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

'stroke.color2' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

'stroke.imagesize.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

'stroke.imagesize.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

'stroke.startArrow' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

'stroke.endArrow' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

'stroke.startArrowWidth' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

'stroke.startArrowLength' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

'stroke.endArrowWidth' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

'stroke.endArrowLength' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

'shadow.on' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

'shadow.type' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

'shadow.color' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

'shadow.color2' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

'shadow.opacity' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

'shadow.offset.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

'shadow.offset.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

'shadow.offset2.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

'shadow.offset2.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

'shadow.origin.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

'shadow.origin.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

'shadow.matrix.xtox' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

'shadow.matrix.xtoy' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

'shadow.matrix.ytox' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

'shadow.matrix.ytoy' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

'shadow.matrix.perspectiveX' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

'shadow.matrix.perspectiveY' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

'skew.on' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

'skew.offset.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

'skew.offset.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

'skew.origin.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

'skew.origin.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

'skew.matrix.xtox' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

'skew.matrix.xtoy' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

'skew.matrix.ytox' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

'skew.matrix.ytoy' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

'skew.matrix.perspectiveX' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

'skew.matrix.perspectiveY' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

'extrusion.on' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

'extrusion.type' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

'extrusion.render' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

'extrusion.viewpointorigin.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

'extrusion.viewpointorigin.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

'extrusion.viewpoint.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

'extrusion.viewpoint.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

'extrusion.viewpoint.z' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

'extrusion.plane' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

'extrusion.skewangle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

'extrusion.skewamt' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

'extrusion.backdepth' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

'extrusion.foredepth' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

'extrusion.orientation.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

'extrusion.orientation.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

'extrusion.orientation.z' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

'extrusion.orientationangle' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

'extrusion.color' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

'extrusion.rotationangle.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

'extrusion.rotationangle.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

'extrusion.lockrotationcenter' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

'extrusion.autorotationcenter' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

'extrusion.rotationcenter.x' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

'extrusion.rotationcenter.y' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

'extrusion.rotationcenter.z' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

'extrusion.colormode' प्रॉपर्टी का प्रतिनिधित्व करता है

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

जाँचता है कि यह ऑब्जेक्ट दूसरे के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने वाला ऑब्जेक्ट |

**वापसी:**
boolean - यदि ऑब्जेक्ट समान हों तो true.

### hashCode() {#hashCode--}
```
public int hashCode()
```

(\#getValue.getValue) प्रॉपर्टी के आधार पर हैश कोड की गणना और वापसी करता है

**वापसी:**
int - इस ऑब्जेक्ट के लिए हैश कोड लौटाता है

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

वैध वैल्यू द्वारा मौजूदा व्यवहार प्रॉपर्टी को खोजता है या निर्दिष्ट वैल्यू के साथ नया कस्टम बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| propertyValue | java.lang.String | प्रॉपर्टी का वैल्यू |

**वापसी:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty का इंस्टेंस