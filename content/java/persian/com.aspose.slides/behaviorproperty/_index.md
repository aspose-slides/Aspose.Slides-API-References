---
title: BehaviorProperty
second_title: مرجع API Aspose.Slides برای جاوا
description: انواع ویژگی‌ها را برای رفتار انیمیشن نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/behaviorproperty/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

نمایش‌دهندهٔ انواع ویژگی‌ها برای رفتار انیمیشن. مطابق با فهرست ویژگی‌ها در https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx و https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## متدها

| متد | توضیح |
| --- | --- |
| [getValue()](#getValue--) | مقدار این ویژگی |
| [isCustom()](#isCustom--) | نشان می‌دهد که این ویژگی در فهرست ویژگی‌های پیش‌تعریف‌شدهٔ مشخصات موجود نیست: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | نمایانگر ویژگی 'ppt_x' |
| [getPptY()](#getPptY--) | نمایانگر ویژگی 'ppt_y' |
| [getPptW()](#getPptW--) | نمایانگر ویژگی 'ppt_w' |
| [getPptH()](#getPptH--) | نمایانگر ویژگی 'ppt_h' |
| [getPptC()](#getPptC--) | نمایانگر ویژگی 'ppt_c' |
| [getPptR()](#getPptR--) | نمایانگر ویژگی 'ppt_r' |
| [getXShear()](#getXShear--) | نمایانگر ویژگی 'xshear' |
| [getYShear()](#getYShear--) | نمایانگر ویژگی 'yshear' |
| [getImage()](#getImage--) | نمایانگر ویژگی 'image' |
| [getScaleX()](#getScaleX--) | نمایانگر ویژگی 'ScaleX' |
| [getScaleY()](#getScaleY--) | نمایانگر ویژگی 'ScaleY' |
| [getR()](#getR--) | نمایانگر ویژگی 'r' |
| [getFillColor()](#getFillColor--) | نمایانگر ویژگی 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | نمایانگر ویژگی 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | نمایانگر ویژگی 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | نمایانگر ویژگی 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | نمایانگر ویژگی 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | نمایانگر ویژگی 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | نمایانگر ویژگی 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | نمایانگر ویژگی 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | نمایانگر ویژگی 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | نمایانگر ویژگی 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | نمایانگر ویژگی 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | نمایانگر ویژگی 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | نمایانگر ویژگی 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | نمایانگر ویژگی 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | نمایانگر ویژگی 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | نمایانگر ویژگی 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | نمایانگر ویژگی 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | نمایانگر ویژگی 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | نمایانگر ویژگی 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | نمایانگر ویژگی 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | نمایانگر ویژگی 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | نمایانگر ویژگی 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | نمایانگر ویژگی 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | نمایانگر ویژگی 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | نمایانگر ویژگی 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | نمایانگر ویژگی 'fill.on' |
| [getFillType()](#getFillType--) | نمایانگر ویژگی 'fill.type' |
| [getFill_Color()](#getFill-Color--) | نمایانگر ویژگی 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | نمایانگر ویژگی 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | نمایانگر ویژگی 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | نمایانگر ویژگی 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | نمایانگر ویژگی 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | نمایانگر ویژگی 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | نمایانگر ویژگی 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | نمایانگر ویژگی 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | نمایانگر ویژگی 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | نمایانگر ویژگی 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | نمایانگر ویژگی 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | نمایانگر ویژگی 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | نمایانگر ویژگی 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | نمایانگر ویژگی 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | نمایانگر ویژگی 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | نمایانگر ویژگی 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | نمایانگر ویژگی 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | نمایانگر ویژگی 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | نمایانگر ویژگی 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | نمایانگر ویژگی 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | نمایانگر ویژگی 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | نمایانگر ویژگی 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | نمایانگر ویژگی 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | نمایانگر ویژگی 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | نمایانگر ویژگی 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | نمایانگر ویژگی 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | نمایانگر ویژگی 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | نمایانگر ویژگی 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | نمایانگر ویژگی 'shadow.on' |
| [getShadowType()](#getShadowType--) | نمایانگر ویژگی 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | نمایانگر ویژگی 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | نمایانگر ویژگی 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | نمایانگر ویژگی 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | نمایانگر ویژگی 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | نمایانگر ویژگی 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | نمایانگر ویژگی 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | نمایانگر ویژگی 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | نمایانگر ویژگی 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | نمایانگر ویژگی 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | نمایانگر ویژگی 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | نمایانگر ویژگی 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | نمایانگر ویژگی 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | نمایانگر ویژگی 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | نمایانگر ویژگی 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | نمایانگر ویژگی 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | نمایانگر ویژگی 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | نمایانگر ویژگی 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | نمایانگر ویژگی 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | نمایانگر ویژگی 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | نمایانگر ویژگی 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | نمایانگر ویژگی 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | نمایانگر ویژگی 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | نمایانگر ویژگی 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | نمایانگر ویژگی 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | نمایانگر ویژگی 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | نمایانگر ویژگی 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | نمایانگر ویژگی 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | نمایانگر ویژگی 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | نمایانگر ویژگی 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | نمایانگر ویژگی 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | نمایانگر ویژگی 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | نمایانگر ویژگی 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | نمایانگر ویژگی 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | نمایانگر ویژگی 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | نمایانگر ویژگی 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | نمایانگر ویژگی 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | نمایانگر ویژگی 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | نمایانگر ویژگی 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | نمایانگر ویژگی 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | نمایانگر ویژگی 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | نمایانگر ویژگی 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | نمایانگر ویژگی 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | نمایانگر ویژگی 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | نمایانگر ویژگی 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | نمایانگر ویژگی 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | نمایانگر ویژگی 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | نمایانگر ویژگی 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | نمایانگر ویژگی 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | نمایانگر ویژگی 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | نمایانگر ویژگی 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | نمایانگر ویژگی 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | نمایانگر ویژگی 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | بررسی می‌کند که آیا این شیء با شیء دیگر برابر است. |
| [hashCode()](#hashCode--) | محاسبه و بازگرداندن کد هش بر پایهٔ ویژگی (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | جستجو برای ویژگی رفتار موجود بر پایهٔ مقدار یا ایجاد یک ویژگی سفارشی جدید با مقدار مشخص‌شده |
### getValue() {#getValue--}
```
public final String getValue()
```

مقدار این ویژگی

**باز می‌گردد:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

نشان می‌دهد که این ویژگی در فهرست ویژگی‌های پیش‌تعریف‌شدهٔ مشخصات موجود نیست: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**باز می‌گردد:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

نمایانگر ویژگی 'ppt_x'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

نمایانگر ویژگی 'ppt_y'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

نمایانگر ویژگی 'ppt_w'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

نمایانگر ویژگی 'ppt_h'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

نمایانگر ویژگی 'ppt_c'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

نمایانگر ویژگی 'ppt_r'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

نمایانگر ویژگی 'xshear'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

نمایانگر ویژگی 'yshear'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

نمایانگر ویژگی 'image'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

نمایانگر ویژگی 'ScaleX'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

نمایانگر ویژگی 'ScaleY'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

نمایانگر ویژگی 'r'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

نمایانگر ویژگی 'fillcolor'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

نمایانگر ویژگی 'style.opacity'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

نمایانگر ویژگی 'style.rotation'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

نمایانگر ویژگی 'style.visibility'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

نمایانگر ویژگی 'style.color'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

نمایانگر ویژگی 'style.fontSize'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

نمایانگر ویژگی 'style.fontWeight'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

نمایانگر ویژگی 'style.fontStyle'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

نمایانگر ویژگی 'style.fontFamily'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

نمایانگر ویژگی 'style.textEffectEmboss'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

نمایانگر ویژگی 'style.textShadow'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

نمایانگر ویژگی 'style.textTransform'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

نمایانگر ویژگی 'style.textDecorationUnderline'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

نمایانگر ویژگی 'style.textEffectOutline'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

نمایانگر ویژگی 'style.textDecorationLineThrough'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

نمایانگر ویژگی 'style.sRotation'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

نمایانگر ویژگی 'imageData.cropTop'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

نمایانگر ویژگی 'imageData.cropBottom'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

نمایانگر ویژگی 'imageData.cropLeft'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

نمایانگر ویژگی 'imageData.cropRight'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

نمایانگر ویژگی 'imageData.gain'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

نمایانگر ویژگی 'imageData.blacklevel'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

نمایانگر ویژگی 'imageData.gamma'

**باز می‌گردد:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

نمایانگر 'imageData.grayscale' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

نمایانگر 'imageData.chromakey' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

نمایانگر 'fill.on' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

نمایانگر 'fill.type' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

نمایانگر 'fill.color' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

نمایانگر 'fill.opacity' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

نمایانگر 'fill.color2' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

نمایانگر 'fill.method' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

نمایانگر 'fill.opacity2' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

نمایانگر 'fill.angle' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

نمایانگر 'fill.focus' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

نمایانگر 'fill.focusposition.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

نمایانگر 'fill.focusposition.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

نمایانگر 'fill.focussize.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

نمایانگر 'fill.focussize.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

نمایانگر 'stroke.on' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

نمایانگر 'stroke.color' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

نمایانگر 'stroke.weight' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

نمایانگر 'stroke.opacity' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

نمایانگر 'stroke.linestyle' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

نمایانگر 'stroke.dashstyle' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

نمایانگر 'stroke.filltype' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

نمایانگر 'stroke.src' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

نمایانگر 'stroke.color2' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

نمایانگر 'stroke.imagesize.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

نمایانگر 'stroke.imagesize.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

نمایانگر 'stroke.startArrow' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

نمایانگر 'stroke.endArrow' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

نمایانگر 'stroke.startArrowWidth' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

نمایانگر 'stroke.startArrowLength' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

نمایانگر 'stroke.endArrowWidth' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

نمایانگر 'stroke.endArrowLength' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

نمایانگر 'shadow.on' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

نمایانگر 'shadow.type' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

نمایانگر 'shadow.color' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

نمایانگر 'shadow.color2' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

نمایانگر 'shadow.opacity' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

نمایانگر 'shadow.offset.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

نمایانگر 'shadow.offset.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

نمایانگر 'shadow.offset2.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

نمایانگر 'shadow.offset2.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

نمایانگر 'shadow.origin.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

نمایانگر 'shadow.origin.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

نمایانگر 'shadow.matrix.xtox' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

نمایانگر 'shadow.matrix.xtoy' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

نمایانگر 'shadow.matrix.ytox' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

نمایانگر 'shadow.matrix.ytoy' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

نمایانگر 'shadow.matrix.perspectiveX' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

نمایانگر 'shadow.matrix.perspectiveY' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

نمایانگر 'skew.on' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

نمایانگر 'skew.offset.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

نمایانگر 'skew.offset.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

نمایانگر 'skew.origin.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

نمایانگر 'skew.origin.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

نمایانگر 'skew.matrix.xtox' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

نمایانگر 'skew.matrix.xtoy' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

نمایانگر 'skew.matrix.ytox' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

نمایانگر 'skew.matrix.ytoy' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

نمایانگر 'skew.matrix.perspectiveX' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

نمایانگر 'skew.matrix.perspectiveY' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

نمایانگر 'extrusion.on' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

نمایانگر 'extrusion.type' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

نمایانگر 'extrusion.render' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

نمایانگر 'extrusion.viewpointorigin.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

نمایانگر 'extrusion.viewpointorigin.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

نمایانگر 'extrusion.viewpoint.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

نمایانگر 'extrusion.viewpoint.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

نمایانگر 'extrusion.viewpoint.z' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

نمایانگر 'extrusion.plane' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

نمایانگر 'extrusion.skewangle' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

نمایانگر 'extrusion.skewamt' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

نمایانگر 'extrusion.backdepth' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

نمایانگر 'extrusion.foredepth' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

نمایانگر 'extrusion.orientation.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

نمایانگر 'extrusion.orientation.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

نمایانگر 'extrusion.orientation.z' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

نمایانگر 'extrusion.orientationangle' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

نمایانگر 'extrusion.color' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

نمایانگر 'extrusion.rotationangle.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

نمایانگر 'extrusion.rotationangle.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

نمایانگر 'extrusion.lockrotationcenter' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

نمایانگر 'extrusion.autorotationcenter' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

نمایانگر 'extrusion.rotationcenter.x' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

نمایانگر 'extrusion.rotationcenter.y' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

نمایانگر 'extrusion.rotationcenter.z' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

نمایانگر 'extrusion.colormode' ویژگی

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

بررسی می‌کند آیا این شیء با شیء دیگری برابر است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | شیء برای مقایسه. |

**باز می‌گرداند:**
boolean - درست اگر اشیاء برابر باشند.

### hashCode() {#hashCode--}
```
public int hashCode()
```

محاسبه و بازگرداندن کد هش بر اساس ویژگی (\#getValue.getValue)

**باز می‌گرداند:**
int - کد هش این شیء را برمی‌گرداند

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

به دنبال ویژگی رفتار موجود با مقدار می‌گردد یا یک مورد سفارشی جدید با مقدار مشخص شده ایجاد می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی |

**باز می‌گرداند:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - نمونه‌ای از BehaviorProperty