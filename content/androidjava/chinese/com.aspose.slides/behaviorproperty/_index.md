---
title: BehaviorProperty
second_title: Aspose.Slides Android 通过 Java API 参考
description: 表示动画行为的属性类型。
type: docs
url: /zh/com.aspose.slides/behaviorproperty/
---
**继承：**
java.lang.Object

**实现的所有接口：**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

表示动画行为的属性类型。遵循来自 https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 和 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx 的属性列表。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getValue()](#getValue--) | 属性的值 |
| [isCustom()](#isCustom--) | 显示该属性是否不属于规范中预定义属性列表：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | 表示 'ppt_x' 属性 |
| [getPptY()](#getPptY--) | 表示 'ppt_y' 属性 |
| [getPptW()](#getPptW--) | 表示 'ppt_w' 属性 |
| [getPptH()](#getPptH--) | 表示 'ppt_h' 属性 |
| [getPptC()](#getPptC--) | 表示 'ppt_c' 属性 |
| [getPptR()](#getPptR--) | 表示 'ppt_r' 属性 |
| [getXShear()](#getXShear--) | 表示 'xshear' 属性 |
| [getYShear()](#getYShear--) | 表示 'yshear' 属性 |
| [getImage()](#getImage--) | 表示 'image' 属性 |
| [getScaleX()](#getScaleX--) | 表示 'ScaleX' 属性 |
| [getScaleY()](#getScaleY--) | 表示 'ScaleY' 属性 |
| [getR()](#getR--) | 表示 'r' 属性 |
| [getFillColor()](#getFillColor--) | 表示 'fillcolor' 属性 |
| [getStyleOpacity()](#getStyleOpacity--) | 表示 'style.opacity' 属性 |
| [getStyleRotation()](#getStyleRotation--) | 表示 'style.rotation' 属性 |
| [getStyleVisibility()](#getStyleVisibility--) | 表示 'style.visibility' 属性 |
| [getStyleColor()](#getStyleColor--) | 表示 'style.color' 属性 |
| [getStyleFontSize()](#getStyleFontSize--) | 表示 'style.fontSize' 属性 |
| [getStyleFontWeight()](#getStyleFontWeight--) | 表示 'style.fontWeight' 属性 |
| [getStyleFontStyle()](#getStyleFontStyle--) | 表示 'style.fontStyle' 属性 |
| [getStyleFontFamily()](#getStyleFontFamily--) | 表示 'style.fontFamily' 属性 |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | 表示 'style.textEffectEmboss' 属性 |
| [getStyleTextShadow()](#getStyleTextShadow--) | 表示 'style.textShadow' 属性 |
| [getStyleTextTransform()](#getStyleTextTransform--) | 表示 'style.textTransform' 属性 |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | 表示 'style.textDecorationUnderline' 属性 |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | 表示 'style.textEffectOutline' 属性 |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | 表示 'style.textDecorationLineThrough' 属性 |
| [getStyleSRotation()](#getStyleSRotation--) | 表示 'style.sRotation' 属性 |
| [getImageDataCropTop()](#getImageDataCropTop--) | 表示 'imageData.cropTop' 属性 |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | 表示 'imageData.cropBottom' 属性 |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | 表示 'imageData.cropLeft' 属性 |
| [getImageDataCropRight()](#getImageDataCropRight--) | 表示 'imageData.cropRight' 属性 |
| [getImageDataGain()](#getImageDataGain--) | 表示 'imageData.gain' 属性 |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | 表示 'imageData.blacklevel' 属性 |
| [getImageDataGamma()](#getImageDataGamma--) | 表示 'imageData.gamma' 属性 |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | 表示 'imageData.grayscale' 属性 |
| [getImageDataChromakey()](#getImageDataChromakey--) | 表示 'imageData.chromakey' 属性 |
| [getFillOn()](#getFillOn--) | 表示 'fill.on' 属性 |
| [getFillType()](#getFillType--) | 表示 'fill.type' 属性 |
| [getFill_Color()](#getFill-Color--) | 表示 'fill.color' 属性 |
| [getFillOpacity()](#getFillOpacity--) | 表示 'fill.opacity' 属性 |
| [getFillColor2()](#getFillColor2--) | 表示 'fill.color2' 属性 |
| [getFillMethod()](#getFillMethod--) | 表示 'fill.method' 属性 |
| [getFillOpacity2()](#getFillOpacity2--) | 表示 'fill.opacity2' 属性 |
| [getFillAngle()](#getFillAngle--) | 表示 'fill.angle' 属性 |
| [getFillFocus()](#getFillFocus--) | 表示 'fill.focus' 属性 |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | 表示 'fill.focusposition.x' 属性 |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | 表示 'fill.focusposition.y' 属性 |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | 表示 'fill.focussize.x' 属性 |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | 表示 'fill.focussize.y' 属性 |
| [getStrokeOn()](#getStrokeOn--) | 表示 'stroke.on' 属性 |
| [getStrokeColor()](#getStrokeColor--) | 表示 'stroke.color' 属性 |
| [getStrokeWeight()](#getStrokeWeight--) | 表示 'stroke.weight' 属性 |
| [getStrokeOpacity()](#getStrokeOpacity--) | 表示 'stroke.opacity' 属性 |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | 表示 'stroke.linestyle' 属性 |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | 表示 'stroke.dashstyle' 属性 |
| [getStrokeFillType()](#getStrokeFillType--) | 表示 'stroke.filltype' 属性 |
| [getStrokeSrc()](#getStrokeSrc--) | 表示 'stroke.src' 属性 |
| [getStrokeColor2()](#getStrokeColor2--) | 表示 'stroke.color2' 属性 |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | 表示 'stroke.imagesize.x' 属性 |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | 表示 'stroke.imagesize.y' 属性 |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | 表示 'stroke.startArrow' 属性 |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | 表示 'stroke.endArrow' 属性 |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | 表示 'stroke.startArrowWidth' 属性 |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | 表示 'stroke.startArrowLength' 属性 |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | 表示 'stroke.endArrowWidth' 属性 |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | 表示 'stroke.endArrowLength' 属性 |
| [getShadowOn()](#getShadowOn--) | 表示 'shadow.on' 属性 |
| [getShadowType()](#getShadowType--) | 表示 'shadow.type' 属性 |
| [getShadowColor()](#getShadowColor--) | 表示 'shadow.color' 属性 |
| [getShadowColor2()](#getShadowColor2--) | 表示 'shadow.color2' 属性 |
| [getShadowOpacity()](#getShadowOpacity--) | 表示 'shadow.opacity' 属性 |
| [getShadowOffsetX()](#getShadowOffsetX--) | 表示 'shadow.offset.x' 属性 |
| [getShadowOffsetY()](#getShadowOffsetY--) | 表示 'shadow.offset.y' 属性 |
| [getShadowOffset2X()](#getShadowOffset2X--) | 表示 'shadow.offset2.x' 属性 |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | 表示 'shadow.offset2.y' 属性 |
| [getShadowOriginX()](#getShadowOriginX--) | 表示 'shadow.origin.x' 属性 |
| [getShadowOriginY()](#getShadowOriginY--) | 表示 'shadow.origin.y' 属性 |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | 表示 'shadow.matrix.xtox' 属性 |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | 表示 'shadow.matrix.xtoy' 属性 |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | 表示 'shadow.matrix.ytox' 属性 |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | 表示 'shadow.matrix.ytoy' 属性 |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | 表示 'shadow.matrix.perspectiveX' 属性 |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | 表示 'shadow.matrix.perspectiveY' 属性 |
| [getSkewOn()](#getSkewOn--) | 表示 'skew.on' 属性 |
| [getSkewOffsetX()](#getSkewOffsetX--) | 表示 'skew.offset.x' 属性 |
| [getSkewOffsetY()](#getSkewOffsetY--) | 表示 'skew.offset.y' 属性 |
| [getSkewOriginX()](#getSkewOriginX--) | 表示 'skew.origin.x' 属性 |
| [getSkewOriginY()](#getSkewOriginY--) | 表示 'skew.origin.y' 属性 |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | 表示 'skew.matrix.xtox' 属性 |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | 表示 'skew.matrix.xtoy' 属性 |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | 表示 'skew.matrix.ytox' 属性 |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | 表示 'skew.matrix.ytoy' 属性 |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | 表示 'skew.matrix.perspectiveX' 属性 |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | 表示 'skew.matrix.perspectiveY' 属性 |
| [getExtrusionOn()](#getExtrusionOn--) | 表示 'extrusion.on' 属性 |
| [getExtrusionType()](#getExtrusionType--) | 表示 'extrusion.type' 属性 |
| [getExtrusionRender()](#getExtrusionRender--) | 表示 'extrusion.render' 属性 |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | 表示 'extrusion.viewpointorigin.x' 属性 |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | 表示 'extrusion.viewpointorigin.y' 属性 |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | 表示 'extrusion.viewpoint.x' 属性 |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | 表示 'extrusion.viewpoint.y' 属性 |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | 表示 'extrusion.viewpoint.z' 属性 |
| [getExtrusionPlane()](#getExtrusionPlane--) | 表示 'extrusion.plane' 属性 |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | 表示 'extrusion.skewangle' 属性 |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | 表示 'extrusion.skewamt' 属性 |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | 表示 'extrusion.backdepth' 属性 |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | 表示 'extrusion.foredepth' 属性 |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | 表示 'extrusion.orientation.x' 属性 |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | 表示 'extrusion.orientation.y' 属性 |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | 表示 'extrusion.orientation.z' 属性 |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | 表示 'extrusion.orientationangle' 属性 |
| [getExtrusionColor()](#getExtrusionColor--) | 表示 'extrusion.color' 属性 |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | 表示 'extrusion.rotationangle.x' 属性 |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | 表示 'extrusion.rotationangle.y' 属性 |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | 表示 'extrusion.lockrotationcenter' 属性 |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | 表示 'extrusion.autorotationcenter' 属性 |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | 表示 'extrusion.rotationcenter.x' 属性 |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | 表示 'extrusion.rotationcenter.y' 属性 |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | 表示 'extrusion.rotationcenter.z' 属性 |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | 表示 'extrusion.colormode' 属性 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查此对象是否等于另一个对象。 |
| [hashCode()](#hashCode--) | 基于 (\#getValue.getValue) 属性计算并返回哈希码 |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | 根据值查找现有行为属性，或使用指定的值创建新的自定义属性 |
### getValue() {#getValue--}
```
public final String getValue()
```


属性的值

**返回：**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


显示该属性是否不属于规范中预定义属性列表：https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**返回：**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```


表示 'ppt_x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```


表示 'ppt_y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```


表示 'ppt_w' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```


表示 'ppt_h' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```


表示 'ppt_c' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```


表示 'ppt_r' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```


表示 'xshear' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```


表示 'yshear' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```


表示 'image' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```


表示 'ScaleX' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```


表示 'ScaleY' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```


表示 'r' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```


表示 'fillcolor' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```


表示 'style.opacity' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```


表示 'style.rotation' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```


表示 'style.visibility' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```


表示 'style.color' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```


表示 'style.fontSize' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```


表示 'style.fontWeight' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```


表示 'style.fontStyle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```


表示 'style.fontFamily' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```


表示 'style.textEffectEmboss' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```


表示 'style.textShadow' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```


表示 'style.textTransform' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```


表示 'style.textDecorationUnderline' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```


表示 'style.textEffectOutline' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```


表示 'style.textDecorationLineThrough' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```


表示 'style.sRotation' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```


表示 'imageData.cropTop' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```


表示 'imageData.cropBottom' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```


表示 'imageData.cropLeft' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```


表示 'imageData.cropRight' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```


表示 'imageData.gain' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```


表示 'imageData.blacklevel' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```


表示 'imageData.gamma' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


表示 'imageData.grayscale' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


表示 'imageData.chromakey' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


表示 'fill.on' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


表示 'fill.type' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


表示 'fill.color' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


表示 'fill.opacity' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


表示 'fill.color2' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


表示 'fill.method' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


表示 'fill.opacity2' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


表示 'fill.angle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


表示 'fill.focus' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


表示 'fill.focusposition.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


表示 'fill.focusposition.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


表示 'fill.focussize.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


表示 'fill.focussize.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


表示 'stroke.on' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


表示 'stroke.color' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


表示 'stroke.weight' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


表示 'stroke.opacity' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


表示 'stroke.linestyle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


表示 'stroke.dashstyle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


表示 'stroke.filltype' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


表示 'stroke.src' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


表示 'stroke.color2' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


表示 'stroke.imagesize.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


表示 'stroke.imagesize.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


表示 'stroke.startArrow' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


表示 'stroke.endArrow' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


表示 'stroke.startArrowWidth' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


表示 'stroke.startArrowLength' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


表示 'stroke.endArrowWidth' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


表示 'stroke.endArrowLength' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


表示 'shadow.on' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


表示 'shadow.type' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


表示 'shadow.color' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


表示 'shadow.color2' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


表示 'shadow.opacity' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


表示 'shadow.offset.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


表示 'shadow.offset.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


表示 'shadow.offset2.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


表示 'shadow.offset2.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


表示 'shadow.origin.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


表示 'shadow.origin.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


表示 'shadow.matrix.xtox' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


表示 'shadow.matrix.xtoy' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


表示 'shadow.matrix.ytox' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


表示 'shadow.matrix.ytoy' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


表示 'shadow.matrix.perspectiveX' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


表示 'shadow.matrix.perspectiveY' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


表示 'skew.on' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


表示 'skew.offset.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


表示 'skew.offset.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


表示 'skew.origin.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


表示 'skew.origin.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


表示 'skew.matrix.xtox' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


表示 'skew.matrix.xtoy' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


表示 'skew.matrix.ytox' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


表示 'skew.matrix.ytoy' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


表示 'skew.matrix.perspectiveX' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


表示 'skew.matrix.perspectiveY' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


表示 'extrusion.on' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


表示 'extrusion.type' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


表示 'extrusion.render' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


表示 'extrusion.viewpointorigin.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


表示 'extrusion.viewpointorigin.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


表示 'extrusion.viewpoint.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


表示 'extrusion.viewpoint.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


表示 'extrusion.viewpoint.z' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


表示 'extrusion.plane' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


表示 'extrusion.skewangle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


表示 'extrusion.skewamt' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


表示 'extrusion.backdepth' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


表示 'extrusion.foredepth' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


表示 'extrusion.orientation.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


表示 'extrusion.orientation.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


表示 'extrusion.orientation.z' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


表示 'extrusion.orientationangle' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


表示 'extrusion.color' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


表示 'extrusion.rotationangle.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


表示 'extrusion.rotationangle.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


表示 'extrusion.lockrotationcenter' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


表示 'extrusion.autorotationcenter' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


表示 'extrusion.rotationcenter.x' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


表示 'extrusion.rotationcenter.y' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


表示 'extrusion.rotationcenter.z' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


表示 'extrusion.colormode' 属性

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查此对象是否等于另一个对象。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的对象。 |

**返回：**
boolean - 如果对象相等则返回 true。
### hashCode() {#hashCode--}
```
public int hashCode()
```


基于 (\#getValue.getValue) 属性计算并返回哈希码

**返回：**
int - 返回此对象的哈希码
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


根据值查找现有行为属性，或使用指定的值创建新的自定义属性

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyValue | java.lang.String | 属性的值 |

**返回：**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty 的实例