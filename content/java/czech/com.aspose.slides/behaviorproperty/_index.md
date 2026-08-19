---
title: BehaviorProperty
second_title: Aspose.Slides pro Java API Reference
description: Představuje typy vlastností pro chování animace.
type: docs
url: /cs/com.aspose.slides/behaviorproperty/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Reprezentuje typy vlastností pro chování animace. Vychází ze seznamu vlastností na https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx a https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Hodnota vlastnosti |
| [isCustom()](#isCustom--) | Zobrazuje, zda tato vlastnost nepatří do předdefinovaného seznamu vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Zastupuje vlastnost 'ppt\_x' |
| [getPptY()](#getPptY--) | Zastupuje vlastnost 'ppt\_y' |
| [getPptW()](#getPptW--) | Zastupuje vlastnost 'ppt\_w' |
| [getPptH()](#getPptH--) | Zastupuje vlastnost 'ppt\_h' |
| [getPptC()](#getPptC--) | Zastupuje vlastnost 'ppt\_c' |
| [getPptR()](#getPptR--) | Zastupuje vlastnost 'ppt\_r' |
| [getXShear()](#getXShear--) | Zastupuje vlastnost 'xshear' |
| [getYShear()](#getYShear--) | Zastupuje vlastnost 'yshear' |
| [getImage()](#getImage--) | Zastupuje vlastnost 'image' |
| [getScaleX()](#getScaleX--) | Zastupuje vlastnost 'ScaleX' |
| [getScaleY()](#getScaleY--) | Zastupuje vlastnost 'ScaleY' |
| [getR()](#getR--) | Zastupuje vlastnost 'r' |
| [getFillColor()](#getFillColor--) | Zastupuje vlastnost 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Zastupuje vlastnost 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Zastupuje vlastnost 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Zastupuje vlastnost 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Zastupuje vlastnost 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Zastupuje vlastnost 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Zastupuje vlastnost 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Zastupuje vlastnost 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Zastupuje vlastnost 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Zastupuje vlastnost 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Zastupuje vlastnost 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Zastupuje vlastnost 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Zastupuje vlastnost 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Zastupuje vlastnost 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Zastupuje vlastnost 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Zastupuje vlastnost 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Zastupuje vlastnost 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Zastupuje vlastnost 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Zastupuje vlastnost 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Zastupuje vlastnost 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Zastupuje vlastnost 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Zastupuje vlastnost 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Zastupuje vlastnost 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Zastupuje vlastnost 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Zastupuje vlastnost 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Zastupuje vlastnost 'fill.on' |
| [getFillType()](#getFillType--) | Zastupuje vlastnost 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Zastupuje vlastnost 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Zastupuje vlastnost 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Zastupuje vlastnost 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Zastupuje vlastnost 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Zastupuje vlastnost 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Zastupuje vlastnost 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Zastupuje vlastnost 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Zastupuje vlastnost 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Zastupuje vlastnost 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Zastupuje vlastnost 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Zastupuje vlastnost 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Zastupuje vlastnost 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Zastupuje vlastnost 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Zastupuje vlastnost 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Zastupuje vlastnost 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Zastupuje vlastnost 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Zastupuje vlastnost 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Zastupuje vlastnost 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Zastupuje vlastnost 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Zastupuje vlastnost 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Zastupuje vlastnost 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Zastupuje vlastnost 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Zastupuje vlastnost 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Zastupuje vlastnost 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Zastupuje vlastnost 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Zastupuje vlastnost 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Zastupuje vlastnost 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Zastupuje vlastnost 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Zastupuje vlastnost 'shadow.on' |
| [getShadowType()](#getShadowType--) | Zastupuje vlastnost 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Zastupuje vlastnost 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Zastupuje vlastnost 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Zastupuje vlastnost 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Zastupuje vlastnost 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Zastupuje vlastnost 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Zastupuje vlastnost 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Zastupuje vlastnost 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Zastupuje vlastnost 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Zastupuje vlastnost 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Zastupuje vlastnost 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Zastupuje vlastnost 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Zastupuje vlastnost 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Zastupuje vlastnost 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Zastupuje vlastnost 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Zastupuje vlastnost 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Zastupuje vlastnost 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Zastupuje vlastnost 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Zastupuje vlastnost 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Zastupuje vlastnost 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Zastupuje vlastnost 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Zastupuje vlastnost 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Zastupuje vlastnost 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Zastupuje vlastnost 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Zastupuje vlastnost 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Zastupuje vlastnost 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Zastupuje vlastnost 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Zastupuje vlastnost 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Zastupuje vlastnost 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Zastupuje vlastnost 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Zastupuje vlastnost 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Zastupuje vlastnost 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Zastupuje vlastnost 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Zastupuje vlastnost 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Zastupuje vlastnost 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Zastupuje vlastnost 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Zastupuje vlastnost 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Zastupuje vlastnost 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Zastupuje vlastnost 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Zastupuje vlastnost 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Zastupuje vlastnost 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Zastupuje vlastnost 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Zastupuje vlastnost 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Zastupuje vlastnost 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Zastupuje vlastnost 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Zastupuje vlastnost 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Zastupuje vlastnost 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Zastupuje vlastnost 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Zastupuje vlastnost 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Zastupuje vlastnost 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Zastupuje vlastnost 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Zastupuje vlastnost 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Zastupuje vlastnost 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontroluje, zda je tento objekt roven jinému. |
| [hashCode()](#hashCode--) | Vypočítá a vrátí hash kód na základě vlastnosti (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Vyhledá existující vlastnost chování podle hodnoty nebo vytvoří novou vlastní s danou hodnotou |

### getValue() {#getValue--}
```
public final String getValue()
```

Hodnota vlastnosti

**Vrací:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Zobrazuje, zda tato vlastnost nepatří do předdefinovaného seznamu vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Vrací:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Zastupuje vlastnost 'ppt\_x'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Zastupuje vlastnost 'ppt\_y'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Zastupuje vlastnost 'ppt\_w'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Zastupuje vlastnost 'ppt\_h'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Zastupuje vlastnost 'ppt\_c'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Zastupuje vlastnost 'ppt\_r'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Zastupuje vlastnost 'xshear'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Zastupuje vlastnost 'yshear'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Zastupuje vlastnost 'image'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Zastupuje vlastnost 'ScaleX'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Zastupuje vlastnost 'ScaleY'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Zastupuje vlastnost 'r'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Zastupuje vlastnost 'fillcolor'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Zastupuje vlastnost 'style.opacity'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Zastupuje vlastnost 'style.rotation'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Zastupuje vlastnost 'style.visibility'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Zastupuje vlastnost 'style.color'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Zastupuje vlastnost 'style.fontSize'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Zastupuje vlastnost 'style.fontWeight'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Zastupuje vlastnost 'style.fontStyle'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Zastupuje vlastnost 'style.fontFamily'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Zastupuje vlastnost 'style.textEffectEmboss'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Zastupuje vlastnost 'style.textShadow'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Zastupuje vlastnost 'style.textTransform'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Zastupuje vlastnost 'style.textDecorationUnderline'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Zastupuje vlastnost 'style.textEffectOutline'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Zastupuje vlastnost 'style.textDecorationLineThrough'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Zastupuje vlastnost 'style.sRotation'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Zastupuje vlastnost 'imageData.cropTop'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Zastupuje vlastnost 'imageData.cropBottom'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Zastupuje vlastnost 'imageData.cropLeft'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Zastupuje vlastnost 'imageData.cropRight'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Zastupuje vlastnost 'imageData.gain'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Zastupuje vlastnost 'imageData.blacklevel'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Zastupuje vlastnost 'imageData.gamma'

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Representuje vlastnost **'imageData.grayscale'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Representuje vlastnost **'imageData.chromakey'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Representuje vlastnost **'fill.on'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Representuje vlastnost **'fill.type'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Representuje vlastnost **'fill.color'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Representuje vlastnost **'fill.opacity'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Representuje vlastnost **'fill.color2'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Representuje vlastnost **'fill.method'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Representuje vlastnost **'fill.opacity2'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Representuje vlastnost **'fill.angle'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Representuje vlastnost **'fill.focus'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Representuje vlastnost **'fill.focusposition.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Representuje vlastnost **'fill.focusposition.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Representuje vlastnost **'fill.focussize.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Representuje vlastnost **'fill.focussize.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Representuje vlastnost **'stroke.on'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Representuje vlastnost **'stroke.color'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Representuje vlastnost **'stroke.weight'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Representuje vlastnost **'stroke.opacity'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Representuje vlastnost **'stroke.linestyle'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Representuje vlastnost **'stroke.dashstyle'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Representuje vlastnost **'stroke.filltype'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Representuje vlastnost **'stroke.src'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Representuje vlastnost **'stroke.color2'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Representuje vlastnost **'stroke.imagesize.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Representuje vlastnost **'stroke.imagesize.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Representuje vlastnost **'stroke.startArrow'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Representuje vlastnost **'stroke.endArrow'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Representuje vlastnost **'stroke.startArrowWidth'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Representuje vlastnost **'stroke.startArrowLength'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Representuje vlastnost **'stroke.endArrowWidth'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Representuje vlastnost **'stroke.endArrowLength'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Representuje vlastnost **'shadow.on'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Representuje vlastnost **'shadow.type'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Representuje vlastnost **'shadow.color'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Representuje vlastnost **'shadow.color2'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Representuje vlastnost **'shadow.opacity'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Representuje vlastnost **'shadow.offset.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Representuje vlastnost **'shadow.offset.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Representuje vlastnost **'shadow.offset2.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Representuje vlastnost **'shadow.offset2.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Representuje vlastnost **'shadow.origin.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Representuje vlastnost **'shadow.origin.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Representuje vlastnost **'shadow.matrix.xtox'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Representuje vlastnost **'shadow.matrix.xtoy'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Representuje vlastnost **'shadow.matrix.ytox'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Representuje vlastnost **'shadow.matrix.ytoy'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Representuje vlastnost **'shadow.matrix.perspectiveX'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Representuje vlastnost **'shadow.matrix.perspectiveY'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Representuje vlastnost **'skew.on'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Representuje vlastnost **'skew.offset.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Representuje vlastnost **'skew.offset.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Representuje vlastnost **'skew.origin.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Representuje vlastnost **'skew.origin.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Representuje vlastnost **'skew.matrix.xtox'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Representuje vlastnost **'skew.matrix.xtoy'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Representuje vlastnost **'skew.matrix.ytox'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Representuje vlastnost **'skew.matrix.ytoy'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Representuje vlastnost **'skew.matrix.perspectiveX'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Representuje vlastnost **'skew.matrix.perspectiveY'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Representuje vlastnost **'extrusion.on'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Representuje vlastnost **'extrusion.type'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Representuje vlastnost **'extrusion.render'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Representuje vlastnost **'extrusion.viewpointorigin.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Representuje vlastnost **'extrusion.viewpointorigin.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Representuje vlastnost **'extrusion.viewpoint.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Representuje vlastnost **'extrusion.viewpoint.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Representuje vlastnost **'extrusion.viewpoint.z'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Representuje vlastnost **'extrusion.plane'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Representuje vlastnost **'extrusion.skewangle'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Representuje vlastnost **'extrusion.skewamt'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Representuje vlastnost **'extrusion.backdepth'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Representuje vlastnost **'extrusion.foredepth'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Representuje vlastnost **'extrusion.orientation.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Representuje vlastnost **'extrusion.orientation.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Representuje vlastnost **'extrusion.orientation.z'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Representuje vlastnost **'extrusion.orientationangle'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Representuje vlastnost **'extrusion.color'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Representuje vlastnost **'extrusion.rotationangle.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Representuje vlastnost **'extrusion.rotationangle.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Representuje vlastnost **'extrusion.lockrotationcenter'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Representuje vlastnost **'extrusion.autorotationcenter'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Representuje vlastnost **'extrusion.rotationcenter.x'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Representuje vlastnost **'extrusion.rotationcenter.y'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Representuje vlastnost **'extrusion.rotationcenter.z'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Representuje vlastnost **'extrusion.colormode'**

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kontroluje, zda je tento objekt roven jinému.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt, který se má porovnat. |

**Vrací:**
boolean - True pokud jsou objekty stejné.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Vypočítá a vrátí hash kód na základě vlastnosti (\#getValue.getValue)

**Vrací:**
int - Vrací hash kód pro tento objekt

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Vyhledá existující vlastnost chování podle hodnoty nebo vytvoří novou vlastní s určenou hodnotou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | hodnota vlastnosti |

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance třídy BehaviorProperty