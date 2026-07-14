---
title: BehaviorProperty
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش انواع خصوصیت‌ها برای رفتار انیمیشن.
type: docs
url: /fa/com.aspose.slides/behaviorproperty/
---
**وارثی:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

نمایش می‌دهد انواع ویژگی‌های رفتار انیمیشن. از فهرست ویژگی‌ها موجود در https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx و https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx پیروی می‌کند
## متدها

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | مقدار ویژگی |
| [isCustom()](#isCustom--) | نشان می‌دهد که آیا این ویژگی به فهرست ویژگی‌های پیش‌تعریف‌شده در مشخصات تعلق ندارد: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | نمایش می‌دهد ویژگی 'ppt_x' |
| [getPptY()](#getPptY--) | نمایش می‌دهد ویژگی 'ppt_y' |
| [getPptW()](#getPptW--) | نمایش می‌دهد ویژگی 'ppt_w' |
| [getPptH()](#getPptH--) | نمایش می‌دهد ویژگی 'ppt_h' |
| [getPptC()](#getPptC--) | نمایش می‌دهد ویژگی 'ppt_c' |
| [getPptR()](#getPptR--) | نمایش می‌دهد ویژگی 'ppt_r' |
| [getXShear()](#getXShear--) | نمایش می‌دهد ویژگی 'xshear' |
| [getYShear()](#getYShear--) | نمایش می‌دهد ویژگی 'yshear' |
| [getImage()](#getImage--) | نمایش می‌دهد ویژگی 'image' |
| [getScaleX()](#getScaleX--) | نمایش می‌دهد ویژگی 'ScaleX' |
| [getScaleY()](#getScaleY--) | نمایش می‌دهد ویژگی 'ScaleY' |
| [getR()](#getR--) | نمایش می‌دهد ویژگی 'r' |
| [getFillColor()](#getFillColor--) | نمایش می‌دهد ویژگی 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | نمایش می‌دهد ویژگی 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | نمایش می‌دهد ویژگی 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | نمایش می‌دهد ویژگی 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | نمایش می‌دهد ویژگی 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | نمایش می‌دهد ویژگی 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | نمایش می‌دهد ویژگی 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | نمایش می‌دهد ویژگی 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | نمایش می‌دهد ویژگی 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | نمایش می‌دهد ویژگی 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | نمایش می‌دهد ویژگی 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | نمایش می‌دهد ویژگی 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | نمایش می‌دهد ویژگی 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | نمایش می‌دهد ویژگی 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | نمایش می‌دهد ویژگی 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | نمایش می‌دهد ویژگی 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | نمایش می‌دهد ویژگی 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | نمایش می‌دهد ویژگی 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | نمایش می‌دهد ویژگی 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | نمایش می‌دهد ویژگی 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | نمایش می‌دهد ویژگی 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | نمایش می‌دهد ویژگی 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | نمایش می‌دهد ویژگی 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | نمایش می‌دهد ویژگی 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | نمایش می‌دهد ویژگی 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | نمایش می‌دهد ویژگی 'fill.on' |
| [getFillType()](#getFillType--) | نمایش می‌دهد ویژگی 'fill.type' |
| [getFill_Color()](#getFill-Color--) | نمایش می‌دهد ویژگی 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | نمایش می‌دهد ویژگی 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | نمایش می‌دهد ویژگی 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | نمایش می‌دهد ویژگی 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | نمایش می‌دهد ویژگی 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | نمایش می‌دهد ویژگی 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | نمایش می‌دهد ویژگی 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | نمایش می‌دهد ویژگی 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | نمایش می‌دهد ویژگی 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | نمایش می‌دهد ویژگی 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | نمایش می‌دهد ویژگی 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | نمایش می‌دهد ویژگی 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | نمایش می‌دهد ویژگی 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | نمایش می‌دهد ویژگی 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | نمایش می‌دهد ویژگی 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | نمایش می‌دهد ویژگی 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | نمایش می‌دهد ویژگی 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | نمایش می‌دهد ویژگی 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | نمایش می‌دهد ویژگی 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | نمایش می‌دهد ویژگی 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | نمایش می‌دهد ویژگی 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | نمایش می‌دهد ویژگی 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | نمایش می‌دهد ویژگی 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | نمایش می‌دهد ویژگی 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | نمایش می‌دهد ویژگی 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | نمایش می‌دهد ویژگی 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | نمایش می‌دهد ویژگی 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | نمایش می‌دهد ویژگی 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | نمایش می‌دهد ویژگی 'shadow.on' |
| [getShadowType()](#getShadowType--) | نمایش می‌دهد ویژگی 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | نمایش می‌دهد ویژگی 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | نمایش می‌دهد ویژگی 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | نمایش می‌دهد ویژگی 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | نمایش می‌دهد ویژگی 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | نمایش می‌دهد ویژگی 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | نمایش می‌دهد ویژگی 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | نمایش می‌دهد ویژگی 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | نمایش می‌دهد ویژگی 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | نمایش می‌دهد ویژگی 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | نمایش می‌دهد ویژگی 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | نمایش می‌دهد ویژگی 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | نمایش می‌دهد ویژگی 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | نمایش می‌دهد ویژگی 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | نمایش می‌دهد ویژگی 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | نمایش می‌دهد ویژگی 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | نمایش می‌دهد ویژگی 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | نمایش می‌دهد ویژگی 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | نمایش می‌دهد ویژگی 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | نمایش می‌دهد ویژگی 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | نمایش می‌دهد ویژگی 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | نمایش می‌دهد ویژگی 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | نمایش می‌دهد ویژگی 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | نمایش می‌دهد ویژگی 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | نمایش می‌دهد ویژگی 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | نمایش می‌دهد ویژگی 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | نمایش می‌دهد ویژگی 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | نمایش می‌دهد ویژگی 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | نمایش می‌دهد ویژگی 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | نمایش می‌دهد ویژگی 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | نمایش می‌دهد ویژگی 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | نمایش می‌دهد ویژگی 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | نمایش می‌دهد ویژگی 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | نمایش می‌دهد ویژگی 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | نمایش می‌دهد ویژگی 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | نمایش می‌دهد ویژگی 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | نمایش می‌دهد ویژگی 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | نمایش می‌دهد ویژگی 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | نمایش می‌دهد ویژگی 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | نمایش می‌دهد ویژگی 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | نمایش می‌دهد ویژگی 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | نمایش می‌دهد ویژگی 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | نمایش می‌دهد ویژگی 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | نمایش می‌دهد ویژگی 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | نمایش می‌دهد ویژگی 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | نمایش می‌دهد ویژگی 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | نمایش می‌دهد ویژگی 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | نمایش می‌دهد ویژگی 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | نمایش می‌دهد ویژگی 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | نمایش می‌دهد ویژگی 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | نمایش می‌دهد ویژگی 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | نمایش می‌دهد ویژگی 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | نمایش می‌دهد ویژگی 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | بررسی می‌کند که آیا این شی برابر با شی دیگری است. |
| [hashCode()](#hashCode--) | محاسبه و بازگرداندن کد هش بر پایه ویژگی (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | جستجو برای ویژگی رفتار موجود بر اساس مقدار یا ایجاد یک مورد سفارشی جدید با مقدار مشخص شده |

### getValue() {#getValue--}
```
public final String getValue()
```

مقدار ویژگی

**باز می‌گردد:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

نشان می‌دهد که آیا این ویژگی به فهرست ویژگی‌های پیش‌تعریف‌شده در مشخصات تعلق ندارد: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**باز می‌گردد:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

نمایش می‌دهد ویژگی 'ppt_x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

نمایش می‌دهد ویژگی 'ppt_y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

نمایش می‌دهد ویژگی 'ppt_w'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

نمایش می‌دهد ویژگی 'ppt_h'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

نمایش می‌دهد ویژگی 'ppt_c'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

نمایش می‌دهد ویژگی 'ppt_r'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

نمایش می‌دهد ویژگی 'xshear'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

نمایش می‌دهد ویژگی 'yshear'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

نمایش می‌دهد ویژگی 'image'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

نمایش می‌دهد ویژگی 'ScaleX'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

نمایش می‌دهد ویژگی 'ScaleY'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

نمایش می‌دهد ویژگی 'r'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

نمایش می‌دهد ویژگی 'fillcolor'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

نمایش می‌دهد ویژگی 'style.opacity'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

نمایش می‌دهد ویژگی 'style.rotation'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

نمایش می‌دهد ویژگی 'style.visibility'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

نمایش می‌دهد ویژگی 'style.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

نمایش می‌دهد ویژگی 'style.fontSize'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

نمایش می‌دهد ویژگی 'style.fontWeight'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

نمایش می‌دهد ویژگی 'style.fontStyle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

نمایش می‌دهد ویژگی 'style.fontFamily'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

نمایش می‌دهد ویژگی 'style.textEffectEmboss'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

نمایش می‌دهد ویژگی 'style.textShadow'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

نمایش می‌دهد ویژگی 'style.textTransform'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

نمایش می‌دهد ویژگی 'style.textDecorationUnderline'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

نمایش می‌دهد ویژگی 'style.textEffectOutline'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

نمایش می‌دهد ویژگی 'style.textDecorationLineThrough'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

نمایش می‌دهد ویژگی 'style.sRotation'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

نمایش می‌دهد ویژگی 'imageData.cropTop'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

نمایش می‌دهد ویژگی 'imageData.cropBottom'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

نمایش می‌دهد ویژگی 'imageData.cropLeft'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

نمایش می‌دهد ویژگی 'imageData.cropRight'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

نمایش می‌دهد ویژگی 'imageData.gain'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

نمایش می‌دهد ویژگی 'imageData.blacklevel'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

نمایش می‌دهد ویژگی 'imageData.gamma'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

نمایش می‌دهد ویژگی 'imageData.grayscale'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

نمایش می‌دهد ویژگی 'imageData.chromakey'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

نمایش می‌دهد ویژگی 'fill.on'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

نمایش می‌دهد ویژگی 'fill.type'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

نمایش می‌دهد ویژگی 'fill.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

نمایش می‌دهد ویژگی 'fill.opacity'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

نمایش می‌دهد ویژگی 'fill.color2'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

نمایش می‌دهد ویژگی 'fill.method'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

نمایش می‌دهد ویژهٔ 'fill.opacity2'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

نمایش می‌دهد ویژگی 'fill.angle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

نمایش می‌دهد ویژگی 'fill.focus'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

نمایش می‌دهد ویژگی 'fill.focusposition.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

نمایش می‌دهد ویژگی 'fill.focusposition.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

نمایش می‌دهد ویژگی 'fill.focussize.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

نمایش می‌دهد ویژگی 'fill.focussize.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

نمایش می‌دهد ویژگی 'stroke.on'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

نمایش می‌دهد ویژگی 'stroke.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

نمایش می‌دهد ویژگی 'stroke.weight'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

نمایش می‌دهد ویژگی 'stroke.opacity'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

نمایش می‌دهد ویژگی 'stroke.linestyle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

نمایش می‌دهد ویژگی 'stroke.dashstyle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

نمایش می‌دهد ویژگی 'stroke.filltype'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

نمایش می‌دهد ویژگی 'stroke.src'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

نمایش می‌دهد ویژگی 'stroke.color2'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

نمایش می‌دهد ویژگی 'stroke.imagesize.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

نمایش می‌دهد ویژگی 'stroke.imagesize.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

نمایش می‌دهد ویژگی 'stroke.startArrow'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

نمایش می‌دهد ویژگی 'stroke.endArrow'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

نمایش می‌دهد ویژگی 'stroke.startArrowWidth'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

نمایش می‌دهد ویژگی 'stroke.startArrowLength'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

نمایش می‌دهد ویژگی 'stroke.endArrowWidth'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

نمایش می‌دهد ویژگی 'stroke.endArrowLength'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

نمایش می‌دهد ویژگی 'shadow.on'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

نمایش می‌دهد ویژگی 'shadow.type'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

نمایش می‌دهد ویژگی 'shadow.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

نمایش می‌دهد ویژگی 'shadow.color2'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

نمایش می‌دهد ویژگی 'shadow.opacity'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

نمایش می‌دهد ویژگی 'shadow.offset.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

نمایش می‌دهد ویژگی 'shadow.offset.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

نمایش می‌دهد ویژگی 'shadow.offset2.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

نمایش می‌دهد ویژگی 'shadow.offset2.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

نمایش می‌دهد ویژگی 'shadow.origin.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

نمایش می‌دهد ویژگی 'shadow.origin.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

نمایش می‌دهد ویژگی 'shadow.matrix.xtox'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

نمایش می‌دهد ویژگی 'shadow.matrix.xtoy'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

نمایش می‌دهد ویژگی 'shadow.matrix.ytox'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

نمایش می‌دهد ویژهٔ 'shadow.matrix.ytoy'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

نمایش می‌دهد ویژهٔ 'shadow.matrix.perspectiveX'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

نمایش می‌دهد ویژهٔ 'shadow.matrix.perspectiveY'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

نمایش می‌دهد ویژگی 'skew.on'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

نمایش می‌دهد ویژگی 'skew.offset.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

نمایش می‌دهد ویژگی 'skew.offset.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

نمایش می‌دهد ویژگی 'skew.origin.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

نمایش می‌دهد ویژگی 'skew.origin.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

نمایش می‌دهد ویژگی 'skew.matrix.xtox'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

نمایش می‌دهد ویژگی 'skew.matrix.xtoy'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

نمایش می‌دهد ویژگی 'skew.matrix.ytox'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

نمایش می‌دهد ویژگی 'skew.matrix.ytoy'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

نمایش می‌دهد ویژگی 'skew.matrix.perspectiveX'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

نمایش می‌دهد ویژگی 'skew.matrix.perspectiveY'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

نمایش می‌دهد ویژگی 'extrusion.on'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

نمایش می‌دهد ویژگی 'extrusion.type'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

نمایش می‌دهد ویژگی 'extrusion.render'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

نمایش می‌دهد ویژگی 'extrusion.viewpointorigin.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

نمایش می‌دهد ویژگی 'extrusion.viewpointorigin.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

نمایش می‌دهد ویژگی 'extrusion.viewpoint.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

نمایش می‌دهد ویژگی 'extrusion.viewpoint.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

نمایش می‌دهد ویژگی 'extrusion.viewpoint.z'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

نمایش می‌دهد ویژگی 'extrusion.plane'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

نمایش می‌دهد ویژگی 'extrusion.skewangle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

نمایش می‌دهد ویژهٔ 'extrusion.skewamt'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

نمایش می‌دهد ویژهٔ 'extrusion.backdepth'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

نمایش می‌دهد ویژهٔ 'extrusion.foredepth'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

نمایش می‌دهد ویژگی 'extrusion.orientation.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

نمایش می‌دهد ویژگی 'extrusion.orientation.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

نمایش می‌دهد ویژگی 'extrusion.orientation.z'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

نمایش می‌دهد ویژگی 'extrusion.orientationangle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

نمایش می‌دهد ویژگی 'extrusion.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

نمایش می‌دهد ویژگی 'extrusion.rotationangle.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

نمایش می‌دهد ویژگی 'extrusion.rotationangle.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

نمایش می‌دهد ویژهٔ 'extrusion.lockrotationcenter'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

نمایش می‌دهد ویژهٔ 'extrusion.autorotationcenter'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

نمایش می‌دهد ویژگی 'extrusion.rotationcenter.x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

نمایش می‌دهد ویژگی 'extrusion.rotationcenter.y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

نمایش می‌دهد ویژگی 'extrusion.rotationcenter.z'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

نمایش می‌دهد ویژگی 'extrusion.colormode'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

بررسی می‌کند که آیا این شی برابر با شی دیگری است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | شی برای مقایسه. |

**باز می‌گردد:**
boolean - True if objects are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

محاسبه و بازگرداندن کد هش بر پایه ویژگی (\#getValue.getValue)

**باز می‌گردد:**
int - Returns hash code for this object

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

جستجو برای ویژگی رفتار موجود بر اساس مقدار یا ایجاد یک مورد سفارشی جدید با مقدار مشخص شده

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی |

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance of BehaviorProperty