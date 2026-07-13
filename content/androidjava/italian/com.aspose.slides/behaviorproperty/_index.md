---
title: BehaviorProperty
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta i tipi di proprietà per il comportamento dell'animazione.
type: docs
url: /it/com.aspose.slides/behaviorproperty/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Rappresenta i tipi di proprietà per il comportamento dell'animazione. Segue l'elenco delle proprietà da https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx e https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Valore della proprietà |
| [isCustom()](#isCustom--) | Indica se questa proprietà non appartiene all'elenco delle proprietà predefinite nella specifica: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Rappresenta la proprietà 'ppt_x' |
| [getPptY()](#getPptY--) | Rappresenta la proprietà 'ppt_y' |
| [getPptW()](#getPptW--) | Rappresenta la proprietà 'ppt_w' |
| [getPptH()](#getPptH--) | Rappresenta la proprietà 'ppt_h' |
| [getPptC()](#getPptC--) | Rappresenta la proprietà 'ppt_c' |
| [getPptR()](#getPptR--) | Rappresenta la proprietà 'ppt_r' |
| [getXShear()](#getXShear--) | Rappresenta la proprietà 'xshear' |
| [getYShear()](#getYShear--) | Rappresenta la proprietà 'yshear' |
| [getImage()](#getImage--) | Rappresenta la proprietà 'image' |
| [getScaleX()](#getScaleX--) | Rappresenta la proprietà 'ScaleX' |
| [getScaleY()](#getScaleY--) | Rappresenta la proprietà 'ScaleY' |
| [getR()](#getR--) | Rappresenta la proprietà 'r' |
| [getFillColor()](#getFillColor--) | Rappresenta la proprietà 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Rappresenta la proprietà 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Rappresenta la proprietà 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Rappresenta la proprietà 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Rappresenta la proprietà 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Rappresenta la proprietà 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Rappresenta la proprietà 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Rappresenta la proprietà 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Rappresenta la proprietà 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Rappresenta la proprietà 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Rappresenta la proprietà 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Rappresenta la proprietà 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Rappresenta la proprietà 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Rappresenta la proprietà 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Rappresenta la proprietà 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Rappresenta la proprietà 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Rappresenta la proprietà 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Rappresenta la proprietà 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Rappresenta la proprietà 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Rappresenta la proprietà 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Rappresenta la proprietà 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Rappresenta la proprietà 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Rappresenta la proprietà 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Rappresenta la proprietà 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Rappresenta la proprietà 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Rappresenta la proprietà 'fill.on' |
| [getFillType()](#getFillType--) | Rappresenta la proprietà 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Rappresenta la proprietà 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Rappresenta la proprietà 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Rappresenta la proprietà 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Rappresenta la proprietà 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Rappresenta la proprietà 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Rappresenta la proprietà 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Rappresenta la proprietà 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Rappresenta la proprietà 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Rappresenta la proprietà 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Rappresenta la proprietà 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Rappresenta la proprietà 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Rappresenta la proprietà 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Rappresenta la proprietà 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Rappresenta la proprietà 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Rappresenta la proprietà 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Rappresenta la proprietà 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Rappresenta la proprietà 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Rappresenta la proprietà 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Rappresenta la proprietà 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Rappresenta la proprietà 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Rappresenta la proprietà 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Rappresenta la proprietà 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Rappresenta la proprietà 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Rappresenta la proprietà 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Rappresenta la proprietà 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Rappresenta la proprietà 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Rappresenta la proprietà 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Rappresenta la proprietà 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Rappresenta la proprietà 'shadow.on' |
| [getShadowType()](#getShadowType--) | Rappresenta la proprietà 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Rappresenta la proprietà 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Rappresenta la proprietà 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Rappresenta la proprietà 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Rappresenta la proprietà 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Rappresenta la proprietà 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Rappresenta la proprietà 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Rappresenta la proprietà 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Rappresenta la proprietà 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Rappresenta la proprietà 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Rappresenta la proprietà 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Rappresenta la proprietà 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Rappresenta la proprietà 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Rappresenta la proprietà 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Rappresenta la proprietà 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Rappresenta la proprietà 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Rappresenta la proprietà 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Rappresenta la proprietà 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Rappresenta la proprietà 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Rappresenta la proprietà 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Rappresenta la proprietà 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Rappresenta la proprietà 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Rappresenta la proprietà 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Rappresenta la proprietà 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Rappresenta la proprietà 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Rappresenta la proprietà 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Rappresenta la proprietà 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Rappresenta la proprietà 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Rappresenta la proprietà 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Rappresenta la proprietà 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Rappresenta la proprietà 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Rappresenta la proprietà 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Rappresenta la proprietà 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Rappresenta la proprietà 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Rappresenta la proprietà 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Rappresenta la proprietà 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Rappresenta la proprietà 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Rappresenta la proprietà 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Rappresenta la proprietà 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Rappresenta la proprietà 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Rappresenta la proprietà 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Rappresenta la proprietà 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Rappresenta la proprietà 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Rappresenta la proprietà 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Rappresenta la proprietà 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Rappresenta la proprietà 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Rappresenta la proprietà 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Rappresenta la proprietà 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Rappresenta la proprietà 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Rappresenta la proprietà 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Rappresenta la proprietà 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Rappresenta la proprietà 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Rappresenta la proprietà 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se questo oggetto è uguale a un altro. |
| [hashCode()](#hashCode--) | Calcola e restituisce il codice hash basato sulla proprietà (#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Cerca una proprietà di comportamento esistente per valore o crea una nuova personalizzata con il valore specificato |

### getValue() {#getValue--}
```
public final String getValue()
```

Valore della proprietà

**Restituisce:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Indica se questa proprietà non appartiene all'elenco delle proprietà predefinite nella specifica: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Restituisce:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Rappresenta la proprietà 'ppt_x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Rappresenta la proprietà 'ppt_y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Rappresenta la proprietà 'ppt_w'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Rappresenta la proprietà 'ppt_h'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Rappresenta la proprietà 'ppt_c'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Rappresenta la proprietà 'ppt_r'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Rappresenta la proprietà 'xshear'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Rappresenta la proprietà 'yshear'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Rappresenta la proprietà 'image'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Rappresenta la proprietà 'ScaleX'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Rappresenta la proprietà 'ScaleY'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Rappresenta la proprietà 'r'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Rappresenta la proprietà 'fillcolor'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Rappresenta la proprietà 'style.opacity'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Rappresenta la proprietà 'style.rotation'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Rappresenta la proprietà 'style.visibility'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Rappresenta la proprietà 'style.color'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Rappresenta la proprietà 'style.fontSize'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Rappresenta la proprietà 'style.fontWeight'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Rappresenta la proprietà 'style.fontStyle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Rappresenta la proprietà 'style.fontFamily'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Rappresenta la proprietà 'style.textEffectEmboss'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Rappresenta la proprietà 'style.textShadow'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Rappresenta la proprietà 'style.textTransform'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Rappresenta la proprietà 'style.textDecorationUnderline'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Rappresenta la proprietà 'style.textEffectOutline'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Rappresenta la proprietà 'style.textDecorationLineThrough'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Rappresenta la proprietà 'style.sRotation'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Rappresenta la proprietà 'imageData.cropTop'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Rappresenta la proprietà 'imageData.cropBottom'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Rappresenta la proprietà 'imageData.cropLeft'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Rappresenta la proprietà 'imageData.cropRight'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Rappresenta la proprietà 'imageData.gain'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Rappresenta la proprietà 'imageData.blacklevel'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Rappresenta la proprietà 'imageData.gamma'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Rappresenta la proprietà 'imageData.grayscale'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Rappresenta la proprietà 'imageData.chromakey'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Rappresenta la proprietà 'fill.on'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Rappresenta la proprietà 'fill.type'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Rappresenta la proprietà 'fill.color'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Rappresenta la proprietà 'fill.opacity'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Rappresenta la proprietà 'fill.color2'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Rappresenta la proprietà 'fill.method'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Rappresenta la proprietà 'fill.opacity2'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Rappresenta la proprietà 'fill.angle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Rappresenta la proprietà 'fill.focus'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Rappresenta la proprietà 'fill.focusposition.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Rappresenta la proprietà 'fill.focusposition.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Rappresenta la proprietà 'fill.focussize.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Rappresenta la proprietà 'fill.focussize.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Rappresenta la proprietà 'stroke.on'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Rappresenta la proprietà 'stroke.color'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Rappresenta la proprietà 'stroke.weight'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Rappresenta la proprietà 'stroke.opacity'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Rappresenta la proprietà 'stroke.linestyle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Rappresenta la proprietà 'stroke.dashstyle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Rappresenta la proprietà 'stroke.filltype'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Rappresenta la proprietà 'stroke.src'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Rappresenta la proprietà 'stroke.color2'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Rappresenta la proprietà 'stroke.imagesize.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Rappresenta la proprietà 'stroke.imagesize.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Rappresenta la proprietà 'stroke.startArrow'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Rappresenta la proprietà 'stroke.endArrow'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Rappresenta la proprietà 'stroke.startArrowWidth'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Rappresenta la proprietà 'stroke.startArrowLength'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Rappresenta la proprietà 'stroke.endArrowWidth'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Rappresenta la proprietà 'stroke.endArrowLength'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Rappresenta la proprietà 'shadow.on'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Rappresenta la proprietà 'shadow.type'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Rappresenta la proprietà 'shadow.color'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Rappresenta la proprietà 'shadow.color2'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Rappresenta la proprietà 'shadow.opacity'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Rappresenta la proprietà 'shadow.offset.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Rappresenta la proprietà 'shadow.offset.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Rappresenta la proprietà 'shadow.offset2.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Rappresenta la proprietà 'shadow.offset2.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Rappresenta la proprietà 'shadow.origin.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Rappresenta la proprietà 'shadow.origin.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Rappresenta la proprietà 'shadow.matrix.xtox'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Rappresenta la proprietà 'shadow.matrix.xtoy'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Rappresenta la proprietà 'shadow.matrix.ytox'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Rappresenta la proprietà 'shadow.matrix.ytoy'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Rappresenta la proprietà 'shadow.matrix.perspectiveX'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Rappresenta la proprietà 'shadow.matrix.perspectiveY'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Rappresenta la proprietà 'skew.on'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Rappresenta la proprietà 'skew.offset.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Rappresenta la proprietà 'skew.offset.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Rappresenta la proprietà 'skew.origin.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Rappresenta la proprietà 'skew.origin.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Rappresenta la proprietà 'skew.matrix.xtox'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public .     
```

Rappresenta la proprietà 'skew.matrix.xtoy'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Rappresenta la proprietà 'skew.matrix.ytox'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Rappresenta la proprietà 'skew.matrix.ytoy'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Rappresenta la proprietà 'skew.matrix.perspectiveX'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Rappresenta la proprietà 'skew.matrix.perspectiveY'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Rappresenta la proprietà 'extrusion.on'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Rappresenta la proprietà 'extrusion.type'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Rappresenta la proprietà 'extrusion.render'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Rappresenta la proprietà 'extrusion.viewpointorigin.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Rappresenta la proprietà 'extrusion.viewpointorigin.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Rappresenta la proprietà 'extrusion.viewpoint.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Rappresenta la proprietà 'extrusion.viewpoint.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Rappresenta la proprietà 'extrusion.viewpoint.z'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Rappresenta la proprietà 'extrusion.plane'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Rappresenta la proprietà 'extrusion.skewangle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Rappresenta la proprietà 'extrusion.skewamt'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Rappresenta la proprietà 'extrusion.backdepth'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Rappresenta la proprietà 'extrusion.foredepth'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Rappresenta la proprietà 'extrusion.orientation.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Rappresenta la proprietà 'extrusion.orientation.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Rappresenta la proprietà 'extrusion.orientation.z'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Rappresenta la proprietà 'extrusion.orientationangle'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Rappresenta la proprietà 'extrusion.color'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Rappresenta la proprietà 'extrusion.rotationangle.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Rappresenta la proprietà 'extrusion.rotationangle.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Rappresenta la proprietà 'extrusion.lockrotationcenter'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Rappresenta la proprietà 'extrusion.autorotationcenter'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Rappresenta la proprietà 'extrusion.rotationcenter.x'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Rappresenta la proprietà 'extrusion.rotationcenter.y'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Rappresenta la proprietà 'extrusion.rotationcenter.z'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Rappresenta la proprietà 'extrusion.colormode'

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Verifica se questo oggetto è uguale a un altro.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto da confrontare. |

**Restituisce:**
boolean - True if objects are equal.

### hashCode() {#hashCode--}
```
public boolean equals(Object obj)
```

Calcola e restituisce il codice hash basato sulla proprietà (#getValue.getValue)

**Restituisce:**
int - Returns hash code for this object

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Cerca una proprietà di comportamento esistente per valore o crea una nuova personalizzata con il valore specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | valore della proprietà |

**Restituisce:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance of BehaviorProperty