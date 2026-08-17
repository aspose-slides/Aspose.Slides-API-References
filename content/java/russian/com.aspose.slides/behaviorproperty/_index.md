---
title: BehaviorProperty
second_title: Справочник API Aspose.Slides для Java
description: Представляет типы свойств для поведения анимации.
type: docs
url: /ru/com.aspose.slides/behaviorproperty/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Представляет типы свойств для поведения анимации. Следует список свойств из https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx и https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Значение свойства |
| [isCustom()](#isCustom--) | Показывает, относится ли это свойство к списку предопределённых свойств в спецификации: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Представляет свойство 'ppt\_x' |
| [getPptY()](#getPptY--) | Представляет свойство 'ppt\_y' |
| [getPptW()](#getPptW--) | Представляет свойство 'ppt\_w' |
| [getPptH()](#getPptH--) | Представляет свойство 'ppt\_h' |
| [getPptC()](#getPptC--) | Представляет свойство 'ppt\_c' |
| [getPptR()](#getPptR--) | Представляет свойство 'ppt\_r' |
| [getXShear()](#getXShear--) | Представляет свойство 'xshear' |
| [getYShear()](#getYShear--) | Представляет свойство 'yshear' |
| [getImage()](#getImage--) | Представляет свойство 'image' |
| [getScaleX()](#getScaleX--) | Представляет свойство 'ScaleX' |
| [getScaleY()](#getScaleY--) | Представляет свойство 'ScaleY' |
| [getR()](#getR--) | Представляет свойство 'r' |
| [getFillColor()](#getFillColor--) | Представляет свойство 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Представляет свойство 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Представляет свойство 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Представляет свойство 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Представляет свойство 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Представляет свойство 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Представляет свойство 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Представляет свойство 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Представляет свойство 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Представляет свойство 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Представляет свойство 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Представляет свойство 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Представляет свойство 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Представляет свойство 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Представляет свойство 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Представляет свойство 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Представляет свойство 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Представляет свойство 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Представляет свойство 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Представляет свойство 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Представляет свойство 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Представляет свойство 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Представляет свойство 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Представляет свойство 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Представляет свойство 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Представляет свойство 'fill.on' |
| [getFillType()](#getFillType--) | Представляет свойство 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Представляет свойство 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Представляет свойство 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Представляет свойство 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Представляет свойство 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Представляет свойство 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Представляет свойство 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Представляет свойство 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Представляет свойство 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Представляет свойство 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Представляет свойство 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Представляет свойство 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Представляет свойство 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Представляет свойство 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Представляет свойство 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Представляет свойство 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Представляет свойство 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Представляет свойство 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Представляет свойство 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Представляет свойство 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Представляет свойство 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Представляет свойство 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Представляет свойство 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Представляет свойство 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Представляет свойство 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Представляет свойство 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Представляет свойство 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Представляет свойство 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Представляет свойство 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Представляет свойство 'shadow.on' |
| [getShadowType()](#getShadowType--) | Представляет свойство 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Представляет свойство 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Представляет свойство 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Представляет свойство 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Представляет свойство 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Представляет свойство 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Представляет свойство 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Представляет свойство 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Представляет свойство 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Представляет свойство 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Представляет свойство 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Представляет свойство 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Представляет свойство 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Представляет свойство 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Представляет свойство 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Представляет свойство 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Представляет свойство 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Представляет свойство 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Представляет свойство 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Представляет свойство 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Представляет свойство 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Представляет свойство 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Представляет свойство 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Представляет свойство 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Представляет свойство 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Представляет свойство 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Представляет свойство 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Представляет свойство 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Представляет свойство 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Представляет свойство 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Представляет свойство 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Представляет свойство 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Представляет свойство 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Представляет свойство 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Представляет свойство 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Представляет свойство 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Представляет свойство 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Представляет свойство 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Представляет свойство 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Представляет свойство 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Представляет свойство 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Представляет свойство 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Представляет свойство 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Представляет свойство 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Представляет свойство 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Представляет свойство 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Представляет свойство 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Представляет свойство 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Представляет свойство 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Представляет свойство 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Представляет свойство 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Представляет свойство 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Представляет свойство 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, равен ли этот объект другому. |
| [hashCode()](#hashCode--) | Вычисляет и возвращает hach-code на основе свойства (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Ищет существующее свойство поведения по значению или создаёт новое пользовательское со указанным значением |

### getValue() {#getValue--}
```
public final String getValue()
```

Значение свойства

**Возвращает:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Показывает, относится ли это свойство к списку предопределённых свойств в спецификации: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Возвращает:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Представляет свойство 'ppt\_x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Представляет свойство 'ppt\_y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Представляет свойство 'ppt\_w'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Представляет свойство 'ppt\_h'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Представляет свойство 'ppt\_c'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Представляет свойство 'ppt\_r'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Представляет свойство 'xshear'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Представляет свойство 'yshear'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Представляет свойство 'image'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Представляет свойство 'ScaleX'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Представляет свойство 'ScaleY'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Представляет свойство 'r'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Представляет свойство 'fillcolor'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Представляет свойство 'style.opacity'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Представляет свойство 'style.rotation'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Представляет свойство 'style.visibility'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Представляет свойство 'style.color'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Представляет свойство 'style.fontSize'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Представляет свойство 'style.fontWeight'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Представляет свойство 'style.fontStyle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Представляет свойство 'style.fontFamily'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Представляет свойство 'style.textEffectEmboss'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Представляет свойство 'style.textShadow'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Представляет свойство 'style.textTransform'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Представляет свойство 'style.textDecorationUnderline'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Представляет свойство 'style.textEffectOutline'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Представляет свойство 'style.textDecorationLineThrough'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Представляет свойство 'style.sRotation'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Представляет свойство 'imageData.cropTop'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Представляет свойство 'imageData.cropBottom'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Представляет свойство 'imageData.cropLeft'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Представляет свойство 'imageData.cropRight'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Представляет свойство 'imageData.gain'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Представляет свойство 'imageData.blacklevel'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Представляет свойство 'imageData.gamma'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


Представляет свойство 'imageData.grayscale'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


Представляет свойство 'imageData.chromakey'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


Представляет свойство 'fill.on'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


Представляет свойство 'fill.type'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


Представляет свойство 'fill.color'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


Представляет свойство 'fill.opacity'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


Представляет свойство 'fill.color2'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


Представляет свойство 'fill.method'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


Представляет свойство 'fill.opacity2'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


Представляет свойство 'fill.angle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


Представляет свойство 'fill.focus'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


Представляет свойство 'fill.focusposition.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


Представляет свойство 'fill.focusposition.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


Представляет свойство 'fill.focussize.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


Представляет свойство 'fill.focussize.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


Представляет свойство 'stroke.on'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


Представляет свойство 'stroke.color'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


Представляет свойство 'stroke.weight'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


Представляет свойство 'stroke.opacity'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


Представляет свойство 'stroke.linestyle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


Представляет свойство 'stroke.dashstyle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


Представляет свойство 'stroke.filltype'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


Представляет свойство 'stroke.src'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


Представляет свойство 'stroke.color2'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


Представляет свойство 'stroke.imagesize.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


Представляет свойство 'stroke.imagesize.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


Представляет свойство 'stroke.startArrow'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


Представляет свойство 'stroke.endArrow'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


Представляет свойство 'stroke.startArrowWidth'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


Представляет свойство 'stroke.startArrowLength'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


Представляет свойство 'stroke.endArrowWidth'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


Представляет свойство 'stroke.endArrowLength'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


Представляет свойство 'shadow.on'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


Представляет свойство 'shadow.type'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


Представляет свойство 'shadow.color'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


Представляет свойство 'shadow.color2'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


Представляет свойство 'shadow.opacity'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


Представляет свойство 'shadow.offset.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


Представляет свойство 'shadow.offset.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


Представляет свойство 'shadow.offset2.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


Представляет свойство 'shadow.offset2.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


Представляет свойство 'shadow.origin.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


Представляет свойство 'shadow.origin.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Представляет свойство 'shadow.matrix.xtox'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


Представляет свойство 'shadow.matrix.xtoy'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


Представляет свойство 'shadow.matrix.ytox'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


Представляет свойство 'shadow.matrix.ytoy'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


Представляет свойство 'shadow.matrix.perspectiveX'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


Представляет свойство 'shadow.matrix.perspectiveY'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


Представляет свойство 'skew.on'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


Представляет свойство 'skew.offset.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


Представляет свойство 'skew.offset.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


Представляет свойство 'skew.origin.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


Представляет свойство 'skew.origin.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


Представляет свойство 'skew.matrix.xtox'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


Представляет свойство 'skew.matrix.xtoy'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


Представляет свойство 'skew.matrix.ytox'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


Представляет свойство 'skew.matrix.ytoy'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


Представляет свойство 'skew.matrix.perspectiveX'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


Представляет свойство 'skew.matrix.perspectiveY'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


Представляет свойство 'extrusion.on'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


Представляет свойство 'extrusion.type'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


Представляет свойство 'extrusion.render'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


Представляет свойство 'extrusion.viewpointorigin.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


Представляет свойство 'extrusion.viewpointorigin.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


Представляет свойство 'extrusion.viewpoint.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


Представляет свойство 'extrusion.viewpoint.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


Представляет свойство 'extrusion.viewpoint.z'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


Представляет свойство 'extrusion.plane'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


Представляет свойство 'extrusion.skewangle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


Представляет свойство 'extrusion.skewamt'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


Представляет свойство 'extrusion.backdepth'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


Представляет свойство 'extrusion.foredepth'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


Представляет свойство 'extrusion.orientation.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


Представляет свойство 'extrusion.orientation.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


Представляет свойство 'extrusion.orientation.z'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


Представляет свойство 'extrusion.orientationangle'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


Представляет свойство 'extrusion.color'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


Представляет свойство 'extrusion.rotationangle.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


Представляет свойство 'extrusion.rotationangle.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


Представляет свойство 'extrusion.lockrotationcenter'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


Представляет свойство 'extrusion.autorotationcenter'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


Представляет свойство 'extrusion.rotationcenter.x'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


Представляет свойство 'extrusion.rotationcenter.y'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


Представляет свойство 'extrusion.rotationcenter.z'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


Представляет свойство 'extrusion.colormode'

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, равен ли этот объект другому.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения. |

**Возвращает:**
boolean - true, если объекты равны.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет и возвращает hach code на основе свойства (\#getValue.getValue)

**Возвращает:**
int - Возвращает хеш-код для этого объекта
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


Ищет существующее свойство поведения по значению или создает новое пользовательское со указанным значением

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | значение свойства |

**Возвращает:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - экземпляр BehaviorProperty