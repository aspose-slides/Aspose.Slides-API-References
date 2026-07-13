---
title: BehaviorProperty
second_title: Aspose.Slides dla Androida za pomocą referencji API Java
description: Reprezentuje typy właściwości dla zachowania animacji.
type: docs
url: /pl/com.aspose.slides/behaviorproperty/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Reprezentuje typy właściwości zachowania animacji. Opiera się na liście właściwości z https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx i https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metody

| Metoda | Opis |
| --- | --- |
| [getValue()](#getValue--) | Wartość właściwości |
| [isCustom()](#isCustom--) | Pokazuje, czy ta właściwość nie należy do listy wstępnie zdefiniowanych właściwości w specyfikacji: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Reprezentuje właściwość 'ppt\_x' |
| [getPptY()](#getPptY--) | Reprezentuje właściwość 'ppt\_y' |
| [getPptW()](#getPptW--) | Reprezentuje właściwość 'ppt\_w' |
| [getPptH()](#getPptH--) | Reprezentuje właściwość 'ppt\_h' |
| [getPptC()](#getPptC--) | Reprezentuje właściwość 'ppt\_c' |
| [getPptR()](#getPptR--) | Reprezentuje właściwość 'ppt\_r' |
| [getXShear()](#getXShear--) | Reprezentuje właściwość 'xshear' |
| [getYShear()](#getYShear--) | Reprezentuje właściwość 'yshear' |
| [getImage()](#getImage--) | Reprezentuje właściwość 'image' |
| [getScaleX()](#getScaleX--) | Reprezentuje właściwość 'ScaleX' |
| [getScaleY()](#getScaleY--) | Reprezentuje właściwość 'ScaleY' |
| [getR()](#getR--) | Reprezentuje właściwość 'r' |
| [getFillColor()](#getFillColor--) | Reprezentuje właściwość 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Reprezentuje właściwość 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Reprezentuje właściwość 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Reprezentuje właściwość 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Reprezentuje właściwość 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Reprezentuje właściwość 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Reprezentuje właściwość 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Reprezentuje właściwość 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Reprezentuje właściwość 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Reprezentuje właściwość 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Reprezentuje właściwość 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Reprezentuje właściwość 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Reprezentuje właściwość 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Reprezentuje właściwość 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Reprezentuje właściwość 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Reprezentuje właściwość 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Reprezentuje właściwość 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Reprezentuje właściwość 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Reprezentuje właściwość 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Reprezentuje właściwość 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Reprezentuje właściwość 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Reprezentuje właściwość 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Reprezentuje właściwość 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Reprezentuje właściwość 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Reprezentuje właściwość 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Reprezentuje właściwość 'fill.on' |
| [getFillType()](#getFillType--) | Reprezentuje właściwość 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Reprezentuje właściwość 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Reprezentuje właściwość 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Reprezentuje właściwość 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Reprezentuje właściwość 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Reprezentuje właściwość 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Reprezentuje właściwość 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Reprezentuje właściwość 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Reprezentuje właściwość 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Reprezentuje właściwość 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Reprezentuje właściwość 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Reprezentuje właściwość 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Reprezentuje właściwość 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Reprezentuje właściwość 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Reprezentuje właściwość 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Reprezentuje właściwość 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Reprezentuje właściwość 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Reprezentuje właściwość 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Reprezentuje właściwość 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Reprezentuje właściwość 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Reprezentuje właściwość 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Reprezentuje właściwość 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Reprezentuje właściwość 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Reprezentuje właściwość 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Reprezentuje właściwość 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Reprezentuje właściwość 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Reprezentuje właściwość 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Reprezentuje właściwość 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Reprezentuje właściwość 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Reprezentuje właściwość 'shadow.on' |
| [getShadowType()](#getShadowType--) | Reprezentuje właściwość 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Reprezentuje właściwość 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Reprezentuje właściwość 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Reprezentuje właściwość 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Reprezentuje właściwość 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Reprezentuje właściwość 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Reprezentuje właściwość 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Reprezentuje właściwość 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Reprezentuje właściwość 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Reprezentuje właściwość 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Reprezentuje właściwość 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Reprezentuje właściwość 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Reprezentuje właściwość 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Reprezentuje właściwość 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Reprezentuje właściwość 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Reprezentuje właściwość 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Reprezentuje właściwość 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Reprezentuje właściwość 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Reprezentuje właściwość 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Reprezentuje właściwość 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Reprezentuje właściwość 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Reprezentuje właściwość 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Reprezentuje właściwość 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Reprezentuje właściwość 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Reprezentuje właściwość 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Reprezentuje właściwość 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Reprezentuje właściwość 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Reprezentuje właściwość 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Reprezentuje właściwość 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Reprezentuje właściwość 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Reprezentuje właściwość 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Reprezentuje właściwość 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Reprezentuje właściwość 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Reprezentuje właściwość 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Reprezentuje właściwość 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Reprezentuje właściwość 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Reprezentuje właściwość 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Reprezentuje właściwość 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Reprezentuje właściwość 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Reprezentuje właściwość 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Reprezentuje właściwość 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Reprezentuje właściwość 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Reprezentuje właściwość 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Reprezentuje właściwość 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Reprezentuje właściwość 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Reprezentuje właściwość 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Reprezentuje właściwość 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Reprezentuje właściwość 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Reprezentuje właściwość 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Reprezentuje właściwość 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Reprezentuje właściwość 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Reprezentuje właściwość 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Reprezentuje właściwość 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Sprawdza, czy ten obiekt jest równy innemu. |
| [hashCode()](#hashCode--) | Oblicza i zwraca kod hash na podstawie właściwości (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Szuka istniejącej właściwości zachowania po wartości lub tworzy nową niestandardową o podanej wartości |

### getValue() {#getValue--}
```
public final String getValue()
```

Wartość właściwości

**Zwraca:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Pokazuje, czy ta właściwość nie należy do listy wstępnie zdefiniowanych właściwości w specyfikacji: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Zwraca:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Reprezentuje właściwość 'ppt\_x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Reprezentuje właściwość 'ppt\_y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Reprezentuje właściwość 'ppt\_w'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Reprezentuje właściwość 'ppt\_h'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Reprezentuje właściwość 'ppt\_c'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Reprezentuje właściwość 'ppt\_r'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Reprezentuje właściwość 'xshear'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Reprezentuje właściwość 'yshear'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Reprezentuje właściwość 'image'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Reprezentuje właściwość 'ScaleX'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Reprezentuje właściwość 'ScaleY'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Reprezentuje właściwość 'r'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Reprezentuje właściwość 'fillcolor'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Reprezentuje właściwość 'style.opacity'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Reprezentuje właściwość 'style.rotation'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Reprezentuje właściwość 'style.visibility'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Reprezentuje właściwość 'style.color'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Reprezentuje właściwość 'style.fontSize'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Reprezentuje właściwość 'style.fontWeight'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Reprezentuje właściwość 'style.fontStyle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Reprezentuje właściwość 'style.fontFamily'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Reprezentuje właściwość 'style.textEffectEmboss'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Reprezentuje właściwość 'style.textShadow'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Reprezentuje właściwość 'style.textTransform'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Reprezentuje właściwość 'style.textDecorationUnderline'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Reprezentuje właściwość 'style.textEffectOutline'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Reprezentuje właściwość 'style.textDecorationLineThrough'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Reprezentuje właściwość 'style.sRotation'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Reprezentuje właściwość 'imageData.cropTop'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Reprezentuje właściwość 'imageData.cropBottom'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Reprezentuje właściwość 'imageData.cropLeft'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Reprezentuje właściwość 'imageData.cropRight'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Reprezentuje właściwość 'imageData.gain'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Reprezentuje właściwość 'imageData.blacklevel'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Reprezentuje właściwość 'imageData.gamma'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Reprezentuje właściwość 'imageData.grayscale'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Reprezentuje właściwość 'imageData.chromakey'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Reprezentuje właściwość 'fill.on'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Reprezentuje właściwość 'fill.type'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Reprezentuje właściwość 'fill.color'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Reprezentuje właściwość 'fill.opacity'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Reprezentuje właściwość 'fill.color2'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Reprezentuje właściwość 'fill.method'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Reprezentuje właściwość 'fill.opacity2'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Reprezentuje właściwość 'fill.angle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Reprezentuje właściwość 'fill.focus'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Reprezentuje właściwość 'fill.focusposition.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Reprezentuje właściwość 'fill.focusposition.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Reprezentuje właściwość 'fill.focussize.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Reprezentuje właściwość 'fill.focussize.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Reprezentuje właściwość 'stroke.on'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Reprezentuje właściwość 'stroke.color'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Reprezentuje właściwość 'stroke.weight'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Reprezentuje właściwość 'stroke.opacity'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Reprezentuje właściwość 'stroke.linestyle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Reprezentuje właściwość 'stroke.dashstyle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Reprezentuje właściwość 'stroke.filltype'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Reprezentuje właściwość 'stroke.src'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Reprezentuje właściwość 'stroke.color2'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Reprezentuje właściwość 'stroke.imagesize.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Reprezentuje właściwość 'stroke.imagesize.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Reprezentuje właściwość 'stroke.startArrow'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Reprezentuje właściwość 'stroke.endArrow'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Reprezentuje właściwość 'stroke.startArrowWidth'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Reprezentuje właściwość 'stroke.startArrowLength'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Reprezentuje właściwość 'stroke.endArrowWidth'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Reprezentuje właściwość 'stroke.endArrowLength'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Reprezentuje właściwość 'shadow.on'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Reprezentuje właściwość 'shadow.type'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Reprezentuje właściwość 'shadow.color'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Reprezentuje właściwość 'shadow.color2'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Reprezentuje właściwość 'shadow.opacity'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Reprezentuje właściwość 'shadow.offset.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Reprezentuje właściwość 'shadow.offset.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Reprezentuje właściwość 'shadow.offset2.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Reprezentuje właściwość 'shadow.offset2.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Reprezentuje właściwość 'shadow.origin.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Reprezentuje właściwość 'shadow.origin.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Reprezentuje właściwość 'shadow.matrix.xtox'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Reprezentuje właściwość 'shadow.matrix.xtoy'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Reprezentuje właściwość 'shadow.matrix.ytox'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Reprezentuje właściwość 'shadow.matrix.ytoy'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Reprezentuje właściwość 'shadow.matrix.perspectiveX'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Reprezentuje właściwość 'shadow.matrix.perspectiveY'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Reprezentuje właściwość 'skew.on'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Reprezentuje właściwość 'skew.offset.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Reprezentuje właściwość 'skew.offset.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Reprezentuje właściwość 'skew.origin.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Reprezentuje właściwość 'skew.origin.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Reprezentuje właściwość 'skew.matrix.xtox'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Reprezentuje właściwość 'skew.matrix.xtoy'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Reprezentuje właściwość 'skew.matrix.ytox'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Reprezentuje właściwość 'skew.matrix.ytoy'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Reprezentuje właściwość 'skew.matrix.perspectiveX'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Reprezentuje właściwość 'skew.matrix.perspectiveY'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Reprezentuje właściwość 'extrusion.on'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Reprezentuje właściwość 'extrusion.type'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Reprezentuje właściwość 'extrusion.render'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Reprezentuje właściwość 'extrusion.viewpointorigin.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Reprezentuje właściwość 'extrusion.viewpointorigin.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Reprezentuje właściwość 'extrusion.viewpoint.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Reprezentuje właściwość 'extrusion.viewpoint.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Reprezentuje właściwość 'extrusion.viewpoint.z'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```java
public static BehaviorProperty getExtrusionPlane()
```

Reprezentuje właściwość 'extrusion.plane'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Reprezentuje właściwość 'extrusion.skewangle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Reprezentuje właściwość 'extrusion.skewamt'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Reprezentuje właściwość 'extrusion.backdepth'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Reprezentuje właściwość 'extrusion.foredepth'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Reprezentuje właściwość 'extrusion.orientation.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Reprezentuje właściwość 'extrusion.orientation.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Reprezentuje właściwość 'extrusion.orientation.z'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Reprezentuje właściwość 'extrusion.orientationangle'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Reprezentuje właściwość 'extrusion.color'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Reprezentuje właściwość 'extrusion.rotationangle.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Reprezentuje właściwość 'extrusion.rotationangle.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Reprezentuje właściwość 'extrusion.lockrotationcenter'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Reprezentuje właściwość 'extrusion.autorotationcenter'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Reprezentuje właściwość 'extrusion.rotationcenter.x'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Reprezentuje właściwość 'extrusion.rotationcenter.y'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Reprezentuje właściwość 'extrusion.rotationcenter.z'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Reprezentuje właściwość 'extrusion.colormode'

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Sprawdza, czy ten obiekt jest równy innemu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt do porównania. |

**Zwraca:**
boolean - Prawda, jeśli obiekty są równe.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Oblicza i zwraca kod hash na podstawie właściwości (\#getValue.getValue)

**Zwraca:**
int - Zwraca kod hash dla tego obiektu

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Szuka istniejącej właściwości zachowania po wartości lub tworzy nową niestandardową o podanej wartości

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| propertyValue | java.lang.String | wartość właściwości |

**Zwraca:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instancja BehaviorProperty