---
title: BehaviorProperty
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: アニメーション ビヘイビアのプロパティタイプを表します。
type: docs
url: /ja/com.aspose.slides/behaviorproperty/
---
**継承:**  
java.lang.Object

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)  
```
public class BehaviorProperty implements IBehaviorProperty
```

アニメーション動作のプロパティタイプを表します。プロパティのリストは https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx と https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx を参照してください。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | プロパティの値 |
| [isCustom()](#isCustom--) | このプロパティが仕様の事前定義されたプロパティリストに属さないかどうかを示します: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | 'ppt_x' プロパティを表します |
| [getPptY()](#getPptY--) | 'ppt_y' プロパティを表します |
| [getPptW()](#getPptW--) | 'ppt_w' プロパティを表します |
| [getPptH()](#getPptH--) | 'ppt_h' プロパティを表します |
| [getPptC()](#getPptC--) | 'ppt_c' プロパティを表します |
| [getPptR()](#getPptR--) | 'ppt_r' プロパティを表します |
| [getXShear()](#getXShear--) | 'xshear' プロパティを表します |
| [getYShear()](#getYShear--) | 'yshear' プロパティを表します |
| [getImage()](#getImage--) | 'image' プロパティを表します |
| [getScaleX()](#getScaleX--) | 'ScaleX' プロパティを表します |
| [getScaleY()](#getScaleY--) | 'ScaleY' プロパティを表します |
| [getR()](#getR--) | 'r' プロパティを表します |
| [getFillColor()](#getFillColor--) | 'fillcolor' プロパティを表します |
| [getStyleOpacity()](#getStyleOpacity--) | 'style.opacity' プロパティを表します |
| [getStyleRotation()](#getStyleRotation--) | 'style.rotation' プロパティを表します |
| [getStyleVisibility()](#getStyleVisibility--) | 'style.visibility' プロパティを表します |
| [getStyleColor()](#getStyleColor--) | 'style.color' プロパティを表します |
| [getStyleFontSize()](#getStyleFontSize--) | 'style.fontSize' プロパティを表します |
| [getStyleFontWeight()](#getStyleFontWeight--) | 'style.fontWeight' プロパティを表します |
| [getStyleFontStyle()](#getStyleFontStyle--) | 'style.fontStyle' プロパティを表します |
| [getStyleFontFamily()](#getStyleFontFamily--) | 'style.fontFamily' プロパティを表します |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | 'style.textEffectEmboss' プロパティを表します |
| [getStyleTextShadow()](#getStyleTextShadow--) | 'style.textShadow' プロパティを表します |
| [getStyleTextTransform()](#getStyleTextTransform--) | 'style.textTransform' プロパティを表します |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | 'style.textDecorationUnderline' プロパティを表します |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | 'style.textEffectOutline' プロパティを表します |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | 'style.textDecorationLineThrough' プロパティを表します |
| [getStyleSRotation()](#getStyleSRotation--) | 'style.sRotation' プロパティを表します |
| [getImageDataCropTop()](#getImageDataCropTop--) | 'imageData.cropTop' プロパティを表します |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | 'imageData.cropBottom' プロパティを表します |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | 'imageData.cropLeft' プロパティを表します |
| [getImageDataCropRight()](#getImageDataCropRight--) | 'imageData.cropRight' プロパティを表します |
| [getImageDataGain()](#getImageDataGain--) | 'imageData.gain' プロパティを表します |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | 'imageData.blacklevel' プロパティを表します |
| [getImageDataGamma()](#getImageDataGamma--) | 'imageData.gamma' プロパティを表します |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | 'imageData.grayscale' プロパティを表します |
| [getImageDataChromakey()](#getImageDataChromakey--) | 'imageData.chromakey' プロパティを表します |
| [getFillOn()](#getFillOn--) | 'fill.on' プロパティを表します |
| [getFillType()](#getFillType--) | 'fill.type' プロパティを表します |
| [getFill_Color()](#getFill-Color--) | 'fill.color' プロパティを表します |
| [getFillOpacity()](#getFillOpacity--) | 'fill.opacity' プロパティを表します |
| [getFillColor2()](#getFillColor2--) | 'fill.color2' プロパティを表します |
| [getFillMethod()](#getFillMethod--) | 'fill.method' プロパティを表します |
| [getFillOpacity2()](#getFillOpacity2--) | 'fill.opacity2' プロパティを表します |
| [getFillAngle()](#getFillAngle--) | 'fill.angle' プロパティを表します |
| [getFillFocus()](#getFillFocus--) | 'fill.focus' プロパティを表します |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | 'fill.focusposition.x' プロパティを表します |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | 'fill.focusposition.y' プロパティを表します |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | 'fill.focussize.x' プロパティを表します |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | 'fill.focussize.y' プロパティを表します |
| [getStrokeOn()](#getStrokeOn--) | 'stroke.on' プロパティを表します |
| [getStrokeColor()](#getStrokeColor--) | 'stroke.color' プロパティを表します |
| [getStrokeWeight()](#getStrokeWeight--) | 'stroke.weight' プロパティを表します |
| [getStrokeOpacity()](#getStrokeOpacity--) | 'stroke.opacity' プロパティを表します |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | 'stroke.linestyle' プロパティを表します |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | 'stroke.dashstyle' プロパティを表します |
| [getStrokeFillType()](#getStrokeFillType--) | 'stroke.filltype' プロパティを表します |
| [getStrokeSrc()](#getStrokeSrc--) | 'stroke.src' プロパティを表します |
| [getStrokeColor2()](#getStrokeColor2--) | 'stroke.color2' プロパティを表します |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | 'stroke.imagesize.x' プロパティを表します |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | 'stroke.imagesize.y' プロパティを表します |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | 'stroke.startArrow' プロパティを表します |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | 'stroke.endArrow' プロパティを表します |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | 'stroke.startArrowWidth' プロパティを表します |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | 'stroke.startArrowLength' プロパティを表します |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | 'stroke.endArrowWidth' プロパティを表します |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | 'stroke.endArrowLength' プロパティを表します |
| [getShadowOn()](#getShadowOn--) | 'shadow.on' プロパティを表します |
| [getShadowType()](#getShadowType--) | 'shadow.type' プロパティを表します |
| [getShadowColor()](#getShadowColor--) | 'shadow.color' プロパティを表します |
| [getShadowColor2()](#getShadowColor2--) | 'shadow.color2' プロパティを表します |
| [getShadowOpacity()](#getShadowOpacity--) | 'shadow.opacity' プロパティを表します |
| [getShadowOffsetX()](#getShadowOffsetX--) | 'shadow.offset.x' プロパティを表します |
| [getShadowOffsetY()](#getShadowOffsetY--) | 'shadow.offset.y' プロパティを表します |
| [getShadowOffset2X()](#getShadowOffset2X--) | 'shadow.offset2.x' プロパティを表します |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | 'shadow.offset2.y' プロパティを表します |
| [getShadowOriginX()](#getShadowOriginX--) | 'shadow.origin.x' プロパティを表します |
| [getShadowOriginY()](#getShadowOriginY--) | 'shadow.origin.y' プロパティを表します |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | 'shadow.matrix.xtox' プロパティを表します |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | 'shadow.matrix.xtoy' プロパティを表します |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | 'shadow.matrix.ytox' プロパティを表します |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | 'shadow.matrix.ytoy' プロパティを表します |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | 'shadow.matrix.perspectiveX' プロパティを表します |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | 'shadow.matrix.perspectiveY' プロパティを表します |
| [getSkewOn()](#getSkewOn--) | 'skew.on' プロパティを表します |
| [getSkewOffsetX()](#getSkewOffsetX--) | 'skew.offset.x' プロパティを表します |
| [getSkewOffsetY()](#getSkewOffsetY--) | 'skew.offset.y' プロパティを表します |
| [getSkewOriginX()](#getSkewOriginX--) | 'skew.origin.x' プロパティを表します |
| [getSkewOriginY()](#getSkewOriginY--) | 'skew.origin.y' プロパティを表します |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | 'skew.matrix.xtox' プロパティを表します |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | 'skew.matrix.xtoy' プロパティを表します |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | 'skew.matrix.ytox' プロパティを表します |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | 'skew.matrix.ytoy' プロパティを表します |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | 'skew.matrix.perspectiveX' プロパティを表します |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | 'skew.matrix.perspectiveY' プロパティを表します |
| [getExtrusionOn()](#getExtrusionOn--) | 'extrusion.on' プロパティを表します |
| [getExtrusionType()](#getExtrusionType--) | 'extrusion.type' プロパティを表します |
| [getExtrusionRender()](#getExtrusionRender--) | 'extrusion.render' プロパティを表します |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | 'extrusion.viewpointorigin.x' プロパティを表します |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | 'extrusion.viewpointorigin.y' プロパティを表します |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | 'extrusion.viewpoint.x' プロパティを表します |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | 'extrusion.viewpoint.y' プロパティを表します |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | 'extrusion.viewpoint.z' プロパティを表します |
| [getExtrusionPlane()](#getExtrusionPlane--) | 'extrusion.plane' プロパティを表します |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | 'extrusion.skewangle' プロパティを表します |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | 'extrusion.skewamt' プロパティを表します |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | 'extrusion.backdepth' プロパティを表します |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | 'extrusion.foredepth' プロパティを表します |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | 'extrusion.orientation.x' プロパティを表します |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | 'extrusion.orientation.y' プロパティを表します |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | 'extrusion.orientation.z' プロパティを表します |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | 'extrusion.orientationangle' プロパティを表します |
| [getExtrusionColor()](#getExtrusionColor--) | 'extrusion.color' プロパティを表します |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | 'extrusion.rotationangle.x' プロパティを表します |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | 'extrusion.rotationangle.y' プロパティを表します |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | 'extrusion.lockrotationcenter' プロパティを表します |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | 'extrusion.autorotationcenter' プロパティを表します |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | 'extrusion.rotationcenter.x' プロパティを表します |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | 'extrusion.rotationcenter.y' プロパティを表します |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | 'extrusion.rotationcenter.z' プロパティを表します |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | 'extrusion.colormode' プロパティを表します |
| [equals(Object obj)](#equals-java.lang.Object-) | このオブジェクトが別のオブジェクトと等しいかどうかを確認します。 |
| [hashCode()](#hashCode--) | (\#getValue.getValue) プロパティに基づいてハッシュコードを計算し返します |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | 既存のビヘイビアプロパティを値で検索するか、指定された値で新しいカスタムプロパティを作成します |

### getValue() {#getValue--}
```
public final String getValue()
```

プロパティの値

**戻り値:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

このプロパティが仕様の事前定義されたプロパティリストに属さないかどうかを示します: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**戻り値:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

'ppt_x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

'ppt_y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

'ppt_w' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

'ppt_h' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

'ppt_c' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

'ppt_r' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

'xshear' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

'yshear' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

'image' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

'ScaleX' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

'ScaleY' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

'r' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

'fillcolor' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

'style.opacity' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

'style.rotation' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

'style.visibility' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

'style.color' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

'style.fontSize' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

'style.fontWeight' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

'style.fontStyle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

'style.fontFamily' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

'style.textEffectEmboss' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

'style.textShadow' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

'style.textTransform' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

'style.textDecorationUnderline' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

'style.textEffectOutline' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

'style.textDecorationLineThrough' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

'style.sRotation' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

'imageData.cropTop' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

'imageData.cropBottom' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

'imageData.cropLeft' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

'imageData.cropRight' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

'imageData.gain' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

'imageData.blacklevel' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

'imageData.gamma' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

'imageData.grayscale' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

'imageData.chromakey' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

'fill.on' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

'fill.type' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

'fill.color' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

'fill.opacity' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

'fill.color2' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

'fill.method' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

'fill.opacity2' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

'fill.angle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

'fill.focus' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

'fill.focusposition.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

'fill.focusposition.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

'fill.focussize.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

'fill.focussize.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

'stroke.on' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

'stroke.color' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

'stroke.weight' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

'stroke.opacity' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

'stroke.linestyle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

'stroke.dashstyle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

'stroke.filltype' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

'stroke.src' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

'stroke.color2' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

'stroke.imagesize.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

'stroke.imagesize.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

'stroke.startArrow' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

'stroke.endArrow' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

'stroke.startArrowWidth' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

'stroke.startArrowLength' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

'stroke.endArrowWidth' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

'stroke.endArrowLength' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

'shadow.on' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

'shadow.type' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

'shadow.color' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

'shadow.color2' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

'shadow.opacity' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

'shadow.offset.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

'shadow.offset.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

'shadow.offset2.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

'shadow.offset2.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

'shadow.origin.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

'shadow.origin.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

'shadow.matrix.xtox' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

'shadow.matrix.xtoy' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

'shadow.matrix.ytox' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

'shadow.matrix.ytoy' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

'shadow.matrix.perspectiveX' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

'shadow.matrix.perspectiveY' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

'skew.on' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

'skew.offset.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

'skew.offset.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

'skew.origin.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

'skew.origin.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

'skew.matrix.xtox' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

'skew.matrix.xtoy' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

'skew.matrix.ytox' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

'skew.matrix.ytoy' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

'skew.matrix.perspectiveX' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

'skew.matrix.perspectiveY' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

'extrusion.on' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

'extrusion.type' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

'extrusion.render' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

'extrusion.viewpointorigin.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

'extrusion.viewpointorigin.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

'extrusion.viewpoint.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

'extrusion.viewpoint.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

'extrusion.viewpoint.z' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

'extrusion.plane' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

'extrusion.skewangle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

'extrusion.skewamt' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

'extrusion.backdepth' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

'extrusion.foredepth' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

'extrusion.orientation.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

'extrusion.orientation.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

'extrusion.orientation.z' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

'extrusion.orientationangle' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

'extrusion.color' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

'extrusion.rotationangle.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

'extrusion.rotationangle.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

'extrusion.lockrotationcenter' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

'extrusion.autorotationcenter' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

'extrusion.rotationcenter.x' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

'extrusion.rotationcenter.y' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

'extrusion.rotationcenter.z' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

'extrusion.colormode' プロパティを表します

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

このオブジェクトが別のオブジェクトと等しいかどうかを確認します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象のオブジェクト。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true

### hashCode() {#hashCode--}
```
public int hashCode()
```

(\#getValue.getValue) プロパティに基づいてハッシュコードを計算し返します

**戻り値:**
int - このオブジェクトのハッシュコードを返します

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

値で既存のビヘイビアプロパティを検索するか、指定された値で新しいカスタムプロパティを作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| propertyValue | java.lang.String | プロパティの値 |

**戻り値:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty のインスタンス