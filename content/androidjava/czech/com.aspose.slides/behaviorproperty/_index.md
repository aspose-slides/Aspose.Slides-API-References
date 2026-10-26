---
title: BehaviorProperty
second_title: Aspose.Slides pro Android pomocí referenčního dokumentu Java API
description: Reprezentuje typy vlastností pro animační chování.
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

Reprezentuje typy vlastností pro animační chování. Řídí se seznamem vlastností z https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx a https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metody

| Metoda | Popis |
| --- | --- |
| [getValue()](#getValue--) | Hodnota vlastnosti |
| [isCustom()](#isCustom--) | Ukazuje, zda tato vlastnost nepatří do předdefinovaného seznamu vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Představuje 'ppt_x' vlastnost |
| [getPptY()](#getPptY--) | Představuje 'ppt_y' vlastnost |
| [getPptW()](#getPptW--) | Představuje 'ppt_w' vlastnost |
| [getPptH()](#getPptH--) | Představuje 'ppt_h' vlastnost |
| [getPptC()](#getPptC--) | Představuje 'ppt_c' vlastnost |
| [getPptR()](#getPptR--) | Představuje 'ppt_r' vlastnost |
| [getXShear()](#getXShear--) | Představuje 'xshear' vlastnost |
| [getYShear()](#getYShear--) | Představuje 'yshear' vlastnost |
| [getImage()](#getImage--) | Představuje 'image' vlastnost |
| [getScaleX()](#getScaleX--) | Představuje 'ScaleX' vlastnost |
| [getScaleY()](#getScaleY--) | Představuje 'ScaleY' vlastnost |
| [getR()](#getR--) | Představuje 'r' vlastnost |
| [getFillColor()](#getFillColor--) | Představuje 'fillcolor' vlastnost |
| [getStyleOpacity()](#getStyleOpacity--) | Představuje 'style.opacity' vlastnost |
| [getStyleRotation()](#getStyleRotation--) | Představuje 'style.rotation' vlastnost |
| [getStyleVisibility()](#getStyleVisibility--) | Představuje 'style.visibility' vlastnost |
| [getStyleColor()](#getStyleColor--) | Představuje 'style.color' vlastnost |
| [getStyleFontSize()](#getStyleFontSize--) | Představuje 'style.fontSize' vlastnost |
| [getStyleFontWeight()](#getStyleFontWeight--) | Představuje 'style.fontWeight' vlastnost |
| [getStyleFontStyle()](#getStyleFontStyle--) | Představuje 'style.fontStyle' vlastnost |
| [getStyleFontFamily()](#getStyleFontFamily--) | Představuje 'style.fontFamily' vlastnost |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Představuje 'style.textEffectEmboss' vlastnost |
| [getStyleTextShadow()](#getStyleTextShadow--) | Představuje 'style.textShadow' vlastnost |
| [getStyleTextTransform()](#getStyleTextTransform--) | Představuje 'style.textTransform' vlastnost |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Představuje 'style.textDecorationUnderline' vlastnost |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Představuje 'style.textEffectOutline' vlastnost |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Představuje 'style.textDecorationLineThrough' vlastnost |
| [getStyleSRotation()](#getStyleSRotation--) | Představuje 'style.sRotation' vlastnost |
| [getImageDataCropTop()](#getImageDataCropTop--) | Představuje 'imageData.cropTop' vlastnost |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Představuje 'imageData.cropBottom' vlastnost |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Představuje 'imageData.cropLeft' vlastnost |
| [getImageDataCropRight()](#getImageDataCropRight--) | Představuje 'imageData.cropRight' vlastnost |
| [getImageDataGain()](#getImageDataGain--) | Představuje 'imageData.gain' vlastnost |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Představuje 'imageData.blacklevel' vlastnost |
| [getImageDataGamma()](#getImageDataGamma--) | Představuje 'imageData.gamma' vlastnost |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Představuje 'imageData.grayscale' vlastnost |
| [getImageDataChromakey()](#getImageDataChromakey--) | Představuje 'imageData.chromakey' vlastnost |
| [getFillOn()](#getFillOn--) | Představuje 'fill.on' vlastnost |
| [getFillType()](#getFillType--) | Představuje 'fill.type' vlastnost |
| [getFill_Color()](#getFill-Color--) | Představuje 'fill.color' vlastnost |
| [getFillOpacity()](#getFillOpacity--) | Představuje 'fill.opacity' vlastnost |
| [getFillColor2()](#getFillColor2--) | Představuje 'fill.color2' vlastnost |
| [getFillMethod()](#getFillMethod--) | Představuje 'fill.method' vlastnost |
| [getFillOpacity2()](#getFillOpacity2--) | Představuje 'fill.opacity2' vlastnost |
| [getFillAngle()](#getFillAngle--) | Představuje 'fill.angle' vlastnost |
| [getFillFocus()](#getFillFocus--) | Představuje 'fill.focus' vlastnost |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Představuje 'fill.focusposition.x' vlastnost |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Představuje 'fill.focusposition.y' vlastnost |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Představuje 'fill.focussize.x' vlastnost |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Představuje 'fill.focussize.y' vlastnost |
| [getStrokeOn()](#getStrokeOn--) | Představuje 'stroke.on' vlastnost |
| [getStrokeColor()](#getStrokeColor--) | Představuje 'stroke.color' vlastnost |
| [getStrokeWeight()](#getStrokeWeight--) | Představuje 'stroke.weight' vlastnost |
| [getStrokeOpacity()](#getStrokeOpacity--) | Představuje 'stroke.opacity' vlastnost |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Představuje 'stroke.linestyle' vlastnost |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Představuje 'stroke.dashstyle' vlastnost |
| [getStrokeFillType()](#getStrokeFillType--) | Představuje 'stroke.filltype' vlastnost |
| [getStrokeSrc()](#getStrokeSrc--) | Představuje 'stroke.src' vlastnost |
| [getStrokeColor2()](#getStrokeColor2--) | Představuje 'stroke.color2' vlastnost |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Představuje 'stroke.imagesize.x' vlastnost |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Představuje 'stroke.imagesize.y' vlastnost |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Představuje 'stroke.startArrow' vlastnost |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Představuje 'stroke.endArrow' vlastnost |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Představuje 'stroke.startArrowWidth' vlastnost |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Představuje 'stroke.startArrowLength' vlastnost |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Představuje 'stroke.endArrowWidth' vlastnost |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Představuje 'stroke.endArrowLength' vlastnost |
| [getShadowOn()](#getShadowOn--) | Představuje 'shadow.on' vlastnost |
| [getShadowType()](#getShadowType--) | Představuje 'shadow.type' vlastnost |
| [getShadowColor()](#getShadowColor--) | Představuje 'shadow.color' vlastnost |
| [getShadowColor2()](#getShadowColor2--) | Představuje 'shadow.color2' vlastnost |
| [getShadowOpacity()](#getShadowOpacity--) | Představuje 'shadow.opacity' vlastnost |
| [getShadowOffsetX()](#getShadowOffsetX--) | Představuje 'shadow.offset.x' vlastnost |
| [getShadowOffsetY()](#getShadowOffsetY--) | Představuje 'shadow.offset.y' vlastnost |
| [getShadowOffset2X()](#getShadowOffset2X--) | Představuje 'shadow.offset2.x' vlastnost |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Představuje 'shadow.offset2.y' vlastnost |
| [getShadowOriginX()](#getShadowOriginX--) | Představuje 'shadow.origin.x' vlastnost |
| [getShadowOriginY()](#getShadowOriginY--) | Představuje 'shadow.origin.y' vlastnost |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Představuje 'shadow.matrix.xtox' vlastnost |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Představuje 'shadow.matrix.xtoy' vlastnost |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Představuje 'shadow.matrix.ytox' vlastnost |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Představuje 'shadow.matrix.ytoy' vlastnost |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Představuje 'shadow.matrix.perspectiveX' vlastnost |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Představuje 'shadow.matrix.perspectiveY' vlastnost |
| [getSkewOn()](#getSkewOn--) | Představuje 'skew.on' vlastnost |
| [getSkewOffsetX()](#getSkewOffsetX--) | Představuje 'skew.offset.x' vlastnost |
| [getSkewOffsetY()](#getSkewOffsetY--) | Představuje 'skew.offset.y' vlastnost |
| [getSkewOriginX()](#getSkewOriginX--) | Představuje 'skew.origin.x' vlastnost |
| [getSkewOriginY()](#getSkewOriginY--) | Představuje 'skew.origin.y' vlastnost |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Představuje 'skew.matrix.xtox' vlastnost |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Představuje 'skew.matrix.xtoy' vlastnost |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Představuje 'skew.matrix.ytox' vlastnost |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Představuje 'skew.matrix.ytoy' vlastnost |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Představuje 'skew.matrix.perspectiveX' vlastnost |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Představuje 'skew.matrix.perspectiveY' vlastnost |
| [getExtrusionOn()](#getExtrusionOn--) | Představuje 'extrusion.on' vlastnost |
| [getExtrusionType()](#getExtrusionType--) | Představuje 'extrusion.type' vlastnost |
| [getExtrusionRender()](#getExtrusionRender--) | Představuje 'extrusion.render' vlastnost |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Představuje 'extrusion.viewpointorigin.x' vlastnost |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Představuje 'extrusion.viewpointorigin.y' vlastnost |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Představuje 'extrusion.viewpoint.x' vlastnost |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Představuje 'extrusion.viewpoint.y' vlastnost |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Představuje 'extrusion.viewpoint.z' vlastnost |
| [getExtrusionPlane()](#getExtrusionPlane--) | Představuje 'extrusion.plane' vlastnost |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Představuje 'extrusion.skewangle' vlastnost |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Představuje 'extrusion.skewamt' vlastnost |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Představuje 'extrusion.backdepth' vlastnost |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Představuje 'extrusion.foredepth' vlastnost |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Představuje 'extrusion.orientation.x' vlastnost |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Představuje 'extrusion.orientation.y' vlastnost |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Představuje 'extrusion.orientation.z' vlastnost |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Představuje 'extrusion.orientationangle' vlastnost |
| [getExtrusionColor()](#getExtrusionColor--) | Představuje 'extrusion.color' vlastnost |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Představuje 'extrusion.rotationangle.x' vlastnost |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Představuje 'extrusion.rotationangle.y' vlastnost |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Představuje 'extrusion.lockrotationcenter' vlastnost |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Představuje 'extrusion.autorotationcenter' vlastnost |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Představuje 'extrusion.rotationcenter.x' vlastnost |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Představuje 'extrusion.rotationcenter.y' vlastnost |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Představuje 'extrusion.rotationcenter.z' vlastnost |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Představuje 'extrusion.colormode' vlastnost |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontroluje, zda je tento objekt roven jinému. |
| [hashCode()](#hashCode--) | Vypočítá a vrátí hash kód na základě vlastnosti (#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Hledá existující vlastnost chování podle hodnoty nebo vytvoří novou vlastní s určenou hodnotou |

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

Ukazuje, zda tato vlastnost nepatří do předdefinovaného seznamu vlastností ve specifikaci: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Vrací:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Představuje 'ppt_x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Představuje 'ppt_y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Představuje 'ppt_w' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Představuje 'ppt_h' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Představuje 'ppt_c' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Představuje 'ppt_r' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Představuje 'xshear' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Představuje 'yshear' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Představuje 'image' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Představuje 'ScaleX' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Představuje 'ScaleY' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Představuje 'r' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Představuje 'fillcolor' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Představuje 'style.opacity' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Představuje 'style.rotation' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Představuje 'style.visibility' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Představuje 'style.color' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Představuje 'style.fontSize' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Představuje 'style.fontWeight' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Představuje 'style.fontStyle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Představuje 'style.fontFamily' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Představuje 'style.textEffectEmboss' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Představuje 'style.textShadow' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Představuje 'style.textTransform' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Představuje 'style.textDecorationUnderline' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Představuje 'style.textEffectOutline' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Představuje 'style.textDecorationLineThrough' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Představuje 'style.sRotation' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Představuje 'imageData.cropTop' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Představuje 'imageData.cropBottom' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Představuje 'imageData.cropLeft' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Představuje 'imageData.cropRight' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Představuje 'imageData.gain' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Představuje 'imageData.blacklevel' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Představuje 'imageData.gamma' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Představuje 'imageData.grayscale' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Představuje 'imageData.chromakey' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Představuje 'fill.on' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Představuje 'fill.type' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Představuje 'fill.color' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Představuje 'fill.opacity' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Představuje 'fill.color2' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Představuje 'fill.method' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Představuje 'fill.opacity2' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Představuje 'fill.angle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Představuje 'fill.focus' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Představuje 'fill.focusposition.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Představuje 'fill.focusposition.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Představuje 'fill.focussize.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Představuje 'fill.focussize.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Představuje 'stroke.on' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Představuje 'stroke.color' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Představuje 'stroke.weight' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Představuje 'stroke.opacity' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Představuje 'stroke.linestyle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Představuje 'stroke.dashstyle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Představuje 'stroke.filltype' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Představuje 'stroke.src' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Představuje 'stroke.color2' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Představuje 'stroke.imagesize.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Představuje 'stroke.imagesize.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Představuje 'stroke.startArrow' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Představuje 'stroke.endArrow' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Představuje 'stroke.startArrowWidth' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Představuje 'stroke.startArrowLength' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Představuje 'stroke.endArrowWidth' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Představuje 'stroke.endArrowLength' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Představuje 'shadow.on' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Představuje 'shadow.type' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Představuje 'shadow.color' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Představuje 'shadow.color2' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Představuje 'shadow.opacity' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Představuje 'shadow.offset.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Představuje 'shadow.offset.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Představuje 'shadow.offset2.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Představuje 'shadow.offset2.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Představuje 'shadow.origin.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
**



```

Představuje 'shadow.origin.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Představuje 'shadow.matrix.xtox' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Představuje 'shadow.matrix.xtoy' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Představuje 'shadow.matrix.ytox' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Představuje 'shadow.matrix.ytoy' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Představuje 'shadow.matrix.perspectiveX' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Představuje 'shadow.matrix.perspectiveY' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Představuje 'skew.on' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Představuje 'skew.offset.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Představuje 'skew.offset.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Představuje 'skew.origin.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Představuje 'skew.origin.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Představuje 'skew.matrix.xtox' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Představuje 'skew.matrix.xtoy' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Představuje 'skew.matrix.ytox' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Představuje 'skew.matrix.ytoy' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Představuje 'skew.matrix.perspectiveX' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Představuje 'skew.matrix.perspectiveY' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Představuje 'extrusion.on' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Představuje 'extrusion.type' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Představuje 'extrusion.render' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Představuje 'extrusion.viewpointorigin.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Představuje 'extrusion.viewpointorigin.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public 

```

Představuje 'extrusion.viewpoint.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Představuje 'extrusion.viewpoint.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Představuje 'extrusion.viewpoint.z' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Představuje 'extrusion.plane' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Představuje 'extrusion.skewangle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Představuje 'extrusion.skewamt' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Představuje 'extrusion.backdepth' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Představuje 'extrusion.foredepth' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Představuje 'extrusion.orientation.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Představuje 'extrusion.orientation.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Představuje 'extrusion.orientation.z' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Představuje 'extrusion.orientationangle' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Představuje 'extrusion.color' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Představuje 'extrusion.rotationangle.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Představuje 'extrusion.rotationangle.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Představuje 'extrusion.lockrotationcenter' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Představuje 'extrusion.autorotationcenter' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Představuje 'extrusion.rotationcenter.x' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Představuje 'extrusion.rotationcenter.y' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Představuje 'extrusion.rotationcenter.z' vlastnost

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Představuje 'extrusion.colormode' vlastnost

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
| obj | java.lang.Object | Objekt k porovnání. |

**Vrací:**
boolean - True, pokud jsou objekty stejné.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Vypočítá a vrátí hash kód na základě vlastnosti (#getValue.getValue)

**Vrací:**
int - Vrací hash kód pro tento objekt

### getOrCreateByValue(java.lang.String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Hledá existující vlastnost chování podle hodnoty nebo vytvoří novou vlastní s určenou hodnotou

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | hodnota vlastnosti |

**Vrací:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance třídy BehaviorProperty