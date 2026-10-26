---
title: BehaviorProperty
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa los tipos de propiedad para el comportamiento de animación.
type: docs
url: /es/com.aspose.slides/behaviorproperty/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Representa tipos de propiedad para el comportamiento de animación. Sigue la lista de propiedades de https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx y https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Valor de la propiedad |
| [isCustom()](#isCustom--) | Muestra si esta propiedad no pertenece a la lista de propiedades predefinidas en la especificación: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Representa la propiedad 'ppt\_x' |
| [getPptY()](#getPptY--) | Representa la propiedad 'ppt\_y' |
| [getPptW()](#getPptW--) | Representa la propiedad 'ppt\_w' |
| [getPptH()](#getPptH--) | Representa la propiedad 'ppt\_h' |
| [getPptC()](#getPptC--) | Representa la propiedad 'ppt\_c' |
| [getPptR()](#getPptR--) | Representa la propiedad 'ppt\_r' |
| [getXShear()](#getXShear--) | Representa la propiedad 'xshear' |
| [getYShear()](#getYShear--) | Representa la propiedad 'yshear' |
| [getImage()](#getImage--) | Representa la propiedad 'image' |
| [getScaleX()](#getScaleX--) | Representa la propiedad 'ScaleX' |
| [getScaleY()](#getScaleY--) | Representa la propiedad 'ScaleY' |
| [getR()](#getR--) | Representa la propiedad 'r' |
| [getFillColor()](#getFillColor--) | Representa la propiedad 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Representa la propiedad 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Representa la propiedad 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Representa la propiedad 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Representa la propiedad 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Representa la propiedad 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Representa la propiedad 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Representa la propiedad 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Representa la propiedad 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Representa la propiedad 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Representa la propiedad 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Representa la propiedad 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Representa la propiedad 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Representa la propiedad 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Representa la propiedad 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Representa la propiedad 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Representa la propiedad 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Representa la propiedad 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Representa la propiedad 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Representa la propiedad 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Representa la propiedad 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Representa la propiedad 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Representa la propiedad 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Representa la propiedad 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Representa la propiedad 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Representa la propiedad 'fill.on' |
| [getFillType()](#getFillType--) | Representa la propiedad 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Representa la propiedad 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Representa la propiedad 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Representa la propiedad 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Representa la propiedad 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Representa la propiedad 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Representa la propiedad 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Representa la propiedad 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Representa la propiedad 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Representa la propiedad 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Representa la propiedad 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Representa la propiedad 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Representa la propiedad 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Representa la propiedad 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Representa la propiedad 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Representa la propiedad 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Representa la propiedad 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Representa la propiedad 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Representa la propiedad 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Representa la propiedad 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Representa la propiedad 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Representa la propiedad 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Representa la propiedad 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Representa la propiedad 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Representa la propiedad 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Representa la propiedad 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Representa la propiedad 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Representa la propiedad 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Representa la propiedad 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Representa la propiedad 'shadow.on' |
| [getShadowType()](#getShadowType--) | Representa la propiedad 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Representa la propiedad 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Representa la propiedad 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Representa la propiedad 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Representa la propiedad 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Representa la propiedad 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Representa la propiedad 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Representa la propiedad 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Representa la propiedad 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Representa la propiedad 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Representa la propiedad 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Representa la propiedad 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Representa la propiedad 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Representa la propiedad 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Representa la propiedad 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Representa la propiedad 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Representa la propiedad 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Representa la propiedad 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Representa la propiedad 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Representa la propiedad 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Representa la propiedad 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Representa la propiedad 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Representa la propiedad 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Representa la propiedad 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Representa la propiedad 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Representa la propiedad 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Representa la propiedad 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Representa la propiedad 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Representa la propiedad 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Representa la propiedad 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Representa la propiedad 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Representa la propiedad 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Representa la propiedad 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Representa la propiedad 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Representa la propiedad 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Representa la propiedad 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Representa la propiedad 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Representa la propiedad 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Representa la propiedad 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Representa la propiedad 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Representa la propiedad 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Representa la propiedad 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Representa la propiedad 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Representa la propiedad 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Representa la propiedad 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Representa la propiedad 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Representa la propiedad 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Representa la propiedad 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Representa la propiedad 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Representa la propiedad 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Representa la propiedad 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Representa la propiedad 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Representa la propiedad 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Comprueba si este objeto es igual a otro. |
| [hashCode()](#hashCode--) | Calcula y devuelve el código hash basado en la propiedad (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Busca una propiedad de comportamiento existente por valor o crea una nueva personalizada con el valor especificado |

### getValue() {#getValue--}
```
public final String getValue()
```

Valor de la propiedad

**Devuelve:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Muestra si esta propiedad no pertenece a la lista de propiedades predefinidas en la especificación: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Devuelve:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Representa la propiedad 'ppt\_x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Representa la propiedad 'ppt\_y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Representa la propiedad 'ppt\_w'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Representa la propiedad 'ppt\_h'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Representa la propiedad 'ppt\_c'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Representa la propiedad 'ppt\_r'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Representa la propiedad 'xshear'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Representa la propiedad 'yshear'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Representa la propiedad 'image'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Representa la propiedad 'ScaleX'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Representa la propiedad 'ScaleY'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Representa la propiedad 'r'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Representa la propiedad 'fillcolor'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Representa la propiedad 'style.opacity'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Representa la propiedad 'style.rotation'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Representa la propiedad 'style.visibility'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Representa la propiedad 'style.color'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Representa la propiedad 'style.fontSize'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Representa la propiedad 'style.fontWeight'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Representa la propiedad 'style.fontStyle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Representa la propiedad 'style.fontFamily'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Representa la propiedad 'style.textEffectEmboss'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Representa la propiedad 'style.textShadow'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Representa la propiedad 'style.textTransform'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Representa la propiedad 'style.textDecorationUnderline'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Representa la propiedad 'style.textEffectOutline'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Representa la propiedad 'style.textDecorationLineThrough'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Representa la propiedad 'style.sRotation'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Representa la propiedad 'imageData.cropTop'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Representa la propiedad 'imageData.cropBottom'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Representa la propiedad 'imageData.cropLeft'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Representa la propiedad 'imageData.cropRight'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Representa la propiedad 'imageData.gain'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Representa la propiedad 'imageData.blacklevel'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Representa la propiedad 'imageData.gamma'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Representa la propiedad 'imageData.grayscale'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Representa la propiedad 'imageData.chromakey'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Representa la propiedad 'fill.on'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Representa la propiedad 'fill.type'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Representa la propiedad 'fill.color'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Representa la propiedad 'fill.opacity'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Representa la propiedad 'fill.color2'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Representa la propiedad 'fill.method'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Representa la propiedad 'fill.opacity2'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Representa la propiedad 'fill.angle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Representa la propiedad 'fill.focus'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Representa la propiedad 'fill.focusposition.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Representa la propiedad 'fill.focusposition.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Representa la propiedad 'fill.focussize.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Representa la propiedad 'fill.focussize.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Representa la propiedad 'stroke.on'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Representa la propiedad 'stroke.color'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Representa la propiedad 'stroke.weight'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Representa la propiedad 'stroke.opacity'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Representa la propiedad 'stroke.linestyle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Representa la propiedad 'stroke.dashstyle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Representa la propiedad 'stroke.filltype'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Representa la propiedad 'stroke.src'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Representa la propiedad 'stroke.color2'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Representa la propiedad 'stroke.imagesize.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Representa la propiedad 'stroke.imagesize.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Representa la propiedad 'stroke.startArrow'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Representa la propiedad 'stroke.endArrow'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Representa la propiedad 'stroke.startArrowWidth'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Representa la propiedad 'stroke.startArrowLength'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Representa la propiedad 'stroke.endArrowWidth'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Representa la propiedad 'stroke.endArrowLength'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public  
```

Representa la propiedad 'shadow.on'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Representa la propiedad 'shadow.type'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Representa la propiedad 'shadow.color'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Representa la propiedad 'shadow.color2'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Representa la propiedad 'shadow.opacity'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Representa la propiedad 'shadow.offset.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Representa la propiedad 'shadow.offset.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Representa la propiedad 'shadow.offset2.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Representa la propiedad 'shadow.offset2.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Representa la propiedad 'shadow.origin.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Representa la propiedad 'shadow.origin.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Representa la propiedad 'shadow.matrix.xtox'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Representa la propiedad 'shadow.matrix.xtoy'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Representa la propiedad 'shadow.matrix.ytox'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Representa la propiedad 'shadow.matrix.ytoy'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Representa la propiedad 'shadow.matrix.perspectiveX'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Representa la propiedad 'shadow.matrix.perspectiveY'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Representa la propiedad 'skew.on'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Representa la propiedad 'skew.offset.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Representa la propiedad 'skew.offset.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Representa la propiedad 'skew.origin.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Representa la propiedad 'skew.origin.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Representa la propiedad 'skew.matrix.xtox'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Representa la propiedad 'skew.matrix.xtoy'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Representa la propiedad 'skew.matrix.ytox'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Representa la propiedad 'skew.matrix.ytoy'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Representa la propiedad 'skew.matrix.perspectiveX'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Representa la propiedad 'skew.matrix.perspectiveY'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Representa la propiedad 'extrusion.on'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Representa la propiedad 'extrusion.type'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Representa la propiedad 'extrusion.render'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Representa la propiedad 'extrusion.viewpointorigin.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Representa la propiedad 'extrusion.viewpointorigin.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Representa la propiedad 'extrusion.viewpoint.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Representa la propiedad 'extrusion.viewpoint.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Representa la propiedad 'extrusion.viewpoint.z'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Representa la propiedad 'extrusion.plane'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Representa la propiedad 'extrusion.skewangle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Representa la propiedad 'extrusion.skewamt'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Representa la propiedad 'extrusion.backdepth'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Representa la propiedad 'extrusion.foredepth'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Representa la propiedad 'extrusion.orientation.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Representa la propiedad 'extrusion.orientation.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Representa la propiedad 'extrusion.orientation.z'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Representa la propiedad 'extrusion.orientationangle'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Representa la propiedad 'extrusion.color'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Representa la propiedad 'extrusion.rotationangle.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Representa la propiedad 'extrusion.rotationangle.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Representa la propiedad 'extrusion.lockrotationcenter'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Representa la propiedad 'extrusion.autorotationcenter'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Representa la propiedad 'extrusion.rotationcenter.x'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Representa la propiedad 'extrusion.rotationcenter.y'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Representa la propiedad 'extrusion.rotationcenter.z'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Representa la propiedad 'extrusion.colormode'

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Comprueba si este objeto es igual a otro.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a comparar. |

**Devuelve:**
boolean - Verdadero si los objetos son iguales.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Calcula y devuelve el código hash basado en la propiedad (\#getValue.getValue)

**Devuelve:**
int - Devuelve el código hash para este objeto

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Busca una propiedad de comportamiento existente por valor o crea una nueva personalizada con el valor especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propertyValue | java.lang.String | valor de la propiedad |

**Devuelve:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instancia de BehaviorProperty