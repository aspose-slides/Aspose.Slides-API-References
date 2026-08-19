---
title: BehaviorProperty
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de eigenschapstypen voor animatiegedrag voor.
type: docs
url: /nl/com.aspose.slides/behaviorproperty/
---
**Erfelijkheid:**  
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
| [isCustom()](#isCustom--) | Toont of deze eigenschap niet behoort tot de vooraf gedefinieerde eigenschappenlijst in de specificatie: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Vertegenwoordigt de eigenschap 'ppt\_x' |
| [getPptY()](#getPptY--) | Vertegenwoordigt de eigenschap 'ppt\_y' |
| [getPptW()](#getPptW--) | Vertegenwoordigt de eigenschap 'ppt\_w' |
| [getPptH()](#getPptH--) | Vertegenwoordigt de eigenschap 'ppt\_h' |
| [getPptC()](#getPptC--) | Vertegenwoordigt de eigenschap 'ppt\_c' |
| [getPptR()](#getPptR--) | Vertegenwoordigt de eigenschap 'ppt\_r' |
| [getXShear()](#getXShear--) | Vertegenwoordigt de eigenschap 'xshear' |
| [getYShear()](#getYShear--) | Vertegenwoordigt de eigenschap 'yshear' |
| [getImage()](#getImage--) | Vertegenwoordigt de eigenschap 'image' |
| [getScaleX()](#getScaleX--) | Vertegenwoordigt de eigenschap 'ScaleX' |
| [getScaleY()](#getScaleY--) | Vertegenwoordigt de eigenschap 'ScaleY' |
| [getR()](#getR--) | Vertegenwoordigt de eigenschap 'r' |
| [getFillColor()](#getFillColor--) | Vertegenwoordigt de eigenschap 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Vertegenwoordigt de eigenschap 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Vertegenwoordigt de eigenschap 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Vertegenwoordigt de eigenschap 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Vertegenwoordigt de eigenschap 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Vertegenwoordigt de eigenschap 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Vertegenwoordigt de eigenschap 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Vertegenwoordigt de eigenschap 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Vertegenwoordigt de eigenschap 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Vertegenwoordigt de eigenschap 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Vertegenwoordigt de eigenschap 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Vertegenwoordigt de eigenschap 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Vertegenwoordigt de eigenschap 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Vertegenwoordigt de eigenschap 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Vertegenwoordigt de eigenschap 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Vertegenwoordigt de eigenschap 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Vertegenwoordigt de eigenschap 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Vertegenwoordigt de eigenschap 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Vertegenwoordigt de eigenschap 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Vertegenwoordigt de eigenschap 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Vertegenwoordigt de eigenschap 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Vertegenwoordigt de eigenschap 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Vertegenwoordigt de eigenschap 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Vertegenwoordigt de eigenschap 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Vertegenwoordigt de eigenschap 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Vertegenwoordigt de eigenschap 'fill.on' |
| [getFillType()](#getFillType--) | Vertegenwoordigt de eigenschap 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Vertegenwoordigt de eigenschap 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Vertegenwoordigt de eigenschap 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Vertegenwoordigt de eigenschap 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Vertegenwoordigt de eigenschap 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Vertegenwoordigt de eigenschap 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Vertegenwoordigt de eigenschap 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Vertegenwoordigt de eigenschap 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Vertegenwoordigt de eigenschap 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Vertegenwoordigt de eigenschap 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Vertegenwoordigt de eigenschap 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Vertegenwoordigt de eigenschap 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Vertegenwoordigt de eigenschap 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Vertegenwoordigt de eigenschap 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Vertegenwoordigt de eigenschap 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Vertegenwoordigt de eigenschap 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Vertegenwoordigt de eigenschap 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Vertegenwoordigt de eigenschap 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Vertegenwoordigt de eigenschap 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Vertegenwoordigt de eigenschap 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Vertegenwoordigt de eigenschap 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Vertegenwoordigt de eigenschap 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Vertegenwoordigt de eigenschap 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Vertegenwoordigt de eigenschap 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Vertegenwoordigt de eigenschap 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Vertegenwoordigt de eigenschap 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Vertegenwoordigt de eigenschap 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Vertegenwoordigt de eigenschap 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Vertegenwoordigt de eigenschap 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Vertegenwoordigt de eigenschap 'shadow.on' |
| [getShadowType()](#getShadowType--) | Vertegenwoordigt de eigenschap 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Vertegenwoordigt de eigenschap 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Vertegenwoordigt de eigenschap 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Vertegenwoordigt de eigenschap 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Vertegenwoordigt de eigenschap 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Vertegenwoordigt de eigenschap 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Vertegenwoordigt de eigenschap 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Vertegenwoordigt de eigenschap 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Vertegenwoordigt de eigenschap 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Vertegenwoordigt de eigenschap 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Vertegenwoordigt de eigenschap 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Vertegenwoordigt de eigenschap 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Vertegenwoordigt de eigenschap 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Vertegenwoordigt de eigenschap 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Vertegenwoordigt de eigenschap 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Vertegenwoordigt de eigenschap 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Vertegenwoordigt de eigenschap 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Vertegenwoordigt de eigenschap 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Vertegenwoordigt de eigenschap 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Vertegenwoordigt de eigenschap 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Vertegenwoordigt de eigenschap 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Vertegenwoordigt de eigenschap 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Vertegenwoordigt de eigenschap 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Vertegenwoordigt de eigenschap 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Vertegenwoordigt de eigenschap 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Vertegenwoordigt de eigenschap 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Vertegenwoordigt de eigenschap 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Vertegenwoordigt de eigenschap 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Vertegenwoordigt de eigenschap 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Vertegenwoordigt de eigenschap 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Vertegenwoordigt de eigenschap 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Vertegenwoordigt de eigenschap 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Vertegenwoordigt de eigenschap 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Vertegenwoordigt de eigenschap 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Vertegenwoordigt de eigenschap 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Vertegenwoordigt de eigenschap 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Vertegenwoordigt de eigenschap 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Vertegenwoordigt de eigenschap 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Vertegenwoordigt de eigenschap 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Vertegenwoordigt de eigenschap 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Vertegenwoordigt de eigenschap 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Vertegenwoordigt de eigenschap 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Vertegenwoordigt de eigenschap 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Vertegenwoordigt de eigenschap 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Vertegenwoordigt de eigenschap 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Vertegenwoordigt de eigenschap 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Vertegenwoordigt de eigenschap 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Vertegenwoordigt de eigenschap 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Vertegenwoordigt de eigenschap 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Vertegenwoordigt de eigenschap 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Vertegenwoordigt de eigenschap 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Vertegenwoordigt de eigenschap 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Vertegenwoordigt de eigenschap 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Controleert of dit object gelijk is aan een ander. |
| [hashCode()](#hashCode--) | Berekent en retourneert een hashcode op basis van de (\#getValue.getValue) eigenschap |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Zoekt naar een bestaande gedragseigenschap op waarde of maakt een nieuwe aangepaste eigenschap aan met de opgegeven waarde |

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

Toont of deze eigenschap niet behoort tot de vooraf gedefinieerde eigenschappenlijst in de specificatie: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Retourwaarde:**  
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Vertegenwoordigt de eigenschap 'ppt\_x'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Vertegenwoordigt de eigenschap 'ppt\_y'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Vertegenwoordigt de eigenschap 'ppt\_w'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Vertegenwoordigt de eigenschap 'ppt\_h'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Vertegenwoordigt de eigenschap 'ppt\_c'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Vertegenwoordigt de eigenschap 'ppt\_r'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Vertegenwoordigt de eigenschap 'xshear'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Vertegenwoordigt de eigenschap 'yshear'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Vertegenwoordigt de eigenschap 'image'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Vertegenwoordigt de eigenschap 'ScaleX'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Vertegenwoordigt de eigenschap 'ScaleY'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Vertegenwoordigt de eigenschap 'r'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Vertegenwoordigt de eigenschap 'fillcolor'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Vertegenwoordigt de eigenschap 'style.opacity'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Vertegenwoordigt de eigenschap 'style.rotation'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Vertegenwoordigt de eigenschap 'style.visibility'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Vertegenwoordigt de eigenschap 'style.color'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Vertegenwoordigt de eigenschap 'style.fontSize'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Vertegenwoordigt de eigenschap 'style.fontWeight'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Vertegenwoordigt de eigenschap 'style.fontStyle'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Vertegenwoordigt de eigenschap 'style.fontFamily'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Vertegenwoordigt de eigenschap 'style.textEffectEmboss'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Vertegenwoordigt de eigenschap 'style.textShadow'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Vertegenwoordigt de eigenschap 'style.textTransform'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Vertegenwoordigt de eigenschap 'style.textDecorationUnderline'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Vertegenwoordigt de eigenschap 'style.textEffectOutline'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Vertegenwoordigt de eigenschap 'style.textDecorationLineThrough'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Vertegenwoordigt de eigenschap 'style.sRotation'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Vertegenwoordigt de eigenschap 'imageData.cropTop'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Vertegenwoordigt de eigenschap 'imageData.cropBottom'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Vertegenwoordigt de eigenschap 'imageData.cropLeft'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Vertegenwoordigt de eigenschap 'imageData.cropRight'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Vertegenwoordigt de eigenschap 'imageData.gain'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Vertegenwoordigt de eigenschap 'imageData.blacklevel'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Vertegenwoordigt de eigenschap 'imageData.gamma'

**Retourwaarde:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


Representeert de eigenschap 'imageData.grayscale'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


Representeert de eigenschap 'imageData.chromakey'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


Representeert de eigenschap 'fill.on'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


Representeert de eigenschap 'fill.type'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


Representeert de eigenschap 'fill.color'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


Representeert de eigenschap 'fill.opacity'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


Representeert de eigenschap 'fill.color2'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


Representeert de eigenschap 'fill.method'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


Representeert de eigenschap 'fill.opacity2'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


Representeert de eigenschap 'fill.angle'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


Representeert de eigenschap 'fill.focus'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


Representeert de eigenschap 'fill.focusposition.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


Representeert de eigenschap 'fill.focusposition.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


Representeert de eigenschap 'fill.focussize.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


Representeert de eigenschap 'fill.focussize.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


Representeert de eigenschap 'stroke.on'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


Representeert de eigenschap 'stroke.color'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


Representeert de eigenschap 'stroke.weight'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


Representeert de eigenschap 'stroke.opacity'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


Representeert de eigenschap 'stroke.linestyle'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


Representeert de eigenschap 'stroke.dashstyle'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


Representeert de eigenschap 'stroke.filltype'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


Representeert de eigenschap 'stroke.src'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


Representeert de eigenschap 'stroke.color2'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


Representeert de eigenschap 'stroke.imagesize.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


Representeert de eigenschap 'stroke.imagesize.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


Representeert de eigenschap 'stroke.startArrow'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


Representeert de eigenschap 'stroke.endArrow'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


Representeert de eigenschap 'stroke.startArrowWidth'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


Representeert de eigenschap 'stroke.startArrowLength'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


Representeert de eigenschap 'stroke.endArrowWidth'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


Representeert de eigenschap 'stroke.endArrowLength'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


Representeert de eigenschap 'shadow.on'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


Representeert de eigenschap 'shadow.type'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


Representeert de eigenschap 'shadow.color'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


Representeert de eigenschap 'shadow.color2'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


Representeert de eigenschap 'shadow.opacity'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


Representeert de eigenschap 'shadow.offset.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


Representeert de eigenschap 'shadow.offset.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


Representeert de eigenschap 'shadow.offset2.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


Representeert de eigenschap 'shadow.offset2.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


Representeert de eigenschap 'shadow.origin.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


Representeert de eigenschap 'shadow.origin.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Representeert de eigenschap 'shadow.matrix.xtox'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


Representeert de eigenschap 'shadow.matrix.xtoy'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


Representeert de eigenschap 'shadow.matrix.ytox'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


Representeert de eigenschap 'shadow.matrix.ytoy'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


Representeert de eigenschap 'shadow.matrix.perspectiveX'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


Representeert de eigenschap 'shadow.matrix.perspectiveY'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


Representeert de eigenschap 'skew.on'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


Representeert de eigenschap 'skew.offset.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


Representeert de eigenschap 'skew.offset.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


Representeert de eigenschap 'skew.origin.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


Representeert de eigenschap 'skew.origin.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


Representeert de eigenschap 'skew.matrix.xtox'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


Representeert de eigenschap 'skew.matrix.xtoy'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


Representeert de eigenschap 'skew.matrix.ytox'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


Representeert de eigenschap 'skew.matrix.ytoy'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


Representeert de eigenschap 'skew.matrix.perspectiveX'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


Representeert de eigenschap 'skew.matrix.perspectiveY'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


Representeert de eigenschap 'extrusion.on'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


Representeert de eigenschap 'extrusion.type'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


Representeert de eigenschap 'extrusion.render'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


Representeert de eigenschap 'extrusion.viewpointorigin.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


Representeert de eigenschap 'extrusion.viewpointorigin.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


Representeert de eigenschap 'extrusion.viewpoint.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


Representeert de eigenschap 'extrusion.viewpoint.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


Representeert de eigenschap 'extrusion.viewpoint.z'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


Representeert de eigenschap 'extrusion.plane'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


Representeert de eigenschap 'extrusion.skewangle'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


Representeert de eigenschap 'extrusion.skewamt'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


Representeert de eigenschap 'extrusion.backdepth'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


Representeert de eigenschap 'extrusion.foredepth'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


Representeert de eigenschap 'extrusion.orientation.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


Representeert de eigenschap 'extrusion.orientation.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


Representeert de eigenschap 'extrusion.orientation.z'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


Representeert de eigenschap 'extrusion.orientationangle'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


Representeert de eigenschap 'extrusion.color'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


Representeert de eigenschap 'extrusion.rotationangle.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


Representeert de eigenschap 'extrusion.rotationangle.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


Representeert de eigenschap 'extrusion.lockrotationcenter'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


Representeert de eigenschap 'extrusion.autorotationcenter'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


Representeert de eigenschap 'extrusion.rotationcenter.x'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


Representeert de eigenschap 'extrusion.rotationcenter.y'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


Representeert de eigenschap 'extrusion.rotationcenter.z'

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


Representeert de eigenschap 'extrusion.colormode'

**Retour:**
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

**Retour:**
boolean - Waar als objecten gelijk zijn.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent en retourneert de hashcode op basis van de (\#getValue.getValue) eigenschap

**Retour:**
int - Retourneert de hashcode voor dit object
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


Zoekt naar een bestaande gedrags-eigenschap op basis van waarde of maakt een nieuwe aangepaste aan met de opgegeven waarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | waarde van de eigenschap |

**Retour:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instantie van BehaviorProperty