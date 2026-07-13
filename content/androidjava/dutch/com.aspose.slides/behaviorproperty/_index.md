---
title: BehaviorProperty
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt eigenschapstypen voor animatiegedrag.
type: docs
url: /nl/com.aspose.slides/behaviorproperty/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Vertegenwoordigt eigenschapstypen voor animatiegedrag. Volgt de lijst met eigenschappen van https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx en https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getValue()](#getValue--) | Waarde van de eigenschap |
| [isCustom()](#isCustom--) | Toont of deze eigenschap niet tot de vooraf gedefinieerde eigenschapslijst in de specificatie behoort: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Stelt de eigenschap 'ppt\_x' voor |
| [getPptY()](#getPptY--) | Stelt de eigenschap 'ppt\_y' voor |
| [getPptW()](#getPptW--) | Stelt de eigenschap 'ppt\_w' voor |
| [getPptH()](#getPptH--) | Stelt de eigenschap 'ppt\_h' voor |
| [getPptC()](#getPptC--) | Stelt de eigenschap 'ppt\_c' voor |
| [getPptR()](#getPptR--) | Stelt de eigenschap 'ppt\_r' voor |
| [getXShear()](#getXShear--) | Stelt de eigenschap 'xshear' voor |
| [getYShear()](#getYShear--) | Stelt de eigenschap 'yshear' voor |
| [getImage()](#getImage--) | Stelt de eigenschap 'image' voor |
| [getScaleX()](#getScaleX--) | Stelt de eigenschap 'ScaleX' voor |
| [getScaleY()](#getScaleY--) | Stelt de eigenschap 'ScaleY' voor |
| [getR()](#getR--) | Stelt de eigenschap 'r' voor |
| [getFillColor()](#getFillColor--) | Stelt de eigenschap 'fillcolor' voor |
| [getStyleOpacity()](#getStyleOpacity--) | Stelt de eigenschap 'style.opacity' voor |
| [getStyleRotation()](#getStyleRotation--) | Stelt de eigenschap 'style.rotation' voor |
| [getStyleVisibility()](#getStyleVisibility--) | Stelt de eigenschap 'style.visibility' voor |
| [getStyleColor()](#getStyleColor--) | Stelt de eigenschap 'style.color' voor |
| [getStyleFontSize()](#getStyleFontSize--) | Stelt de eigenschap 'style.fontSize' voor |
| [getStyleFontWeight()](#getStyleFontWeight--) | Stelt de eigenschap 'style.fontWeight' voor |
| [getStyleFontStyle()](#getStyleFontStyle--) | Stelt de eigenschap 'style.fontStyle' voor |
| [getStyleFontFamily()](#getStyleFontFamily--) | Stelt de eigenschap 'style.fontFamily' voor |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Stelt de eigenschap 'style.textEffectEmboss' voor |
| [getStyleTextShadow()](#getStyleTextShadow--) | Stelt de eigenschap 'style.textShadow' voor |
| [getStyleTextTransform()](#getStyleTextTransform--) | Stelt de eigenschap 'style.textTransform' voor |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Stelt de eigenschap 'style.textDecorationUnderline' voor |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Stelt de eigenschap 'style.textEffectOutline' voor |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Stelt de eigenschap 'style.textDecorationLineThrough' voor |
| [getStyleSRotation()](#getStyleSRotation--) | Stelt de eigenschap 'style.sRotation' voor |
| [getImageDataCropTop()](#getImageDataCropTop--) | Stelt de eigenschap 'imageData.cropTop' voor |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Stelt de eigenschap 'imageData.cropBottom' voor |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Stelt de eigenschap 'imageData.cropLeft' voor |
| [getImageDataCropRight()](#getImageDataCropRight--) | Stelt de eigenschap 'imageData.cropRight' voor |
| [getImageDataGain()](#getImageDataGain--) | Stelt de eigenschap 'imageData.gain' voor |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Stelt de eigenschap 'imageData.blacklevel' voor |
| [getImageDataGamma()](#getImageDataGamma--) | Stelt de eigenschap 'imageData.gamma' voor |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Stelt de eigenschap 'imageData.grayscale' voor |
| [getImageDataChromakey()](#getImageDataChromakey--) | Stelt de eigenschap 'imageData.chromakey' voor |
| [getFillOn()](#getFillOn--) | Stelt de eigenschap 'fill.on' voor |
| [getFillType()](#getFillType--) | Stelt de eigenschap 'fill.type' voor |
| [getFill_Color()](#getFill-Color--) | Stelt de eigenschap 'fill.color' voor |
| [getFillOpacity()](#getFillOpacity--) | Stelt de eigenschap 'fill.opacity' voor |
| [getFillColor2()](#getFillColor2--) | Stelt de eigenschap 'fill.color2' voor |
| [getFillMethod()](#getFillMethod--) | Stelt de eigenschap 'fill.method' voor |
| [getFillOpacity2()](#getFillOpacity2--) | Stelt de eigenschap 'fill.opacity2' voor |
| [getFillAngle()](#getFillAngle--) | Stelt de eigenschap 'fill.angle' voor |
| [getFillFocus()](#getFillFocus--) | Stelt de eigenschap 'fill.focus' voor |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Stelt de eigenschap 'fill.focusposition.x' voor |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Stelt de eigenschap 'fill.focusposition.y' voor |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Stelt de eigenschap 'fill.focussize.x' voor |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Stelt de eigenschap 'fill.focussize.y' voor |
| [getStrokeOn()](#getStrokeOn--) | Stelt de eigenschap 'stroke.on' voor |
| [getStrokeColor()](#getStrokeColor--) | Stelt de eigenschap 'stroke.color' voor |
| [getStrokeWeight()](#getStrokeWeight--) | Stelt de eigenschap 'stroke.weight' voor |
| [getStrokeOpacity()](#getStrokeOpacity--) | Stelt de eigenschap 'stroke.opacity' voor |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Stelt de eigenschap 'stroke.linestyle' voor |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Stelt de eigenschap 'stroke.dashstyle' voor |
| [getStrokeFillType()](#getStrokeFillType--) | Stelt de eigenschap 'stroke.filltype' voor |
| [getStrokeSrc()](#getStrokeSrc--) | Stelt de eigenschap 'stroke.src' voor |
| [getStrokeColor2()](#getStrokeColor2--) | Stelt de eigenschap 'stroke.color2' voor |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Stelt de eigenschap 'stroke.imagesize.x' voor |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Stelt de eigenschap 'stroke.imagesize.y' voor |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Stelt de eigenschap 'stroke.startArrow' voor |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Stelt de eigenschap 'stroke.endArrow' voor |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Stelt de eigenschap 'stroke.startArrowWidth' voor |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Stelt de eigenschap 'stroke.startArrowLength' voor |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Stelt de eigenschap 'stroke.endArrowWidth' voor |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Stelt de eigenschap 'stroke.endArrowLength' voor |
| [getShadowOn()](#getShadowOn--) | Stelt de eigenschap 'shadow.on' voor |
| [getShadowType()](#getShadowType--) | Stelt de eigenschap 'shadow.type' voor |
| [getShadowColor()](#getShadowColor--) | Stelt de eigenschap 'shadow.color' voor |
| [getShadowColor2()](#getShadowColor2--) | Stelt de eigenschap 'shadow.color2' voor |
| [getShadowOpacity()](#getShadowOpacity--) | Stelt de eigenschap 'shadow.opacity' voor |
| [getShadowOffsetX()](#getShadowOffsetX--) | Stelt de eigenschap 'shadow.offset.x' voor |
| [getShadowOffsetY()](#getShadowOffsetY--) | Stelt de eigenschap 'shadow.offset.y' voor |
| [getShadowOffset2X()](#getShadowOffset2X--) | Stelt de eigenschap 'shadow.offset2.x' voor |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Stelt de eigenschap 'shadow.offset2.y' voor |
| [getShadowOriginX()](#getShadowOriginX--) | Stelt de eigenschap 'shadow.origin.x' voor |
| [getShadowOriginY()](#getShadowOriginY--) | Stelt de eigenschap 'shadow.origin.y' voor |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Stelt de eigenschap 'shadow.matrix.xtox' voor |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Stelt de eigenschap 'shadow.matrix.xtoy' voor |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Stelt de eigenschap 'shadow.matrix.ytox' voor |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Stelt de eigenschap 'shadow.matrix.ytoy' voor |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Stelt de eigenschap 'shadow.matrix.perspectiveX' voor |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Stelt de eigenschap 'shadow.matrix.perspectiveY' voor |
| [getSkewOn()](#getSkewOn--) | Stelt de eigenschap 'skew.on' voor |
| [getSkewOffsetX()](#getSkewOffsetX--) | Stelt de eigenschap 'skew.offset.x' voor |
| [getSkewOffsetY()](#getSkewOffsetY--) | Stelt de eigenschap 'skew.offset.y' voor |
| [getSkewOriginX()](#getSkewOriginX--) | Stelt de eigenschap 'skew.origin.x' voor |
| [getSkewOriginY()](#getSkewOriginY--) | Stelt de eigenschap 'skew.origin.y' voor |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Stelt de eigenschap 'skew.matrix.xtox' voor |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Stelt de eigenschap 'skew.matrix.xtoy' voor |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Stelt de eigenschap 'skew.matrix.ytox' voor |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Stelt de eigenschap 'skew.matrix.ytoy' voor |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Stelt de eigenschap 'skew.matrix.perspectiveX' voor |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Stelt de eigenschap 'skew.matrix.perspectiveY' voor |
| [getExtrusionOn()](#getExtrusionOn--) | Stelt de eigenschap 'extrusion.on' voor |
| [getExtrusionType()](#getExtrusionType--) | Stelt de eigenschap 'extrusion.type' voor |
| [getExtrusionRender()](#getExtrusionRender--) | Stelt de eigenschap 'extrusion.render' voor |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Stelt de eigenschap 'extrusion.viewpointorigin.x' voor |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Stelt de eigenschap 'extrusion.viewpointorigin.y' voor |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Stelt de eigenschap 'extrusion.viewpoint.x' voor |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Stelt de eigenschap 'extrusion.viewpoint.y' voor |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Stelt de eigenschap 'extrusion.viewpoint.z' voor |
| [getExtrusionPlane()](#getExtrusionPlane--) | Stelt de eigenschap 'extrusion.plane' voor |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Stelt de eigenschap 'extrusion.skewangle' voor |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Stelt de eigenschap 'extrusion.skewamt' voor |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Stelt de eigenschap 'extrusion.backdepth' voor |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Stelt de eigenschap 'extrusion.foredepth' voor |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Stelt de eigenschap 'extrusion.orientation.x' voor |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Stelt de eigenschap 'extrusion.orientation.y' voor |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Stelt de eigenschap 'extrusion.orientation.z' voor |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Stelt de eigenschap 'extrusion.orientationangle' voor |
| [getExtrusionColor()](#getExtrusionColor--) | Stelt de eigenschap 'extrusion.color' voor |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Stelt de eigenschap 'extrusion.rotationangle.x' voor |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Stelt de eigenschap 'extrusion.rotationangle.y' voor |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Stelt de eigenschap 'extrusion.lockrotationcenter' voor |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Stelt de eigenschap 'extrusion.autorotationcenter' voor |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Stelt de eigenschap 'extrusion.rotationcenter.x' voor |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Stelt de eigenschap 'extrusion.rotationcenter.y' voor |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Stelt de eigenschap 'extrusion.rotationcenter.z' voor |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Stelt de eigenschap 'extrusion.colormode' voor |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleert of dit object gelijk is aan een ander. |
| [hashCode()](#hashCode--) | Berekent en retourneert een hashcode op basis van de eigenschap (#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Zoekt naar een bestaande gedragseigenschap op basis van de waarde of maakt een nieuwe aangepaste aan met de opgegeven waarde |

### getValue() {#getValue--}
```
public final String getValue()
```

Waarde van de eigenschap

**Retourwaarde:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Toont of deze eigenschap niet tot de vooraf gedefinieerde eigenschapslijst in de specificatie behoort: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Retourwaarde:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Stelt de eigenschap 'ppt\_x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Stelt de eigenschap 'ppt\_y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Stelt de eigenschap 'ppt\_w' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Stelt de eigenschap 'ppt\_h' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Stelt de eigenschap 'ppt\_c' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Stelt de eigenschap 'ppt\_r' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Stelt de eigenschap 'xshear' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Stelt de eigenschap 'yshear' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Stelt de eigenschap 'image' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Stelt de eigenschap 'ScaleX' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Stelt de eigenschap 'ScaleY' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Stelt de eigenschap 'r' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Stelt de eigenschap 'fillcolor' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Stelt de eigenschap 'style.opacity' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Stelt de eigenschap 'style.rotation' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Stelt de eigenschap 'style.visibility' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Stelt de eigenschap 'style.color' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Stelt de eigenschap 'style.fontSize' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Stelt de eigenschap 'style.fontWeight' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Stelt de eigenschap 'style.fontStyle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Stelt de eigenschap 'style.fontFamily' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Stelt de eigenschap 'style.textEffectEmboss' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Stelt de eigenschap 'style.textShadow' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Stelt de eigenschap 'style.textTransform' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Stelt de eigenschap 'style.textDecorationUnderline' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Stelt de eigenschap 'style.textEffectOutline' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Stelt de eigenschap 'style.textDecorationLineThrough' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Stelt de eigenschap 'style.sRotation' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Stelt de eigenschap 'imageData.cropTop' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Stelt de eigenschap 'imageData.cropBottom' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Stelt de eigenschap 'imageData.cropLeft' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Stelt de eigenschap 'imageData.cropRight' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Stelt de eigenschap 'imageData.gain' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Stelt de eigenschap 'imageData.blacklevel' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Stelt de eigenschap 'imageData.gamma' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Stelt de eigenschap 'imageData.grayscale' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Stelt de eigenschap 'imageData.chromakey' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Stelt de eigenschap 'fill.on' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Stelt de eigenschap 'fill.type' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Stelt de eigenschap 'fill.color' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Stelt de eigenschap 'fill.opacity' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Stelt de eigenschap 'fill.color2' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Stelt de eigenschap 'fill.method' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Stelt de eigenschap 'fill.opacity2' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Stelt de eigenschap 'fill.angle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Stelt de eigenschap 'fill.focus' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Stelt de eigenschap 'fill.focusposition.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Stelt de eigenschap 'fill.focusposition.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Stelt de eigenschap 'fill.focussize.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Stelt de eigenschap 'fill.focussize.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Stelt de eigenschap 'stroke.on' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Stelt de eigenschap 'stroke.color' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Stelt de eigenschap 'stroke.weight' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Stelt de eigenschap 'stroke.opacity' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Stelt de eigenschap 'stroke.linestyle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Stelt de eigenschap 'stroke.dashstyle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Stelt de eigenschap 'stroke.filltype' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Stelt de eigenschap 'stroke.src' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Stelt de eigenschap 'stroke.color2' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Stelt de eigenschap 'stroke.imagesize.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Stelt de eigenschap 'stroke.imagesize.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Stelt de eigenschap 'stroke.startArrow' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Stelt de eigenschap 'stroke.endArrow' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Stelt de eigenschap 'stroke.startArrowWidth' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Stelt de eigenschap 'stroke.startArrowLength' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Stelt de eigenschap 'stroke.endArrowWidth' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Stelt de eigenschap 'stroke.endArrowLength' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Stelt de eigenschap 'shadow.on' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Stelt de eigenschap 'shadow.type' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Stelt de eigenschap 'shadow.color' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Stelt de eigenschap 'shadow.color2' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Stelt de eigenschap 'shadow.opacity' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Stelt de eigenschap 'shadow.offset.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Stelt de eigenschap 'shadow.offset.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Stelt de eigenschap 'shadow.offset2.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Stelt de eigenschap 'shadow.offset2.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Stelt de eigenschap 'shadow.origin.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Stelt de eigenschap 'shadow.origin.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Stelt de eigenschap 'shadow.matrix.xtox' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Stelt de eigenschap 'shadow.matrix.xtoy' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Stelt de eigenschap 'shadow.matrix.ytox' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Stelt de eigenschap 'shadow.matrix.ytoy' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Stelt de eigenschap 'shadow.matrix.perspectiveX' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Stelt de eigenschap 'shadow.matrix.perspectiveY' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Stelt de eigenschap 'skew.on' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Stelt de eigenschap 'skew.offset.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Stelt de eigenschap 'skew.offset.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Stelt de eigenschap 'skew.origin.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Stelt de eigenschap 'skew.origin.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Stelt de eigenschap 'skew.matrix.xtox' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Stelt de eigenschap 'skew.matrix.xtoy' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Stelt de eigenschap 'skew.matrix.ytox' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Stelt de eigenschap 'skew.matrix.ytoy' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Stelt de eigenschap 'skew.matrix.perspectiveX' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Stelt de eigenschap 'skew.matrix.perspectiveY' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Stelt de eigenschap 'extrusion.on' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Stelt de eigenschap 'extrusion.type' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Stelt de eigenschap 'extrusion.render' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Stelt de eigenschap 'extrusion.viewpointorigin.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Stelt de eigenschap 'extrusion.viewpointorigin.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Stelt de eigenschap 'extrusion.viewpoint.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Stelt de eigenschap 'extrusion.viewpoint.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Stelt de eigenschap 'extrusion.viewpoint.z' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Stelt de eigenschap 'extrusion.plane' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Stelt de eigenschap 'extrusion.skewangle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Stelt de eigenschap 'extrusion.skewamt' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Stelt de eigenschap 'extrusion.backdepth' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Stelt de eigenschap 'extrusion.foredepth' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Stelt de eigenschap 'extrusion.orientation.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Stelt de eigenschap 'extrusion.orientation.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Stelt de eigenschap 'extrusion.orientation.z' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Stelt de eigenschap 'extrusion.orientationangle' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Stelt de eigenschap 'extrusion.color' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Stelt de eigenschap 'extrusion.rotationangle.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Stelt de eigenschap 'extrusion.rotationangle.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Stelt de eigenschap 'extrusion.lockrotationcenter' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Stelt de eigenschap 'extrusion.autorotationcenter' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Stelt de eigenschap 'extrusion.rotationcenter.x' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Stelt de eigenschap 'extrusion.rotationcenter.y' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Stelt de eigenschap 'extrusion.rotationcenter.z' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Stelt de eigenschap 'extrusion.colormode' voor

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Controleert of dit object gelijk is aan een ander.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Object om te vergelijken. |

**Retourwaarde:**
boolean - Waar als objecten gelijk zijn.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Berekent en retourneert een hashcode op basis van de eigenschap (#getValue.getValue)

**Retourwaarde:**
int - Geeft de hashcode voor dit object terug

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Zoekt naar een bestaande gedragseigenschap op basis van de waarde of maakt een nieuwe aangepaste aan met de opgegeven waarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | waarde van de eigenschap |

**Retourwaarde:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instantie van BehaviorProperty