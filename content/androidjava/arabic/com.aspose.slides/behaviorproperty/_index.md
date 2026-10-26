---
title: BehaviorProperty
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: تمثيل أنواع الخصائص لسلوك الرسوم المتحركة.
type: docs
url: /ar/com.aspose.slides/behaviorproperty/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)  
```
public class BehaviorProperty implements IBehaviorProperty
```

يمثل أنواع خصائص سلوك الرسوم المتحركة. يتبع قائمة الخصائص من https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx و https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | قيمة الخاصية |
| [isCustom()](#isCustom--) | يوضح ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المحددة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | يمثل الخاصية 'ppt\_x' |
| [getPptY()](#getPptY--) | يمثل الخاصية 'ppt\_y' |
| [getPptW()](#getPptW--) | يمثل الخاصية 'ppt\_w' |
| [getPptH()](#getPptH--) | يمثل الخاصية 'ppt\_h' |
| [getPptC()](#getPptC--) | يمثل الخاصية 'ppt\_c' |
| [getPptR()](#getPptR--) | يمثل الخاصية 'ppt\_r' |
| [getXShear()](#getXShear--) | يمثل الخاصية 'xshear' |
| [getYShear()](#getYShear--) | يمثل الخاصية 'yshear' |
| [getImage()](#getImage--) | يمثل الخاصية 'image' |
| [getScaleX()](#getScaleX--) | يمثل الخاصية 'ScaleX' |
| [getScaleY()](#getScaleY--) | يمثل الخاصية 'ScaleY' |
| [getR()](#getR--) | يمثل الخاصية 'r' |
| [getFillColor()](#getFillColor--) | يمثل الخاصية 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | يمثل الخاصية 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | يمثل الخاصية 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | يمثل الخاصية 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | يمثل الخاصية 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | يمثل الخاصية 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | يمثل الخاصية 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | يمثل الخاصية 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | يمثل الخاصية 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | يمثل الخاصية 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | يمثل الخاصية 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | يمثل الخاصية 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | يمثل الخاصية 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | يمثل الخاصية 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | يمثل الخاصية 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | يمثل الخاصية 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | يمثل الخاصية 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | يمثل الخاصية 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | يمثل الخاصية 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | يمثل الخاصية 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | يمثل الخاصية 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | يمثل الخاصية 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | يمثل الخاصية 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | يمثل الخاصية 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | يمثل الخاصية 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | يمثل الخاصية 'fill.on' |
| [getFillType()](#getFillType--) | يمثل الخاصية 'fill.type' |
| [getFill_Color()](#getFill-Color--) | يمثل الخاصية 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | يمثل الخاصية 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | يمثل الخاصية 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | يمثل الخاصية 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | يمثل الخاصية 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | يمثل الخاصية 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | يمثل الخاصية 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | يمثل الخاصية 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | يمثل الخاصية 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | يمثل الخاصية 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | يمثل الخاصية 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | يمثل الخاصية 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | يمثل الخاصية 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | يمثل الخاصية 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | يمثل الخاصية 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | يمثل الخاصية 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | يمثل الخاصية 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | يمثل الخاصية 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | يمثل الخاصية 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | يمثل الخاصية 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | يمثل الخاصية 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | يمثل الخاصية 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | يمثل الخاصية 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | يمثل الخاصية 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | يمثل الخاصية 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | يمثل الخاصية 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | يمثل الخاصية 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | يمثل الخاصية 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | يمثل الخاصية 'shadow.on' |
| [getShadowType()](#getShadowType--) | يمثل الخاصية 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | يمثل الخاصية 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | يمثل الخاصية 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | يمثل الخاصية 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | يمثل الخاصية 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | يمثل الخاصية 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | يمثل الخاصية 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | يمثل الخاصية 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | يمثل الخاصية 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | يمثل الخاصية 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | يمثل الخاصية 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | يمثل الخاصية 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | يمثل الخاصية 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | يمثل الخاصية 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | يمثل الخاصية 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | يمثل الخاصية 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | يمثل الخاصية 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | يمثل الخاصية 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | يمثل الخاصية 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | يمثل الخاصية 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | يمثل الخاصية 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | يمثل الخاصية 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | يمثل الخاصية 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | يمثل الخاصية 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | يمثل الخاصية 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | يمثل الخاصية 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | يمثل الخاصية 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | يمثل الخاصية 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | يمثل الخاصية 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | يمثل الخاصية 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | يمثل الخاصية 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | يمثل الخاصية 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | يمثل الخاصية 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | يمثل الخاصية 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | يمثل الخاصية 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | يمثل الخاصية 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | يمثل الخاصية 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | يمثل الخاصية 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | يمثل الخاصية 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | يمثل الخاصية 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | يمثل الخاصية 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | يمثل الخاصية 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | يمثل الخاصية 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | يمثل الخاصية 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | يمثل الخاصية 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | يمثل الخاصية 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | يمثل الخاصية 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | يمثل الخاصية 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | يمثل الخاصية 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | يمثل الخاصية 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | يمثل الخاصية 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | يمثل الخاصية 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | يمثل الخاصية 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | يتحقق ما إذا كان هذا الكائن مساوٍ لكائن آخر. |
| [hashCode()](#hashCode--) | يحسب ويعيد قيمة التجزئة بناءً على الخاصية (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | يبحث عن خاصية سلوك موجودة بالقيمة أو ينشئ خاصية مخصصة جديدة بالقيمة المحددة |

### getValue() {#getValue--}
```
public final String getValue()
```

قيمة الخاصية

**الإرجاع:**  
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

يُظهر ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المحددة مسبقًا في المواصفة: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**الإرجاع:**  
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

يمثل الخاصية 'ppt\_x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

يمثل الخاصية 'ppt\_y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

يمثل الخاصية 'ppt\_w'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

يمثل الخاصية 'ppt\_h'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

يمثل الخاصية 'ppt\_c'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

يمثل الخاصية 'ppt\_r'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

يمثل الخاصية 'xshear'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

يمثل الخاصية 'yshear'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

يمثل الخاصية 'image'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

يمثل الخاصية 'ScaleX'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

يمثل الخاصية 'ScaleY'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

يمثل الخاصية 'r'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

يمثل الخاصية 'fillcolor'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

يمثل الخاصية 'style.opacity'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

يمثل الخاصية 'style.rotation'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

يمثل الخاصية 'style.visibility'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

يمثل الخاصية 'style.color'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

يمثل الخاصية 'style.fontSize'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

يمثل الخاصية 'style.fontWeight'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

يمثل الخاصية 'style.fontStyle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

يمثل الخاصية 'style.fontFamily'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

يمثل الخاصية 'style.textEffectEmboss'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

يمثل الخاصية 'style.textShadow'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

يمثل الخاصية 'style.textTransform'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

يمثل الخاصية 'style.textDecorationUnderline'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

يمثل الخاصية 'style.textEffectOutline'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

يمثل الخاصية 'style.textDecorationLineThrough'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

يمثل الخاصية 'style.sRotation'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

يمثل الخاصية 'imageData.cropTop'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

يمثل الخاصية 'imageData.cropBottom'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

يمثل الخاصية 'imageData.cropLeft'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

يمثل الخاصية 'imageData.cropRight'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

يمثل الخاصية 'imageData.gain'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

يمثل الخاصية 'imageData.blacklevel'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

يمثل الخاصية 'imageData.gamma'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

يمثل الخاصية 'imageData.grayscale'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

يمثل الخاصية 'imageData.chromakey'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

يمثل الخاصية 'fill.on'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

يمثل الخاصية 'fill.type'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

يمثل الخاصية 'fill.color'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

يمثل الخاصية 'fill.opacity'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

يمثل الخاصية 'fill.color2'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public
```

يمثل الخاصية 'fill.method'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

يمثل الخاصية 'fill.opacity2'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

يمثل الخاصية 'fill.angle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

يمثل الخاصية 'fill.focus'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

يمثل الخاصية 'fill.focusposition.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

يمثل الخاصية 'fill.focusposition.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

يمثل الخاصية 'fill.focussize.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

يمثل الخاصية 'fill.focussize.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

يمثل الخاصية 'stroke.on'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

يمثل الخاصية 'stroke.color'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

يمثل الخاصية 'stroke.weight'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

يمثل الخاصية 'stroke.opacity'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

يمثل الخاصية 'stroke.linestyle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

يمثل الخاصية 'stroke.dashstyle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

يمثل الخاصية 'stroke.filltype'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

يمثل الخاصية 'stroke.src'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

يمثل الخاصية 'stroke.color2'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

يمثل الخاصية 'stroke.imagesize.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

يمثل الخاصية 'stroke.imagesize.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

يمثل الخاصية 'stroke.startArrow'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

يمثل الخاصية 'stroke.endArrow'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

يمثل الخاصية 'stroke.startArrowWidth'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

يمثل الخاصية 'stroke.startArrowLength'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

يمثل الخاصية 'stroke.endArrowWidth'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

يمثل الخاصية 'stroke.endArrowLength'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

يمثل الخاصية 'shadow.on'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

يمثل الخاصية 'shadow.type'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

يمثل الخاصية 'shadow.color'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

يمثل الخاصية 'shadow.color2'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

يمثل الخاصية 'shadow.opacity'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

يمثل الخاصية 'shadow.offset.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

يمثل الخاصية 'shadow.offset.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

يمثل الخاصية 'shadow.offset2.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

يمثل الخاصية 'shadow.offset2.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

يمثل الخاصية 'shadow.origin.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

يمثل الخاصية 'shadow.origin.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

يمثل الخاصية 'shadow.matrix.xtox'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

يمثل الخاصية 'shadow.matrix.xtoy'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

يمثل الخاصية 'shadow.matrix.ytox'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

يمثل الخاصية 'shadow.matrix.ytoy'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

يمثل الخاصية 'shadow.matrix.perspectiveX'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

يمثل الخاصية 'shadow.matrix.perspectiveY'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

يمثل الخاصية 'skew.on'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

يمثل الخاصية 'skew.offset.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

يمثل الخاصية 'skew.offset.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

يمثل الخاصية 'skew.origin.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

يمثل الخاصية 'skew.origin.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

يمثل الخاصية 'skew.matrix.xtox'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

يمثل الخاصية 'skew.matrix.xtoy'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

يمثل الخاصية 'skew.matrix.ytox'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

يمثل الخاصية 'skew.matrix.ytoy'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

يمثل الخاصية 'skew.matrix.perspectiveX'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

يمثل الخاصية 'skew.matrix.perspectiveY'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

يمثل الخاصية 'extrusion.on'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

يمثل الخاصية 'extrusion.type'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

يمثل الخاصية 'extrusion.render'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

يمثل الخاصية 'extrusion.viewpointorigin.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

يمثل الخاصية 'extrusion.viewpointorigin.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

يمثل الخاصية 'extrusion.viewpoint.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

يمثل الخاصية 'extrusion.viewpoint.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

يمثل الخاصية 'extrusion.viewpoint.z'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

يمثل الخاصية 'extrusion.plane'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

يمثل الخاصية 'extrusion.skewangle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

يمثل الخاصية 'extrusion.skewamt'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

يمثل الخاصية 'extrusion.backdepth'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

يمثل الخاصية 'extrusion.foredepth'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

يمثل الخاصية 'extrusion.orientation.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

يمثل الخاصية 'extrusion.orientation.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

يمثل الخاصية 'extrusion.orientation.z'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

يمثل الخاصية 'extrusion.orientationangle'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

يمثل الخاصية 'extrusion.color'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

يمثل الخاصية 'extrusion.rotationangle.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

يمثل الخاصية 'extrusion.rotationangle.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

يمثل الخاصية 'extrusion.lockrotationcenter'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

يمثل الخاصية 'extrusion.autorotationcenter'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

يمثل الخاصية 'extrusion.rotationcenter.x'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

يمثل الخاصية 'extrusion.rotationcenter.y'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

يمثل الخاصية 'extrusion.rotationcenter.z'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

يمثل الخاصية 'extrusion.colormode'

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يتحقق ما إذا كان هذا الكائن مساوٍ لكائن آخر.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**الإرجاع:**  
boolean - true إذا كان الكائنان متساويين.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يحسب ويعيد قيمة التجزئة بناءً على الخاصية (\#getValue.getValue)

**الإرجاع:**  
int - قيمة التجزئة لهذا الكائن

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

يبحث عن خاصية سلوك موجودة بالقيمة أو ينشئ خاصية مخصصة جديدة بالقيمة المحددة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية |

**الإرجاع:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - نسخة من BehaviorProperty