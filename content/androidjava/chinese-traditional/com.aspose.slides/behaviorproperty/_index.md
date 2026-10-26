---
title: BehaviorProperty
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示動畫行為的屬性類型。
type: docs
url: /zh-hant/com.aspose.slides/behaviorproperty/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

表示動畫行為的屬性類型。遵循來自 https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 和 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx 的屬性清單。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getValue()](#getValue--) | 屬性的值 |
| [isCustom()](#isCustom--) | 顯示此屬性是否不屬於規範中預定義的屬性清單： https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | 表示 'ppt_x' 屬性 |
| [getPptY()](#getPptY--) | 表示 'ppt_y' 屬性 |
| [getPptW()](#getPptW--) | 表示 'ppt_w' 屬性 |
| [getPptH()](#getPptH--) | 表示 'ppt_h' 屬性 |
| [getPptC()](#getPptC--) | 表示 'ppt_c' 屬性 |
| [getPptR()](#getPptR--) | 表示 'ppt_r' 屬性 |
| [getXShear()](#getXShear--) | 表示 'xshear' 屬性 |
| [getYShear()](#getYShear--) | 表示 'yshear' 屬性 |
| [getImage()](#getImage--) | 表示 'image' 屬性 |
| [getScaleX()](#getScaleX--) | 表示 'ScaleX' 屬性 |
| [getScaleY()](#getScaleY--) | 表示 'ScaleY' 屬性 |
| [getR()](#getR--) | 表示 'r' 屬性 |
| [getFillColor()](#getFillColor--) | 表示 'fillcolor' 屬性 |
| [getStyleOpacity()](#getStyleOpacity--) | 表示 'style.opacity' 屬性 |
| [getStyleRotation()](#getStyleRotation--) | 表示 'style.rotation' 屬性 |
| [getStyleVisibility()](#getStyleVisibility--) | 表示 'style.visibility' 屬性 |
| [getStyleColor()](#getStyleColor--) | 表示 'style.color' 屬性 |
| [getStyleFontSize()](#getStyleFontSize--) | 表示 'style.fontSize' 屬性 |
| [getStyleFontWeight()](#getStyleFontWeight--) | 表示 'style.fontWeight' 屬性 |
| [getStyleFontStyle()](#getStyleFontStyle--) | 表示 'style.fontStyle' 屬性 |
| [getStyleFontFamily()](#getStyleFontFamily--) | 表示 'style.fontFamily' 屬性 |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | 表示 'style.textEffectEmboss' 屬性 |
| [getStyleTextShadow()](#getStyleTextShadow--) | 表示 'style.textShadow' 屬性 |
| [getStyleTextTransform()](#getStyleTextTransform--) | 表示 'style.textTransform' 屬性 |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | 表示 'style.textDecorationUnderline' 屬性 |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | 表示 'style.textEffectOutline' 屬性 |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | 表示 'style.textDecorationLineThrough' 屬性 |
| [getStyleSRotation()](#getStyleSRotation--) | 表示 'style.sRotation' 屬性 |
| [getImageDataCropTop()](#getImageDataCropTop--) | 表示 'imageData.cropTop' 屬性 |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | 表示 'imageData.cropBottom' 屬性 |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | 表示 'imageData.cropLeft' 屬性 |
| [getImageDataCropRight()](#getImageDataCropRight--) | 表示 'imageData.cropRight' 屬性 |
| [getImageDataGain()](#getImageDataGain--) | 表示 'imageData.gain' 屬性 |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | 表示 'imageData.blacklevel' 屬性 |
| [getImageDataGamma()](#getImageDataGamma--) | 表示 'imageData.gamma' 屬性 |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | 表示 'imageData.grayscale' 屬性 |
| [getImageDataChromakey()](#getImageDataChromakey--) | 表示 'imageData.chromakey' 屬性 |
| [getFillOn()](#getFillOn--) | 表示 'fill.on' 屬性 |
| [getFillType()](#getFillType--) | 表示 'fill.type' 屬性 |
| [getFill_Color()](#getFill-Color--) | 表示 'fill.color' 屬性 |
| [getFillOpacity()](#getFillOpacity--) | 表示 'fill.opacity' 屬性 |
| [getFillColor2()](#getFillColor2--) | 表示 'fill.color2' 屬性 |
| [getFillMethod()](#getFillMethod--) | 表示 'fill.method' 屬性 |
| [getFillOpacity2()](#getFillOpacity2--) | 表示 'fill.opacity2' 屬性 |
| [getFillAngle()](#getFillAngle--) | 表示 'fill.angle' 屬性 |
| [getFillFocus()](#getFillFocus--) | 表示 'fill.focus' 屬性 |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | 表示 'fill.focusposition.x' 屬性 |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | 表示 'fill.focusposition.y' 屬性 |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | 表示 'fill.focussize.x' 屬性 |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | 表示 'fill.focussize.y' 屬性 |
| [getStrokeOn()](#getStrokeOn--) | 表示 'stroke.on' 屬性 |
| [getStrokeColor()](#getStrokeColor--) | 表示 'stroke.color' 屬性 |
| [getStrokeWeight()](#getStrokeWeight--) | 表示 'stroke.weight' 屬性 |
| [getStrokeOpacity()](#getStrokeOpacity--) | 表示 'stroke.opacity' 屬性 |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | 表示 'stroke.linestyle' 屬性 |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | 表示 'stroke.dashstyle' 屬性 |
| [getStrokeFillType()](#getStrokeFillType--) | 表示 'stroke.filltype' 屬性 |
| [getStrokeSrc()](#getStrokeSrc--) | 表示 'stroke.src' 屬性 |
| [getStrokeColor2()](#getStrokeColor2--) | 表示 'stroke.color2' 屬性 |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | 表示 'stroke.imagesize.x' 屬性 |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | 表示 'stroke.imagesize.y' 屬性 |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | 表示 'stroke.startArrow' 屬性 |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | 表示 'stroke.endArrow' 屬性 |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | 表示 'stroke.startArrowWidth' 屬性 |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | 表示 'stroke.startArrowLength' 屬性 |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | 表示 'stroke.endArrowWidth' 屬性 |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | 表示 'stroke.endArrowLength' 屬性 |
| [getShadowOn()](#getShadowOn--) | 表示 'shadow.on' 屬性 |
| [getShadowType()](#getShadowType--) | 表示 'shadow.type' 屬性 |
| [getShadowColor()](#getShadowColor--) | 表示 'shadow.color' 屬性 |
| [getShadowColor2()](#getShadowColor2--) | 表示 'shadow.color2' 屬性 |
| [getShadowOpacity()](#getShadowOpacity--) | 表示 'shadow.opacity' 屬性 |
| [getShadowOffsetX()](#getShadowOffsetX--) | 表示 'shadow.offset.x' 屬性 |
| [getShadowOffsetY()](#getShadowOffsetY--) | 表示 'shadow.offset.y' 屬性 |
| [getShadowOffset2X()](#getShadowOffset2X--) | 表示 'shadow.offset2.x' 屬性 |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | 表示 'shadow.offset2.y' 屬性 |
| [getShadowOriginX()](#getShadowOriginX--) | 表示 'shadow.origin.x' 屬性 |
| [getShadowOriginY()](#getShadowOriginY--) | 表示 'shadow.origin.y' 屬性 |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | 表示 'shadow.matrix.xtox' 屬性 |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | 表示 'shadow.matrix.xtoy' 屬性 |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | 表示 'shadow.matrix.ytox' 屬性 |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | 表示 'shadow.matrix.ytoy' 屬性 |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | 表示 'shadow.matrix.perspectiveX' 屬性 |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | 表示 'shadow.matrix.perspectiveY' 屬性 |
| [getSkewOn()](#getSkewOn--) | 表示 'skew.on' 屬性 |
| [getSkewOffsetX()](#getSkewOffsetX--) | 表示 'skew.offset.x' 屬性 |
| [getSkewOffsetY()](#getSkewOffsetY--) | 表示 'skew.offset.y' 屬性 |
| [getSkewOriginX()](#getSkewOriginX--) | 表示 'skew.origin.x' 屬性 |
| [getSkewOriginY()](#getSkewOriginY--) | 表示 'skew.origin.y' 屬性 |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | 表示 'skew.matrix.xtox' 屬性 |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | 表示 'skew.matrix.xtoy' 屬性 |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | 表示 'skew.matrix.ytox' 屬性 |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | 表示 'skew.matrix.ytoy' 屬性 |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | 表示 'skew.matrix.perspectiveX' 屬性 |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | 表示 'skew.matrix.perspectiveY' 屬性 |
| [getExtrusionOn()](#getExtrusionOn--) | 表示 'extrusion.on' 屬性 |
| [getExtrusionType()](#getExtrusionType--) | 表示 'extrusion.type' 屬性 |
| [getExtrusionRender()](#getExtrusionRender--) | 表示 'extrusion.render' 屬性 |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | 表示 'extrusion.viewpointorigin.x' 屬性 |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | 表示 'extrusion.viewpointorigin.y' 屬性 |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | 表示 'extrusion.viewpoint.x' 屬性 |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | 表示 'extrusion.viewpoint.y' 屬性 |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | 表示 'extrusion.viewpoint.z' 屬性 |
| [getExtrusionPlane()](#getExtrusionPlane--) | 表示 'extrusion.plane' 屬性 |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | 表示 'extrusion.skewangle' 屬性 |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | 表示 'extrusion.skewamt' 屬性 |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | 表示 'extrusion.backdepth' 屬性 |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | 表示 'extrusion.foredepth' 屬性 |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | 表示 'extrusion.orientation.x' 屬性 |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | 表示 'extrusion.orientation.y' 屬性 |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | 表示 'extrusion.orientation.z' 屬性 |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | 表示 'extrusion.orientationangle' 屬性 |
| [getExtrusionColor()](#getExtrusionColor--) | 表示 'extrusion.color' 屬性 |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | 表示 'extrusion.rotationangle.x' 屬性 |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | 表示 'extrusion.rotationangle.y' 屬性 |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | 表示 'extrusion.lockrotationcenter' 屬性 |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | 表示 'extrusion.autorotationcenter' 屬性 |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | 表示 'extrusion.rotationcenter.x' 屬性 |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | 表示 'extrusion.rotationcenter.y' 屬性 |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | 表示 'extrusion.rotationcenter.z' 屬性 |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | 表示 'extrusion.colormode' 屬性 |
| [equals(Object obj)](#equals-java.lang.Object-) | 檢查此物件是否等於另一個物件。 |
| [hashCode()](#hashCode--) | 根據 (\#getValue.getValue) 屬性計算並傳回雜湊碼 |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | 依值搜尋現有的行為屬性，或以指定的值建立新的自訂屬性 |

### getValue() {#getValue--}
```
public final String getValue()
```

屬性的值

**傳回：**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

顯示此屬性是否不屬於規範中預定義的屬性清單： https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**傳回：**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

表示 'ppt_x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

表示 'ppt_y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

表示 'ppt_w' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

表示 'ppt_h' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

表示 'ppt_c' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

表示 'ppt_r' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

表示 'xshear' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

表示 'yshear' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

表示 'image' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

表示 'ScaleX' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

表示 'ScaleY' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

表示 'r' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

表示 'fillcolor' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

表示 'style.opacity' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

表示 'style.rotation' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

表示 'style.visibility' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

表示 'style.color' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

表示 'style.fontSize' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

表示 'style.fontWeight' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

表示 'style.fontStyle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

表示 'style.fontFamily' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

表示 'style.textEffectEmboss' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

表示 'style.textShadow' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

表示 'style.textTransform' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

表示 'style.textDecorationUnderline' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

表示 'style.textEffectOutline' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

表示 'style.textDecorationLineThrough' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

表示 'style.sRotation' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

表示 'imageData.cropTop' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

表示 'imageData.cropBottom' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

表示 'imageData.cropLeft' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

表示 'imageData.cropRight' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

表示 'imageData.gain' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

表示 'imageData.blacklevel' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

表示 'imageData.gamma' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

表示 'imageData.grayscale' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

表示 'imageData.chromakey' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

表示 'fill.on' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public

```

表示 'fill.type' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

表示 'fill.color' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

表示 'fill.opacity' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

表示 'fill.color2' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

表示 'fill.method' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

表示 'fill.opacity2' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

表示 'fill.angle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

表示 'fill.focus' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

表示 'fill.focusposition.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

表示 'fill.focusposition.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

表示 'fill.focussize.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

表示 'fill.focussize.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

表示 'stroke.on' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

表示 'stroke.color' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

表示 'stroke.weight' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

表示 'stroke.opacity' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

表示 'stroke.linestyle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

表示 'stroke.dashstyle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

表示 'stroke.filltype' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

表示 'stroke.src' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

表示 'stroke.color2' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

表示 'stroke.imagesize.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

表示 'stroke.imagesize.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

表示 'stroke.startArrow' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

表示 'stroke.endArrow' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

表示 'stroke.startArrowWidth' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

表示 'stroke.startArrowLength' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

表示 'stroke.endArrowWidth' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

表示 'stroke.endArrowLength' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

表示 'shadow.on' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

表示 'shadow.type' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

表示 'shadow.color' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

表示 'shadow.color2' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

表示 'shadow.opacity' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

表示 'shadow.offset.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

表示 'shadow.offset.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

表示 'shadow.offset2.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

表示 'shadow.offset2.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

表示 'shadow.origin.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

表示 'shadow.origin.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

表示 'shadow.matrix.xtox' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

表示 'shadow.matrix.xtoy' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

表示 'shadow.matrix.ytox' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

表示 'shadow.matrix.ytoy' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

表示 'shadow.matrix.perspectiveX' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

表示 'shadow.matrix.perspectiveY' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

表示 'skew.on' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

表示 'skew.offset.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

表示 'skew.offset.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

表示 'skew.origin.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

表示 'skew.origin.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

表示 'skew.matrix.xtox' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

表示 'skew.matrix.xtoy' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

表示 'skew.matrix.ytox' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

表示 'skew.matrix.ytoy' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

表示 'skew.matrix.perspectiveX' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

表示 'skew.matrix.perspectiveY' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

表示 'extrusion.on' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

表示 'extrusion.type' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

表示 'extrusion.render' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

表示 'extrusion.viewpointorigin.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

表示 'extrusion.viewpointorigin.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

表示 'extrusion.viewpoint.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

表示 'extrusion.viewpoint.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

表示 'extrusion.viewpoint.z' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

表示 'extrusion.plane' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

表示 'extrusion.skewangle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

表示 'extrusion.skewamt' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

表示 'extrusion.backdepth' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

表示 'extrusion.foredepth' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

表示 'extrusion.orientation.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

表示 'extrusion.orientation.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

表示 'extrusion.orientation.z' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

表示 'extrusion.orientationangle' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

表示 'extrusion.color' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

表示 'extrusion.rotationangle.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

表示 'extrusion.rotationangle.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

表示 'extrusion.lockrotationcenter' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

表示 'extrusion.autorotationcenter' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

表示 'extrusion.rotationcenter.x' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

表示 'extrusion.rotationcenter.y' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

表示 'extrusion.rotationcenter.z' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

表示 'extrusion.colormode' 屬性

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

檢查此物件是否等於另一個物件。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的物件。 |

**傳回：**
boolean - 若物件相等則為 true。

### hashCode() {#hashCode--}
```
public int hashCode()
```

根據 (\#getValue.getValue) 屬性計算並傳回雜湊碼

**傳回：**
int - 傳回此物件的雜湊碼

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

依值搜尋現有的行為屬性，或以指定的值建立新的自訂屬性

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| propertyValue | java.lang.String | 屬性的值 |

**傳回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty 的實例