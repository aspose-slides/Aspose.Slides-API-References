---
title: BehaviorProperty
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa tipos de propriedade para comportamento de animação.
type: docs
url: /pt/com.aspose.slides/behaviorproperty/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Representa tipos de propriedade para comportamento de animação. Segue a lista de propriedades de https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx e https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Métodos

| Método | Descrição |
| --- | --- |
| [getValue()](#getValue--) | Valor da propriedade |
| [isCustom()](#isCustom--) | Indica se esta propriedade não pertence à lista de propriedades predefinidas na especificação: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Representa a propriedade 'ppt_x' |
| [getPptY()](#getPptY--) | Representa a propriedade 'ppt_y' |
| [getPptW()](#getPptW--) | Representa a propriedade 'ppt_w' |
| [getPptH()](#getPptH--) | Representa a propriedade 'ppt_h' |
| [getPptC()](#getPptC--) | Representa a propriedade 'ppt_c' |
| [getPptR()](#getPptR--) | Representa a propriedade 'ppt_r' |
| [getXShear()](#getXShear--) | Representa a propriedade 'xshear' |
| [getYShear()](#getYShear--) | Representa a propriedade 'yshear' |
| [getImage()](#getImage--) | Representa a propriedade 'image' |
| [getScaleX()](#getScaleX--) | Representa a propriedade 'ScaleX' |
| [getScaleY()](#getScaleY--) | Representa a propriedade 'ScaleY' |
| [getR()](#getR--) | Representa a propriedade 'r' |
| [getFillColor()](#getFillColor--) | Representa a propriedade 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Representa a propriedade 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Representa a propriedade 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Representa a propriedade 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Representa a propriedade 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Representa a propriedade 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Representa a propriedade 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Representa a propriedade 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Representa a propriedade 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Representa a propriedade 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Representa a propriedade 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Representa a propriedade 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Representa a propriedade 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Representa a propriedade 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Representa a propriedade 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Representa a propriedade 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Representa a propriedade 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Representa a propriedade 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Representa a propriedade 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Representa a propriedade 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Representa a propriedade 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Representa a propriedade 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Representa a propriedade 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Representa a propriedade 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Representa a propriedade 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Representa a propriedade 'fill.on' |
| [getFillType()](#getFillType--) | Representa a propriedade 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Representa a propriedade 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Representa a propriedade 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Representa a propriedade 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Representa a propriedade 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Representa a propriedade 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Representa a propriedade 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Representa a propriedade 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Representa a propriedade 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Representa a propriedade 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Representa a propriedade 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Representa a propriedade 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Representa a propriedade 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Representa a propriedade 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Representa a propriedade 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Representa a propriedade 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Representa a propriedade 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Representa a propriedade 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Representa a propriedade 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Representa a propriedade 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Representa a propriedade 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Representa a propriedade 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Representa a propriedade 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Representa a propriedade 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Representa a propriedade 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Representa a propriedade 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Representa a propriedade 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Representa a propriedade 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Representa a propriedade 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Representa a propriedade 'shadow.on' |
| [getShadowType()](#getShadowType--) | Representa a propriedade 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Representa a propriedade 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Representa a propriedade 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Representa a propriedade 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Representa a propriedade 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Representa a propriedade 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Representa a propriedade 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Representa a propriedade 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Representa a propriedade 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Representa a propriedade 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Representa a propriedade 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Representa a propriedade 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Representa a propriedade 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Representa a propriedade 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Representa a propriedade 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Representa a propriedade 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Representa a propriedade 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Representa a propriedade 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Representa a propriedade 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Representa a propriedade 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Representa a propriedade 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Representa a propriedade 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Representa a propriedade 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Representa a propriedade 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Representa a propriedade 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Representa a propriedade 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Representa a propriedade 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Representa a propriedade 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Representa a propriedade 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Representa a propriedade 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Representa a propriedade 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Representa a propriedade 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Representa a propriedade 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Representa a propriedade 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Representa a propriedade 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Representa a propriedade 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Representa a propriedade 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Representa a propriedade 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Representa a propriedade 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Representa a propriedade 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Representa a propriedade 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Representa a propriedade 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Representa a propriedade 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Representa a propriedade 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Representa a propriedade 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Representa a propriedade 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Representa a propriedade 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Representa a propriedade 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Representa a propriedade 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Representa a propriedade 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Representa a propriedade 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Representa a propriedade 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Representa a propriedade 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se este objeto é igual a outro. |
| [hashCode()](#hashCode--) | Calcula e retorna o código hash baseado na propriedade (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Procura por propriedade de comportamento existente pelo valor ou cria uma nova personalizada com o valor especificado |
### getValue() {#getValue--}
```
public final String getValue()
```

Valor da propriedade

**Retorna:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Indica se esta propriedade não pertence à lista de propriedades predefinidas na especificação: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Retorna:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Representa a propriedade 'ppt_x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Representa a propriedade 'ppt_y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Representa a propriedade 'ppt_w'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Representa a propriedade 'ppt_h'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Representa a propriedade 'ppt_c'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Representa a propriedade 'ppt_r'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Representa a propriedade 'xshear'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Representa a propriedade 'yshear'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Representa a propriedade 'image'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Representa a propriedade 'ScaleX'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Representa a propriedade 'ScaleY'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Representa a propriedade 'r'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Representa a propriedade 'fillcolor'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Representa a propriedade 'style.opacity'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Representa a propriedade 'style.rotation'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Representa a propriedade 'style.visibility'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Representa a propriedade 'style.color'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Representa a propriedade 'style.fontSize'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Representa a propriedade 'style.fontWeight'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Representa a propriedade 'style.fontStyle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Representa a propriedade 'style.fontFamily'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Representa a propriedade 'style.textEffectEmboss'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Representa a propriedade 'style.textShadow'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Representa a propriedade 'style.textTransform'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Representa a propriedade 'style.textDecorationUnderline'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Representa a propriedade 'style.textEffectOutline'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Representa a propriedade 'style.textDecorationLineThrough'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Representa a propriedade 'style.sRotation'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Representa a propriedade 'imageData.cropTop'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Representa a propriedade 'imageData.cropBottom'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Representa a propriedade 'imageData.cropLeft'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Representa a propriedade 'imageData.cropRight'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Representa a propriedade 'imageData.gain'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Representa a propriedade 'imageData.blacklevel'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Representa a propriedade 'imageData.gamma'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Representa a propriedade 'imageData.grayscale'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Representa a propriedade 'imageData.chromakey'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Representa a propriedade 'fill.on'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Representa a propriedade 'fill.type'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Representa a propriedade 'fill.color'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Representa a propriedade 'fill.opacity'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Representa a propriedade 'fill.color2'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Representa a propriedade 'fill.method'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Representa a propriedade 'fill.opacity2'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Representa a propriedade 'fill.angle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Representa a propriedade 'fill.focus'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Representa a propriedade 'fill.focusposition.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Representa a propriedade 'fill.focusposition.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Representa a propriedade 'fill.focussize.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Representa a propriedade 'fill.focussize.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Representa a propriedade 'stroke.on'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Representa a propriedade 'stroke.color'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Representa a propriedade 'stroke.weight'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Representa a propriedade 'stroke.opacity'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Representa a propriedade 'stroke.linestyle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Representa a propriedade 'stroke.dashstyle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Representa a propriedade 'stroke.filltype'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Representa a propriedade 'stroke.src'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Representa a propriedade 'stroke.color2'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Representa a propriedade 'stroke.imagesize.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Representa a propriedade 'stroke.imagesize.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Representa a propriedade 'stroke.startArrow'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Representa a propriedade 'stroke.endArrow'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Representa a propriedade 'stroke.startArrowWidth'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Representa a propriedade 'stroke.startArrowLength'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Representa a propriedade 'stroke.endArrowWidth'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Representa a propriedade 'stroke.endArrowLength'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Representa a propriedade 'shadow.on'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Representa a propriedade 'shadow.type'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Representa a propriedade 'shadow.color'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Representa a propriedade 'shadow.color2'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Representa a propriedade 'shadow.opacity'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Representa a propriedade 'shadow.offset.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Representa a propriedade 'shadow.offset.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Representa a propriedade 'shadow.offset2.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Representa a propriedade 'shadow.offset2.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Representa a propriedade 'shadow.origin.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Representa a propriedade 'shadow.origin.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Representa a propriedade 'shadow.matrix.xtox'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Representa a propriedade 'shadow.matrix.xtoy'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Representa a propriedade 'shadow.matrix.ytox'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Representa a propriedade 'shadow.matrix.ytoy'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Representa a propriedade 'shadow.matrix.perspectiveX'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Representa a propriedade 'shadow.matrix.perspectiveY'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Representa a propriedade 'skew.on'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Representa a propriedade 'skew.offset.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Representa a propriedade 'skew.offset.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Representa a propriedade 'skew.origin.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Representa a propriedade 'skew.origin.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Representa a propriedade 'skew.matrix.xtox'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Representa a propriedade 'skew.matrix.xtoy'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Representa a propriedade 'skew.matrix.ytox'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Representa a propriedade 'skew.matrix.ytoy'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Representa a propriedade 'skew.matrix.perspectiveX'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Representa a propriedade 'skew.matrix.perspectiveY'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Representa a propriedade 'extrusion.on'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Representa a propriedade 'extrusion.type'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Representa a propriedade 'extrusion.render'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Representa a propriedade 'extrusion.viewpointorigin.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Representa a propriedade 'extrusion.viewpointorigin.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Representa a propriedade 'extrusion.viewpoint.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Representa a propriedade 'extrusion.viewpoint.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Representa a propriedade 'extrusion.viewpoint.z'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Representa a propriedade 'extrusion.plane'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Representa a propriedade 'extrusion.skewangle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Representa a propriedade 'extrusion.skewamt'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Representa a propriedade 'extrusion.backdepth'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Representa a propriedade 'extrusion.foredepth'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Representa a propriedade 'extrusion.orientation.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Representa a propriedade 'extrusion.orientation.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Representa a propriedade 'extrusion.orientation.z'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Representa a propriedade 'extrusion.orientationangle'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Representa a propriedade 'extrusion.color'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Representa a propriedade 'extrusion.rotationangle.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Representa a propriedade 'extrusion.rotationangle.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Representa a propriedade 'extrusion.lockrotationcenter'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Representa a propriedade 'extrusion.autorotationcenter'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Representa a propriedade 'extrusion.rotationcenter.x'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Representa a propriedade 'extrusion.rotationcenter.y'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Representa a propriedade 'extrusion.rotationcenter.z'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Representa a propriedade 'extrusion.colormode'

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Verifica se este objeto é igual a outro.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | Objeto a ser comparado. |

**Retorna:**
boolean - true se os objetos forem iguais.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Calcula e retorna o código hash baseado na propriedade (\#getValue.getValue)

**Retorna:**
int - Retorna o código hash para este objeto
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Procura por propriedade de comportamento existente pelo valor ou cria uma nova personalizada com o valor especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| propertyValue | java.lang.String | valor da propriedade |

**Retorna:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instância de BehaviorProperty