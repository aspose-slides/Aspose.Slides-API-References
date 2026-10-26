---
title: BehaviorProperty
second_title: Android için Aspose.Slides Java API Referansı
description: Animasyon davranışı için özellik türlerini temsil eder.
type: docs
url: /tr/com.aspose.slides/behaviorproperty/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Animasyon davranışı için özellik tiplerini temsil eder. Özellik listesi https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx ve https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx adreslerinden alınmıştır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Özelliğin değeri |
| [isCustom()](#isCustom--) | Bu özelliğin, belirtimdeki önceden tanımlanmış özellikler listesine ait olmadığını gösterir: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | ‘ppt\_x’ özelliğini temsil eder |
| [getPptY()](#getPptY--) | ‘ppt\_y’ özelliğini temsil eder |
| [getPptW()](#getPptW--) | ‘ppt\_w’ özelliğini temsil eder |
| [getPptH()](#getPptH--) | ‘ppt\_h’ özelliğini temsil eder |
| [getPptC()](#getPptC--) | ‘ppt\_c’ özelliğini temsil eder |
| [getPptR()](#getPptR--) | ‘ppt\_r’ özelliğini temsil eder |
| [getXShear()](#getXShear--) | ‘xshear’ özelliğini temsil eder |
| [getYShear()](#getYShear--) | ‘yshear’ özelliğini temsil eder |
| [getImage()](#getImage--) | ‘image’ özelliğini temsil eder |
| [getScaleX()](#getScaleX--) | ‘ScaleX’ özelliğini temsil eder |
| [getScaleY()](#getScaleY--) | ‘ScaleY’ özelliğini temsil eder |
| [getR()](#getR--) | ‘r’ özelliğini temsil eder |
| [getFillColor()](#getFillColor--) | ‘fillcolor’ özelliğini temsil eder |
| [getStyleOpacity()](#getStyleOpacity--) | ‘style.opacity’ özelliğini temsil eder |
| [getStyleRotation()](#getStyleRotation--) | ‘style.rotation’ özelliğini temsil eder |
| [getStyleVisibility()](#getStyleVisibility--) | ‘style.visibility’ özelliğini temsil eder |
| [getStyleColor()](#getStyleColor--) | ‘style.color’ özelliğini temsil eder |
| [getStyleFontSize()](#getStyleFontSize--) | ‘style.fontSize’ özelliğini temsil eder |
| [getStyleFontWeight()](#getStyleFontWeight--) | ‘style.fontWeight’ özelliğini temsil eder |
| [getStyleFontStyle()](#getStyleFontStyle--) | ‘style.fontStyle’ özelliğini temsil eder |
| [getStyleFontFamily()](#getStyleFontFamily--) | ‘style.fontFamily’ özelliğini temsil eder |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | ‘style.textEffectEmboss’ özelliğini temsil eder |
| [getStyleTextShadow()](#getStyleTextShadow--) | ‘style.textShadow’ özelliğini temsil eder |
| [getStyleTextTransform()](#getStyleTextTransform--) | ‘style.textTransform’ özelliğini temsil eder |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | ‘style.textDecorationUnderline’ özelliğini temsil eder |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | ‘style.textEffectOutline’ özelliğini temsil eder |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | ‘style.textDecorationLineThrough’ özelliğini temsil eder |
| [getStyleSRotation()](#getStyleSRotation--) | ‘style.sRotation’ özelliğini temsil eder |
| [getImageDataCropTop()](#getImageDataCropTop--) | ‘imageData.cropTop’ özelliğini temsil eder |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | ‘imageData.cropBottom’ özelliğini temsil eder |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | ‘imageData.cropLeft’ özelliğini temsil eder |
| [getImageDataCropRight()](#getImageDataCropRight--) | ‘imageData.cropRight’ özelliğini temsil eder |
| [getImageDataGain()](#getImageDataGain--) | ‘imageData.gain’ özelliğini temsil eder |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | ‘imageData.blacklevel’ özelliğini temsil eder |
| [getImageDataGamma()](#getImageDataGamma--) | ‘imageData.gamma’ özelliğini temsil eder |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | ‘imageData.grayscale’ özelliğini temsil eder |
| [getImageDataChromakey()](#getImageDataChromakey--) | ‘imageData.chromakey’ özelliğini temsil eder |
| [getFillOn()](#getFillOn--) | ‘fill.on’ özelliğini temsil eder |
| [getFillType()](#getFillType--) | ‘fill.type’ özelliğini temsil eder |
| [getFill_Color()](#getFill-Color--) | ‘fill.color’ özelliğini temsil eder |
| [getFillOpacity()](#getFillOpacity--) | ‘fill.opacity’ özelliğini temsil eder |
| [getFillColor2()](#getFillColor2--) | ‘fill.color2’ özelliğini temsil eder |
| [getFillMethod()](#getFillMethod--) | ‘fill.method’ özelliğini temsil eder |
| [getFillOpacity2()](#getFillOpacity2--) | ‘fill.opacity2’ özelliğini temsil eder |
| [getFillAngle()](#getFillAngle--) | ‘fill.angle’ özelliğini temsil eder |
| [getFillFocus()](#getFillFocus--) | ‘fill.focus’ özelliğini temsil eder |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | ‘fill.focusposition.x’ özelliğini temsil eder |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | ‘fill.focusposition.y’ özelliğini temsil eder |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | ‘fill.focussize.x’ özelliğini temsil eder |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | ‘fill.focussize.y’ özelliğini temsil eder |
| [getStrokeOn()](#getStrokeOn--) | ‘stroke.on’ özelliğini temsil eder |
| [getStrokeColor()](#getStrokeColor--) | ‘stroke.color’ özelliğini temsil eder |
| [getStrokeWeight()](#getStrokeWeight--) | ‘stroke.weight’ özelliğini temsil eder |
| [getStrokeOpacity()](#getStrokeOpacity--) | ‘stroke.opacity’ özelliğini temsil eder |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | ‘stroke.linestyle’ özelliğini temsil eder |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | ‘stroke.dashstyle’ özelliğini temsil eder |
| [getStrokeFillType()](#getStrokeFillType--) | ‘stroke.filltype’ özelliğini temsil eder |
| [getStrokeSrc()](#getStrokeSrc--) | ‘stroke.src’ özelliğini temsil eder |
| [getStrokeColor2()](#getStrokeColor2--) | ‘stroke.color2’ özelliğini temsil eder |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | ‘stroke.imagesize.x’ özelliğini temsil eder |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | ‘stroke.imagesize.y’ özelliğini temsil eder |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | ‘stroke.startArrow’ özelliğini temsil eder |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | ‘stroke.endArrow’ özelliğini temsil eder |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | ‘stroke.startArrowWidth’ özelliğini temsil eder |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | ‘stroke.startArrowLength’ özelliğini temsil eder |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | ‘stroke.endArrowWidth’ özelliğini temsil eder |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | ‘stroke.endArrowLength’ özelliğini temsil eder |
| [getShadowOn()](#getShadowOn--) | ‘shadow.on’ özelliğini temsil eder |
| [getShadowType()](#getShadowType--) | ‘shadow.type’ özelliğini temsil eder |
| [getShadowColor()](#getShadowColor--) | ‘shadow.color’ özelliğini temsil eder |
| [getShadowColor2()](#getShadowColor2--) | ‘shadow.color2’ özelliğini temsil eder |
| [getShadowOpacity()](#getShadowOpacity--) | ‘shadow.opacity’ özelliğini temsil eder |
| [getShadowOffsetX()](#getShadowOffsetX--) | ‘shadow.offset.x’ özelliğini temsil eder |
| [getShadowOffsetY()](#getShadowOffsetY--) | ‘shadow.offset.y’ özelliğini temsil eder |
| [getShadowOffset2X()](#getShadowOffset2X--) | ‘shadow.offset2.x’ özelliğini temsil eder |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | ‘shadow.offset2.y’ özelliğini temsil eder |
| [getShadowOriginX()](#getShadowOriginX--) | ‘shadow.origin.x’ özelliğini temsil eder |
| [getShadowOriginY()](#getShadowOriginY--) | ‘shadow.origin.y’ özelliğini temsil eder |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | ‘shadow.matrix.xtox’ özelliğini temsil eder |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | ‘shadow.matrix.xtoy’ özelliğini temsil eder |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | ‘shadow.matrix.ytox’ özelliğini temsil eder |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | ‘shadow.matrix.ytoy’ özelliğini temsil eder |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | ‘shadow.matrix.perspectiveX’ özelliğini temsil eder |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | ‘shadow.matrix.perspectiveY’ özelliğini temsil eder |
| [getSkewOn()](#getSkewOn--) | ‘skew.on’ özelliğini temsil eder |
| [getSkewOffsetX()](#getSkewOffsetX--) | ‘skew.offset.x’ özelliğini temsil eder |
| [getSkewOffsetY()](#getSkewOffsetY--) | ‘skew.offset.y’ özelliğini temsil eder |
| [getSkewOriginX()](#getSkewOriginX--) | ‘skew.origin.x’ özelliğini temsil eder |
| [getSkewOriginY()](#getSkewOriginY--) | ‘skew.origin.y’ özelliğini temsil eder |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | ‘skew.matrix.xtox’ özelliğini temsil eder |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | ‘skew.matrix.xtoy’ özelliğini temsil eder |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | ‘skew.matrix.ytox’ özelliğini temsil eder |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | ‘skew.matrix.ytoy’ özelliğini temsil eder |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | ‘skew.matrix.perspectiveX’ özelliğini temsil eder |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | ‘skew.matrix.perspectiveY’ özelliğini temsil eder |
| [getExtrusionOn()](#getExtrusionOn--) | ‘extrusion.on’ özelliğini temsil eder |
| [getExtrusionType()](#getExtrusionType--) | ‘extrusion.type’ özelliğini temsil eder |
| [getExtrusionRender()](#getExtrusionRender--) | ‘extrusion.render’ özelliğini temsil eder |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | ‘extrusion.viewpointorigin.x’ özelliğini temsil eder |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | ‘extrusion.viewpointorigin.y’ özelliğini temsil eder |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | ‘extrusion.viewpoint.x’ özelliğini temsil eder |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | ‘extrusion.viewpoint.y’ özelliğini temsil eder |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | ‘extrusion.viewpoint.z’ özelliğini temsil eder |
| [getExtrusionPlane()](#getExtrusionPlane--) | ‘extrusion.plane’ özelliğini temsil eder |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | ‘extrusion.skewangle’ özelliğini temsil eder |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | ‘extrusion.skewamt’ özelliğini temsil eder |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | ‘extrusion.backdepth’ özelliğini temsil eder |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | ‘extrusion.foredepth’ özelliğini temsil eder |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | ‘extrusion.orientation.x’ özelliğini temsil eder |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | ‘extrusion.orientation.y’ özelliğini temsil eder |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | ‘extrusion.orientation.z’ özelliğini temsil eder |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | ‘extrusion.orientationangle’ özelliğini temsil eder |
| [getExtrusionColor()](#getExtrusionColor--) | ‘extrusion.color’ özelliğini temsil eder |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | ‘extrusion.rotationangle.x’ özelliğini temsil eder |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | ‘extrusion.rotationangle.y’ özelliğini temsil eder |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | ‘extrusion.lockrotationcenter’ özelliğini temsil eder |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | ‘extrusion.autorotationcenter’ özelliğini temsil eder |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | ‘extrusion.rotationcenter.x’ özelliğini temsil eder |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | ‘extrusion.rotationcenter.y’ özelliğini temsil eder |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | ‘extrusion.rotationcenter.z’ özelliğini temsil eder |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | ‘extrusion.colormode’ özelliğini temsil eder |
| [equals(Object obj)](#equals-java.lang.Object-) | Nesnenin başka bir nesneye eşit olup olmadığını denetler. |
| [hashCode()](#hashCode--) | (\#getValue.getValue) özelliğine dayalı hash kodunu hesaplar ve döndürür |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Mevcut davranış özelliğini değerine göre arar veya belirtilen değerle yeni özel bir tanım oluşturur |
### getValue() {#getValue--}
```
public final String getValue()
```

Özelliğin değeri

**Döndürür:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Bu özelliğin, belirtimdeki önceden tanımlanmış özellikler listesine ait olmadığını gösterir: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Döndürür:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

‘ppt\_x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

‘ppt\_y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

‘ppt\_w’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

‘ppt\_h’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

‘ppt\_c’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

‘ppt\_r’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

‘xshear’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

‘yshear’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

‘image’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

‘ScaleX’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

‘ScaleY’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

‘r’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

‘fillcolor’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

‘style.opacity’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

‘style.rotation’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

‘style.visibility’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

‘style.color’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

‘style.fontSize’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

‘style.fontWeight’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

‘style.fontStyle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

‘style.fontFamily’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

‘style.textEffectEmboss’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

‘style.textShadow’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

‘style.textTransform’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

‘style.textDecorationUnderline’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

‘style.textEffectOutline’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public        
```

‘style.textDecorationLineThrough’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

‘style.sRotation’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

‘imageData.cropTop’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

‘imageData.cropBottom’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

‘imageData.cropLeft’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

‘imageData.cropRight’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

‘imageData.gain’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

‘imageData.blacklevel’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

‘imageData.gamma’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

‘imageData.grayscale’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

‘imageData.chromakey’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

‘fill.on’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

‘fill.type’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

‘fill.color’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

‘fill.opacity’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

‘fill.color2’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

‘fill.method’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

‘fill.opacity2’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

‘fill.angle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

‘fill.focus’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

‘fill.focusposition.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

‘fill.focusposition.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

‘fill.focussize.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

‘fill.focussize.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

‘stroke.on’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

‘stroke.color’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

‘stroke.weight’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

‘stroke.opacity’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

‘stroke.linestyle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

‘stroke.dashstyle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

‘stroke.filltype’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

‘stroke.src’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

‘stroke.color2’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

‘stroke.imagesize.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

‘stroke.imagesize.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

‘stroke.startArrow’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

‘stroke.endArrow’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

‘stroke.startArrowWidth’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
int    …
```

‘stroke.startArrowLength’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

‘stroke.endArrowWidth’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

‘stroke.endArrowLength’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

‘shadow.on’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

‘shadow.type’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

‘shadow.color’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

‘shadow.color2’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

‘shadow.opacity’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

‘shadow.offset.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

‘shadow.offset.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

‘shadow.offset2.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

‘shadow.offset2.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

‘shadow.origin.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

‘shadow.origin.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

‘shadow.matrix.xtox’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

‘shadow.matrix.xtoy’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

‘shadow.matrix.ytox’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

‘shadow.matrix.ytoy’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

‘shadow.matrix.perspectiveX’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

‘shadow.matrix.perspectiveY’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public    …

300300

```

‘skew.on’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

‘skew.offset.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

‘skew.offset.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

‘skew.origin.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

‘skew.origin.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

‘skew.matrix.xtox’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

‘skew.matrix.xtoy’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

‘skew.matrix.ytox’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

‘skew.matrix.ytoy’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

‘skew.matrix.perspectiveX’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

‘skew.matrix.perspectiveY’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

‘extrusion.on’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

‘extrusion.type’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

‘extrusion.render’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

‘extrusion.viewpointorigin.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

‘extrusion.viewpointorigin.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

‘extrusion.viewpoint.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

‘extrusion.viewpoint.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

‘extrusion.viewpoint.z’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

‘extrusion.plane’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

‘extrusion.skewangle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

‘extrusion.skewamt’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

‘extrusion.backdepth’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

‘extrusion.foredepth’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

‘extrusion.orientation.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

‘extrusion.orientation.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

‘extrusion.orientation.z’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

‘extrusion.orientationangle’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

‘extrusion.color’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

‘extrusion.rotationangle.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

‘extrusion.rotationangle.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

‘extrusion.lockrotationcenter’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

‘extrusion.autorotationcenter’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

‘extrusion.rotationcenter.x’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

‘extrusion.rotationcenter.y’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

‘extrusion.rotationcenter.z’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

‘extrusion.colormode’ özelliğini temsil eder

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Nesnenin başka bir nesneye eşit olup olmadığını denetler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne. |

**Döndürür:**
boolean - Nesneler eşitse true.
### hashCode() {#hashCode--}
```
public int hashCode()
```

(\#getValue.getValue) özelliğine dayalı hash kodunu hesaplar ve döndürür

**Döndürür:**
int - Bu nesne için hash kodu
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public  …

…

…

…

…
```

Mevcut davranış özelliğini değerine göre arar veya belirtilen değerle yeni özel bir tanım oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| propertyValue | java.lang.String | Özelliğin değeri |

**Döndürür:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty örneği