---
title: BehaviorProperty
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili tipe properti untuk perilaku animasi.
type: docs
url: /id/com.aspose.slides/behaviorproperty/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Mewakili tipe properti untuk perilaku animasi. Mengikuti daftar properti dari https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx dan https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getValue()](#getValue--) | Nilai properti |
| [isCustom()](#isCustom--) | Menunjukkan apakah properti ini tidak termasuk dalam daftar properti pra-definisi pada spesifikasi: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Mewakili properti 'ppt_x' |
| [getPptY()](#getPptY--) | Mewakili properti 'ppt_y' |
| [getPptW()](#getPptW--) | Mewakili properti 'ppt_w' |
| [getPptH()](#getPptH--) | Mewakili properti 'ppt_h' |
| [getPptC()](#getPptC--) | Mewakili properti 'ppt_c' |
| [getPptR()](#getPptR--) | Mewakili properti 'ppt_r' |
| [getXShear()](#getXShear--) | Mewakili properti 'xshear' |
| [getYShear()](#getYShear--) | Mewakili properti 'yshear' |
| [getImage()](#getImage--) | Mewakili properti 'image' |
| [getScaleX()](#getScaleX--) | Mewakili properti 'ScaleX' |
| [getScaleY()](#getScaleY--) | Mewakili properti 'ScaleY' |
| [getR()](#getR--) | Mewakili properti 'r' |
| [getFillColor()](#getFillColor--) | Mewakili properti 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Mewakili properti 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Mewakili properti 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Mewakili properti 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Mewakili properti 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Mewakili properti 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Mewakili properti 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Mewakili properti 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Mewakili properti 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Mewakili properti 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Mewakili properti 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Mewakili properti 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Mewakili properti 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Mewakili properti 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Mewakili properti 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Mewakili properti 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Mewakili properti 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Mewakili properti 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Mewakili properti 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Mewakili properti 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Mewakili properti 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Mewakili properti 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Mewakili properti 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Mewakili properti 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Mewakili properti 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Mewakili properti 'fill.on' |
| [getFillType()](#getFillType--) | Mewakili properti 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Mewakili properti 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Mewakili properti 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Mewakili properti 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Mewakili properti 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Mewakili properti 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Mewakili properti 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Mewakili properti 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Mewakili properti 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Mewakili properti 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Mewakili properti 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Mewakili properti 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Mewakili properti 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Mewakili properti 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Mewakili properti 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Mewakili properti 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Mewakili properti 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Mewakili properti 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Mewakili properti 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Mewakili properti 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Mewakili properti 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Mewakili properti 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Mewakili properti 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Mewakili properti 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Mewakili properti 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Mewakili properti 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Mewakili properti 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Mewakili properti 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Mewakili properti 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Mewakili properti 'shadow.on' |
| [getShadowType()](#getShadowType--) | Mewakili properti 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Mewakili properti 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Mewakili properti 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Mewakili properti 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Mewakili properti 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Mewakili properti 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Mewakili properti 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Mewakili properti 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Mewakili properti 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Mewakili properti 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Mewakili properti 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Mewakili properti 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Mewakili properti 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Mewakili properti 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Mewakili properti 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Mewakili properti 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Mewakili properti 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Mewakili properti 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Mewakili properti 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Mewakili properti 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Mewakili properti 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Mewakili properti 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Mewakili properti 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Mewakili properti 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Mewakili properti 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Mewakili properti 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Mewakili properti 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Mewakili properti 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Mewakili properti 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Mewakili properti 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Mewakili properti 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Mewakili properti 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Mewakili properti 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Mewakili properti 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Mewakili properti 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Mewakili properti 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Mewakili properti 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Mewakili properti 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Mewakili properti 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Mewakili properti 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Mewakili properti 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Mewakili properti 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Mewakili properti 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Mewakili properti 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Mewakili properti 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Mewakili properti 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Mewakili properti 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Mewakili properti 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Mewakili properti 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Mewakili properti 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Mewakili properti 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Mewakili properti 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Mewakili properti 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Memeriksa apakah objek ini sama dengan objek lain. |
| [hashCode()](#hashCode--) | Menghitung dan mengembalikan kode hash berdasarkan properti (#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Mencari properti perilaku yang ada berdasarkan nilai atau membuat yang baru khusus dengan nilai yang ditentukan |

### getValue() {#getValue--}
```
public final String getValue()
```

Nilai properti

**Mengembalikan:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Menunjukkan apakah properti ini tidak termasuk dalam daftar properti pra-definisi pada spesifikasi: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Mengembalikan:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Mewakili properti 'ppt_x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Mewakili properti 'ppt_y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Mewakili properti 'ppt_w'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Mewakili properti 'ppt_h'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Mewakili properti 'ppt_c'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Mewakili properti 'ppt_r'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Mewakili properti 'xshear'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Mewakili properti 'yshear'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Mewakili properti 'image'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Mewakili properti 'ScaleX'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Mewakili properti 'ScaleY'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Mewakili properti 'r'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Mewakili properti 'fillcolor'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Mewakili properti 'style.opacity'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Mewakili properti 'style.rotation'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Mewakili properti 'style.visibility'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Mewakili properti 'style.color'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Mewakili properti 'style.fontSize'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Mewakili properti 'style.fontWeight'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Mewakili properti 'style.fontStyle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Mewakili properti 'style.fontFamily'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Mewakili properti 'style.textEffectEmboss'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Mewakili properti 'style.textShadow'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Mewakili properti 'style.textTransform'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Mewakili properti 'style.textDecorationUnderline'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Mewakili properti 'style.textEffectOutline'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public               —    V   
```

Mewakili properti 'style.textDecorationLineThrough'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Mewakili properti 'style.sRotation'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Mewakili properti 'imageData.cropTop'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Mewakili properti 'imageData.cropBottom'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Mewakili properti 'imageData.cropLeft'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Mewakili properti 'imageData.cropRight'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Mewakili properti 'imageData.gain'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Mewakili properti 'imageData.blacklevel'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Mewakili properti 'imageData.gamma'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Mewakili properti 'imageData.grayscale'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Mewakili properti 'imageData.chromakey'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```java
public static BehaviorProperty getFillOn()
```

Mewakili properti 'fill.on'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Mewakili properti 'fill.type'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Mewakili properti 'fill.color'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Mewakili properti 'fill.opacity'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Mewakili properti 'fill.color2'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Mewakili properti 'fill.method'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Mewakili properti 'fill.opacity2'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public   —             
```

Mewakili properti 'fill.angle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Mewakili properti 'fill.focus'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Mewakili properti 'fill.focusposition.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Mewakili properti 'fill.focusposition.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Mewakili properti 'fill.focussize.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Mewakili properti 'fill.focussize.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Mewakili properti 'stroke.on'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Mewakili properti 'stroke.color'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Mewakili properti 'stroke.weight'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Mewakili properti 'stroke.opacity'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Mewakili properti 'stroke.linestyle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Mewakili properti 'stroke.dashstyle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Mewakili properti 'stroke.filltype'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Mewakili properti 'stroke.src'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Mewakili properti 'stroke.color2'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Mewakili properti 'stroke.imagesize.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Mewakili properti 'stroke.imagesize.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Mewakili properti 'stroke.startArrow'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Mewakili properti 'stroke.endArrow'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Mewakili properti 'stroke.startArrowWidth'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Mewakili properti 'stroke.startArrowLength'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Mewakili properti 'stroke.endArrowWidth'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Mewakili properti 'stroke.endArrowLength'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Mewakili properti 'shadow.on'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Mewakili properti 'shadow.type'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public         ... 
```

Mewakili properti 'shadow.color'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Mewakili properti 'shadow.color2'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Mewakili properti 'shadow.opacity'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public    ... 
```

Mewakili properti 'shadow.offset.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Mewakili properti 'shadow.offset.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Mewakili properti 'shadow.offset2.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Mewakili properti 'shadow.offset2.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Mewakili properti 'shadow.origin.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Mewakili properti 'shadow.origin.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Mewakili properti 'shadow.matrix.xtox'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Mewakili properti 'shadow.matrix.xtoy'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Mewakili properti 'shadow.matrix.ytox'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Mewakili properti 'shadow.matrix.ytoy'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Mewakili properti 'shadow.matrix.perspectiveX'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Mewakili properti 'shadow.matrix.perspectiveY'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Mewakili properti 'skew.on'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Mewakili properti 'skew.offset.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Mewakili properti 'skew.offset.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public  …   
```

Mewakili properti 'skew.origin.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Mewakili properti 'skew.origin.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Mewakili properti 'skew.matrix.xtox'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Mewakili properti 'skew.matrix.xtoy'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Mewakili properti 'skew.matrix.ytox'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Mewakili properti 'skew.matrix.ytoy'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Mewakili properti 'skew.matrix.perspectiveX'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Mewakili properti 'skew.matrix.perspectiveY'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Mewakili properti 'extrusion.on'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Mewakili properti 'extrusion.type'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Mewakili properti 'extrusion.render'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Mewakili properti 'extrusion.viewpointorigin.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Mewakili properti 'extrusion.viewpointorigin.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Mewakili properti 'extrusion.viewpoint.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Mewakili properti 'extrusion.viewpoint.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Mewakili properti 'extrusion.viewpoint.z'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Mewakili properti 'extrusion.plane'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Mewakili properti 'extrusion.skewangle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
`````
Apabila Anda memerlukan bantuan lebih lanjut atau memiliki pertanyaan, mohon beri tahu saya.
```

Mewakili properti 'extrusion.skewamt'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Mewakili properti 'extrusion.backdepth'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Mewakili properti 'extrusion.foredepth'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Mewakili properti 'extrusion.orientation.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Mewakili properti 'extrusion.orientation.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Mewakili properti 'extrusion.orientation.z'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Mewakili properti 'extrusion.orientationangle'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Mewakili properti 'extrusion.color'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Mewakili properti 'extrusion.rotationangle.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Mewakili properti 'extrusion.rotationangle.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Mewakili properti 'extrusion.lockrotationcenter'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Mewakili properti 'extrusion.autorotationcenter'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Mewakili properti 'extrusion.rotationcenter.x'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Mewakili properti 'extrusion.rotationcenter.y'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Mewakili properti 'extrusion.rotationcenter.z'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Mewakili properti 'extrusion.colormode'

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Memeriksa apakah objek ini sama dengan objek lain.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang dibandingkan. |

**Mengembalikan:**
boolean - True jika objek sama.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Menghitung dan mengembalikan kode hash berdasarkan properti (#getValue.getValue)

**Mengembalikan:**
int - Mengembalikan kode hash untuk objek ini

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Mencari properti perilaku yang ada berdasarkan nilai atau membuat yang baru khusus dengan nilai yang ditentukan

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| propertyValue | java.lang.String | nilai properti |

**Mengembalikan:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance of BehaviorProperty