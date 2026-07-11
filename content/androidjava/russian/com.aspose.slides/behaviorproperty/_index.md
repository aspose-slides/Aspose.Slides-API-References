---
title: BehaviorProperty
second_title: Aspose.Slides для Android через справочник Java API
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

Представляет типы свойств для поведения анимации. Следует списку свойств с https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx и https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Методы

| Метод | Описание |
| --- | --- |
| [getValue()](#getValue--) | Value of the property |
| [isCustom()](#isCustom--) | Shows if this property does not belong to the predefined properties list in the specification: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Represents 'ppt\_x' property |
| [getPptY()](#getPptY--) | Represents 'ppt\_y' property |
| [getPptW()](#getPptW--) | Represents 'ppt\_w' property |
| [getPptH()](#getPptH--) | Represents 'ppt\_h' property |
| [getPptC()](#getPptC--) | Represents 'ppt\_c' property |
| [getPptR()](#getPptR--) | Represents 'ppt\_r' property |
| [getXShear()](#getXShear--) | Represents 'xshear' property |
| [getYShear()](#getYShear--) | Represents 'yshear' property |
| [getImage()](#getImage--) | Represents 'image' property |
| [getScaleX()](#getScaleX--) | Represents 'ScaleX' property |
| [getScaleY()](#getScaleY--) | Represents 'ScaleY' property |
| [getR()](#getR--) | Represents 'r' property |
| [getFillColor()](#getFillColor--) | Represents 'fillcolor' property |
| [getStyleOpacity()](#getStyleOpacity--) | Represents 'style.opacity' property |
| [getStyleRotation()](#getStyleRotation--) | Represents 'style.rotation' property |
| [getStyleVisibility()](#getStyleVisibility--) | Represents 'style.visibility' property |
| [getStyleColor()](#getStyleColor--) | Represents 'style.color' property |
| [getStyleFontSize()](#getStyleFontSize--) | Represents 'style.fontSize' property |
| [getStyleFontWeight()](#getStyleFontWeight--) | Represents 'style.fontWeight' property |
| [getStyleFontStyle()](#getStyleFontStyle--) | Represents 'style.fontStyle' property |
| [getStyleFontFamily()](#getStyleFontFamily--) | Represents 'style.fontFamily' property |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Represents 'style.textEffectEmboss' property |
| [getStyleTextShadow()](#getStyleTextShadow--) | Represents 'style.textShadow' property |
| [getStyleTextTransform()](#getStyleTextTransform--) | Represents 'style.textTransform' property |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Represents 'style.textDecorationUnderline' property |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Represents 'style.textEffectOutline' property |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Represents 'style.textDecorationLineThrough' property |
| [getStyleSRotation()](#getStyleSRotation--) | Represents 'style.sRotation' property |
| [getImageDataCropTop()](#getImageDataCropTop--) | Represents 'imageData.cropTop' property |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Represents 'imageData.cropBottom' property |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Represents 'imageData.cropLeft' property |
| [getImageDataCropRight()](#getImageDataCropRight--) | Represents 'imageData.cropRight' property |
| [getImageDataGain()](#getImageDataGain--) | Represents 'imageData.gain' property |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Represents 'imageData.blacklevel' property |
| [getImageDataGamma()](#getImageDataGamma--) | Represents 'imageData.gamma' property |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Represents 'imageData.grayscale' property |
| [getImageDataChromakey()](#getImageDataChromakey--) | Represents 'imageData.chromakey' property |
| [getFillOn()](#getFillOn--) | Represents 'fill.on' property |
| [getFillType()](#getFillType--) | Represents 'fill.type' property |
| [getFill_Color()](#getFill-Color--) | Represents 'fill.color' property |
| [getFillOpacity()](#getFillOpacity--) | Represents 'fill.opacity' property |
| [getFillColor2()](#getFillColor2--) | Represents 'fill.color2' property |
| [getFillMethod()](#getFillMethod--) | Represents 'fill.method' property |
| [getFillOpacity2()](#getFillOpacity2--) | Represents 'fill.opacity2' property |
| [getFillAngle()](#getFillAngle--) | Represents 'fill.angle' property |
| [getFillFocus()](#getFillFocus--) | Represents 'fill.focus' property |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Represents 'fill.focusposition.x' property |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Represents 'fill.focusposition.y' property |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Represents 'fill.focussize.x' property |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Represents 'fill.focussize.y' property |
| [getStrokeOn()](#getStrokeOn--) | Represents 'stroke.on' property |
| [getStrokeColor()](#getStrokeColor--) | Represents 'stroke.color' property |
| [getStrokeWeight()](#getStrokeWeight--) | Represents 'stroke.weight' property |
| [getStrokeOpacity()](#getStrokeOpacity--) | Represents 'stroke.opacity' property |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Represents 'stroke.linestyle' property |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Represents 'stroke.dashstyle' property |
| [getStrokeFillType()](#getStrokeFillType--) | Represents 'stroke.filltype' property |
| [getStrokeSrc()](#getStrokeSrc--) | Represents 'stroke.src' property |
| [getStrokeColor2()](#getStrokeColor2--) | Represents 'stroke.color2' property |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Represents 'stroke.imagesize.x' property |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Represents 'stroke.imagesize.y' property |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Represents 'stroke.startArrow' property |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Represents 'stroke.endArrow' property |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Represents 'stroke.startArrowWidth' property |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Represents 'stroke.startArrowLength' property |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Represents 'stroke.endArrowWidth' property |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Represents 'stroke.endArrowLength' property |
| [getShadowOn()](#getShadowOn--) | Represents 'shadow.on' property |
| [getShadowType()](#getShadowType--) | Represents 'shadow.type' property |
| [getShadowColor()](#getShadowColor--) | Represents 'shadow.color' property |
| [getShadowColor2()](#getShadowColor2--) | Represents 'shadow.color2' property |
| [getShadowOpacity()](#getShadowOpacity--) | Represents 'shadow.opacity' property |
| [getShadowOffsetX()](#getShadowOffsetX--) | Represents 'shadow.offset.x' property |
| [getShadowOffsetY()](#getShadowOffsetY--) | Represents 'shadow.offset.y' property |
| [getShadowOffset2X()](#getShadowOffset2X--) | Represents 'shadow.offset2.x' property |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Represents 'shadow.offset2.y' property |
| [getShadowOriginX()](#getShadowOriginX--) | Represents 'shadow.origin.x' property |
| [getShadowOriginY()](#getShadowOriginY--) | Represents 'shadow.origin.y' property |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Represents 'shadow.matrix.xtox' property |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Represents 'shadow.matrix.xtoy' property |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Represents 'shadow.matrix.ytox' property |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Represents 'shadow.matrix.ytoy' property |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Represents 'shadow.matrix.perspectiveX' property |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Represents 'shadow.matrix.perspectiveY' property |
| [getSkewOn()](#getSkewOn--) | Represents 'skew.on' property |
| [getSkewOffsetX()](#getSkewOffsetX--) | Represents 'skew.offset.x' property |
| [getSkewOffsetY()](#getSkewOffsetY--) | Represents 'skew.offset.y' property |
| [getSkewOriginX()](#getSkewOriginX--) | Represents 'skew.origin.x' property |
| [getSkewOriginY()](#getSkewOriginY--) | Represents 'skew.origin.y' property |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Represents 'skew.matrix.xtox' property |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Represents 'skew.matrix.xtoy' property |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Represents 'skew.matrix.ytox' property |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Represents 'skew.matrix.ytoy' property |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Represents 'skew.matrix.perspectiveX' property |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Represents 'skew.matrix.perspectiveY' property |
| [getExtrusionOn()](#getExtrusionOn--) | Represents 'extrusion.on' property |
| [getExtrusionType()](#getExtrusionType--) | Represents 'extrusion.type' property |
| [getExtrusionRender()](#getExtrusionRender--) | Represents 'extrusion.render' property |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Represents 'extrusion.viewpointorigin.x' property |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Represents 'extrusion.viewpointorigin.y' property |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Represents 'extrusion.viewpoint.x' property |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Represents 'extrusion.viewpoint.y' property |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Represents 'extrusion.viewpoint.z' property |
| [getExtrusionPlane()](#getExtrusionPlane--) | Represents 'extrusion.plane' property |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Represents 'extrusion.skewangle' property |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Represents 'extrusion.skewamt' property |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Represents 'extrusion.backdepth' property |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Represents 'extrusion.foredepth' property |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Represents 'extrusion.orientation.x' property |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Represents 'extrusion.orientation.y' property |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Represents 'extrusion.orientation.z' property |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Represents 'extrusion.orientationangle' property |
| [getExtrusionColor()](#getExtrusionColor--) | Represents 'extrusion.color' property |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Represents 'extrusion.rotationangle.x' property |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Represents 'extrusion.rotationangle.y' property |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Represents 'extrusion.lockrotationcenter' property |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Represents 'extrusion.autorotationcenter' property |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Represents 'extrusion.rotationcenter.x' property |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Represents 'extrusion.rotationcenter.y' property |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Represents 'extrusion.rotationcenter.z' property |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Represents 'extrusion.colormode' property |
| [equals(Object obj)](#equals-java.lang.Object-) | Checks if this object is equal to another. |
| [hashCode()](#hashCode--) | Calculates and returns hach code based on the (\#getValue.getValue) property |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Looks for existing behavior property by value or creates new custom one with the specified value |

### getValue() {#getValue--}
```
public final String getValue()
```

Значение свойства

**Возвращаемое значение:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Показывает, не относится ли это свойство к предопределенному списку свойств в спецификации: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Возвращаемое значение:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Represents 'ppt\_x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Represents 'ppt\_y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Represents 'ppt\_w' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Represents 'ppt\_h' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Represents 'ppt\_c' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Represents 'ppt\_r' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Represents 'xshear' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Represents 'yshear' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Represents 'image' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Represents 'ScaleX' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Represents 'ScaleY' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Represents 'r' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Represents 'fillcolor' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Represents 'style.opacity' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Represents 'style.rotation' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Represents 'style.visibility' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Represents 'style.color' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Represents 'style.fontSize' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Represents 'style.fontWeight' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Represents 'style.fontStyle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Represents 'style.fontFamily' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Represents 'style.textEffectEmboss' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Represents 'style.textShadow' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Represents 'style.textTransform' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Represents 'style.textDecorationUnderline' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Represents 'style.textEffectOutline' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Represents 'style.textDecorationLineThrough' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Represents 'style.sRotation' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Represents 'imageData.cropTop' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Represents 'imageData.cropBottom' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Represents 'imageData.cropLeft' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Represents 'imageData.cropRight' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Represents 'imageData.gain' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Represents 'imageData.blacklevel' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Represents 'imageData.gamma' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Represents 'imageData.grayscale' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Represents 'imageData.chromakey' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```java
public static BehaviorProperty getFillOn()
```

Represents 'fill.on' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Represents 'fill.type' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Represents 'fill.color' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Represents 'fill.opacity' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Represents 'fill.color2' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Represents 'fill.method' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Represents 'fill.opacity2' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Represents 'fill.angle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Represents 'fill.focus' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Represents 'fill.focusposition.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Represents 'fill.focusposition.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Represents 'fill.focussize.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Represents 'fill.focussize.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Represents 'stroke.on' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Represents 'stroke.color' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Represents 'stroke.weight' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Represents 'stroke.opacity' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Represents 'stroke.linestyle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Represents 'stroke.dashstyle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Represents 'stroke.filltype' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Represents 'stroke.src' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Represents 'stroke.color2' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Represents 'stroke.imagesize.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public



```

Represents 'stroke.imagesize.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Represents 'stroke.startArrow' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Represents 'stroke.endArrow' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Represents 'stroke.startArrowWidth' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Represents 'stroke.startArrowLength' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Represents 'stroke.endArrowWidth' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Represents 'stroke.endArrowLength' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Represents 'shadow.on' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Represents 'shadow.type' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Represents 'shadow.color' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Represents 'shadow.color2' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Represents 'shadow.opacity' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Represents 'shadow.offset.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Represents 'shadow.offset.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Represents 'shadow.offset2.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Represents 'shadow.offset2.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Represents 'shadow.origin.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Represents 'shadow.origin.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Represents 'shadow.matrix.xtox' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Represents 'shadow.matrix.xtoy' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public



```

Represents 'shadow.matrix.ytox' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Represents 'shadow.matrix.ytoy' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Represents 'shadow.matrix.perspectiveX' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Represents 'shadow.matrix.perspectiveY' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Represents 'skew.on' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Represents 'skew.offset.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Represents 'skew.offset.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Represents 'skew.origin.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Represents 'skew.origin.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Represents 'skew.matrix.xtox' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Represents 'skew.matrix.xtoy' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Represents 'skew.matrix.ytox' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Represents 'skew.matrix.ytoy' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Represents 'skew.matrix.perspectiveX' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Represents 'skew.matrix.perspectiveY' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Represents 'extrusion.on' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Represents 'extrusion.type' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Represents 'extrusion.render' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Represents 'extrusion.viewpointorigin.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Represents 'extrusion.viewpointorigin.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Represents 'extrusion.viewpoint.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Represents 'extrusion.viewpoint.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Represents 'extrusion.viewpoint.z' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Represents 'extrusion.plane' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Represents 'extrusion.skewangle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Represents 'extrusion.skewamt' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Represents 'extrusion.backdepth' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Represents 'extrusion.foredepth' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Represents 'extrusion.orientation.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Represents 'extrusion.orientation.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Represents 'extrusion.orientation.z' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Represents 'extrusion.orientationangle' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Represents 'extrusion.color' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Represents 'extrusion.rotationangle.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Represents 'extrusion.rotationangle.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Represents 'extrusion.lockrotationcenter' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Represents 'extrusion.autorotationcenter' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Represents 'extrusion.rotationcenter.x' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Represents 'extrusion.rotationcenter.y' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Represents 'extrusion.rotationcenter.z' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Represents 'extrusion.colormode' property

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Проверяет, равен ли этот объект другому.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Object to compare. |

**Возвращаемое значение:**
boolean - True if objects are equal.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Вычисляет и возвращает хеш-код на основе свойства (\#getValue.getValue)

**Возвращаемое значение:**
int - Returns hash code for this object

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Ищет существующее свойство поведения по значению или создает новое пользовательское со заданным значением

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| propertyValue | java.lang.String | value of the property |

**Возвращаемое значение:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance of BehaviorProperty