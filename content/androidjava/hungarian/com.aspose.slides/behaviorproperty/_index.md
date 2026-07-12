---
title: BehaviorProperty
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Animációs viselkedéshez tartozó tulajdonságtípusokat képviseli.
type: docs
url: /hu/com.aspose.slides/behaviorproperty/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Animációs viselkedéshez tartozó tulajdonságtípusokat képviseli. Követi a tulajdonságok listáját a https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx és https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx címekről
## Módszerek

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | A tulajdonság értéke |
| [isCustom()](#isCustom--) | Megjeleníti, ha ez a tulajdonság nem tartozik az előre definiált tulajdonságok listájához a specifikációban: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | A 'ppt\_x' tulajdonságot képviseli |
| [getPptY()](#getPptY--) | A 'ppt\_y' tulajdonságot képviseli |
| [getPptW()](#getPptW--) | A 'ppt\_w' tulajdonságot képviseli |
| [getPptH()](#getPptH--) | A 'ppt\_h' tulajdonságot képviseli |
| [getPptC()](#getPptC--) | A 'ppt\_c' tulajdonságot képviseli |
| [getPptR()](#getPptR--) | A 'ppt\_r' tulajdonságot képviseli |
| [getXShear()](#getXShear--) | A 'xshear' tulajdonságot képviseli |
| [getYShear()](#getYShear--) | A 'yshear' tulajdonságot képviseli |
| [getImage()](#getImage--) | A 'image' tulajdonságot képviseli |
| [getScaleX()](#getScaleX--) | A 'ScaleX' tulajdonságot képviseli |
| [getScaleY()](#getScaleY--) | A 'ScaleY' tulajdonságot képviseli |
| [getR()](#getR--) | A 'r' tulajdonságot képviseli |
| [getFillColor()](#getFillColor--) | A 'fillcolor' tulajdonságot képviseli |
| [getStyleOpacity()](#getStyleOpacity--) | A 'style.opacity' tulajdonságot képviseli |
| [getStyleRotation()](#getStyleRotation--) | A 'style.rotation' tulajdonságot képviseli |
| [getStyleVisibility()](#getStyleVisibility--) | A 'style.visibility' tulajdonságot képviseli |
| [getStyleColor()](#getStyleColor--) | A 'style.color' tulajdonságot képviseli |
| [getStyleFontSize()](#getStyleFontSize--) | A 'style.fontSize' tulajdonságot képviseli |
| [getStyleFontWeight()](#getStyleFontWeight--) | A 'style.fontWeight' tulajdonságot képviseli |
| [getStyleFontStyle()](#getStyleFontStyle--) | A 'style.fontStyle' tulajdonságot képviseli |
| [getStyleFontFamily()](#getStyleFontFamily--) | A 'style.fontFamily' tulajdonságot képviseli |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | A 'style.textEffectEmboss' tulajdonságot képviseli |
| [getStyleTextShadow()](#getStyleTextShadow--) | A 'style.textShadow' tulajdonságot képviseli |
| [getStyleTextTransform()](#getStyleTextTransform--) | A 'style.textTransform' tulajdonságot képviseli |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | A 'style.textDecorationUnderline' tulajdonságot képviseli |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | A 'style.textEffectOutline' tulajdonságot képviseli |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | A 'style.textDecorationLineThrough' tulajdonságot képviseli |
| [getStyleSRotation()](#getStyleSRotation--) | A 'style.sRotation' tulajdonságot képviseli |
| [getImageDataCropTop()](#getImageDataCropTop--) | A 'imageData.cropTop' tulajdonságot képviseli |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | A 'imageData.cropBottom' tulajdonságot képviseli |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | A 'imageData.cropLeft' tulajdonságot képviseli |
| [getImageDataCropRight()](#getImageDataCropRight--) | A 'imageData.cropRight' tulajdonságot képviseli |
| [getImageDataGain()](#getImageDataGain--) | A 'imageData.gain' tulajdonságot képviseli |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | A 'imageData.blacklevel' tulajdonságot képviseli |
| [getImageDataGamma()](#getImageDataGamma--) | A 'imageData.gamma' tulajdonságot képviseli |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | A 'imageData.grayscale' tulajdonságot képviseli |
| [getImageDataChromakey()](#getImageDataChromakey--) | A 'imageData.chromakey' tulajdonságot képviseli |
| [getFillOn()](#getFillOn--) | A 'fill.on' tulajdonságot képviseli |
| [getFillType()](#getFillType--) | A 'fill.type' tulajdonságot képviseli |
| [getFill_Color()](#getFill-Color--) | A 'fill.color' tulajdonságot képviseli |
| [getFillOpacity()](#getFillOpacity--) | A 'fill.opacity' tulajdonságot képviseli |
| [getFillColor2()](#getFillColor2--) | A 'fill.color2' tulajdonságot képviseli |
| [getFillMethod()](#getFillMethod--) | A 'fill.method' tulajdonságot képviseli |
| [getFillOpacity2()](#getFillOpacity2--) | A 'fill.opacity2' tulajdonságot képviseli |
| [getFillAngle()](#getFillAngle--) | A 'fill.angle' tulajdonságot képviseli |
| [getFillFocus()](#getFillFocus--) | A 'fill.focus' tulajdonságot képviseli |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | A 'fill.focusposition.x' tulajdonságot képviseli |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | A 'fill.focusposition.y' tulajdonságot képviseli |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | A 'fill.focussize.x' tulajdonságot képviseli |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | A 'fill.focussize.y' tulajdonságot képviseli |
| [getStrokeOn()](#getStrokeOn--) | A 'stroke.on' tulajdonságot képviseli |
| [getStrokeColor()](#getStrokeColor--) | A 'stroke.color' tulajdonságot képviseli |
| [getStrokeWeight()](#getStrokeWeight--) | A 'stroke.weight' tulajdonságot képviseli |
| [getStrokeOpacity()](#getStrokeOpacity--) | A 'stroke.opacity' tulajdonságot képviseli |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | A 'stroke.linestyle' tulajdonságot képviseli |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | A 'stroke.dashstyle' tulajdonságot képviseli |
| [getStrokeFillType()](#getStrokeFillType--) | A 'stroke.filltype' tulajdonságot képviseli |
| [getStrokeSrc()](#getStrokeSrc--) | A 'stroke.src' tulajdonságot képviseli |
| [getStrokeColor2()](#getStrokeColor2--) | A 'stroke.color2' tulajdonságot képviseli |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | A 'stroke.imagesize.x' tulajdonságot képviseli |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | A 'stroke.imagesize.y' tulajdonságot képviseli |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | A 'stroke.startArrow' tulajdonságot képviseli |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | A 'stroke.endArrow' tulajdonságot képviseli |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | A 'stroke.startArrowWidth' tulajdonságot képviseli |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | A 'stroke.startArrowLength' tulajdonságot képviseli |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | A 'stroke.endArrowWidth' tulajdonságot képviseli |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | A 'stroke.endArrowLength' tulajdonságot képviseli |
| [getShadowOn()](#getShadowOn--) | A 'shadow.on' tulajdonságot képviseli |
| [getShadowType()](#getShadowType--) | A 'shadow.type' tulajdonságot képviseli |
| [getShadowColor()](#getShadowColor--) | A 'shadow.color' tulajdonságot képviseli |
| [getShadowColor2()](#getShadowColor2--) | A 'shadow.color2' tulajdonságot képviseli |
| [getShadowOpacity()](#getShadowOpacity--) | A 'shadow.opacity' tulajdonságot képviseli |
| [getShadowOffsetX()](#getShadowOffsetX--) | A 'shadow.offset.x' tulajdonságot képviseli |
| [getShadowOffsetY()](#getShadowOffsetY--) | A 'shadow.offset.y' tulajdonságot képviseli |
| [getShadowOffset2X()](#getShadowOffset2X--) | A 'shadow.offset2.x' tulajdonságot képviseli |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | A 'shadow.offset2.y' tulajdonságot képviseli |
| [getShadowOriginX()](#getShadowOriginX--) | A 'shadow.origin.x' tulajdonságot képviseli |
| [getShadowOriginY()](#getShadowOriginY--) | A 'shadow.origin.y' tulajdonságot képviseli |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | A 'shadow.matrix.xtox' tulajdonságot képviseli |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | A 'shadow.matrix.xtoy' tulajdonságot képviseli |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | A 'shadow.matrix.ytox' tulajdonságot képviseli |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | A 'shadow.matrix.ytoy' tulajdonságot képviseli |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | A 'shadow.matrix.perspectiveX' tulajdonságot képviseli |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | A 'shadow.matrix.perspectiveY' tulajdonságot képviseli |
| [getSkewOn()](#getSkewOn--) | A 'skew.on' tulajdonságot képviseli |
| [getSkewOffsetX()](#getSkewOffsetX--) | A 'skew.offset.x' tulajdonságot képviseli |
| [getSkewOffsetY()](#getSkewOffsetY--) | A 'skew.offset.y' tulajdonságot képviseli |
| [getSkewOriginX()](#getSkewOriginX--) | A 'skew.origin.x' tulajdonságot képviseli |
| [getSkewOriginY()](#getSkewOriginY--) | A 'skew.origin.y' tulajdonságot képviseli |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | A 'skew.matrix.xtox' tulajdonságot képviseli |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | A 'skew.matrix.xtoy' tulajdonságot képviseli |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | A 'skew.matrix.ytox' tulajdonságot képviseli |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | A 'skew.matrix.ytoy' tulajdonságot képviseli |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | A 'skew.matrix.perspectiveX' tulajdonságot képviseli |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | A 'skew.matrix.perspectiveY' tulajdonságot képviseli |
| [getExtrusionOn()](#getExtrusionOn--) | A 'extrusion.on' tulajdonságot képviseli |
| [getExtrusionType()](#getExtrusionType--) | A 'extrusion.type' tulajdonságot képviseli |
| [getExtrusionRender()](#getExtrusionRender--) | A 'extrusion.render' tulajdonságot képviseli |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | A 'extrusion.viewpointorigin.x' tulajdonságot képviseli |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | A 'extrusion.viewpointorigin.y' tulajdonságot képviseli |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | A 'extrusion.viewpoint.x' tulajdonságot képviseli |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | A 'extrusion.viewpoint.y' tulajdonságot képviseli |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | A 'extrusion.viewpoint.z' tulajdonságot képviseli |
| [getExtrusionPlane()](#getExtrusionPlane--) | A 'extrusion.plane' tulajdonságot képviseli |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | A 'extrusion.skewangle' tulajdonságot képviseli |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | A 'extrusion.skewamt' tulajdonságot képviseli |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | A 'extrusion.backdepth' tulajdonságot képviseli |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | A 'extrusion.foredepth' tulajdonságot képviseli |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | A 'extrusion.orientation.x' tulajdonságot képviseli |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | A 'extrusion.orientation.y' tulajdonságot képviseli |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | A 'extrusion.orientation.z' tulajdonságot képviseli |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | A 'extrusion.orientationangle' tulajdonságot képviseli |
| [getExtrusionColor()](#getExtrusionColor--) | A 'extrusion.color' tulajdonságot képviseli |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | A 'extrusion.rotationangle.x' tulajdonságot képviseli |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | A 'extrusion.rotationangle.y' tulajdonságot képviseli |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | A 'extrusion.lockrotationcenter' tulajdonságot képviseli |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | A 'extrusion.autorotationcenter' tulajdonságot képviseli |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | A 'extrusion.rotationcenter.x' tulajdonságot képviseli |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | A 'extrusion.rotationcenter.y' tulajdonságot képviseli |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | A 'extrusion.rotationcenter.z' tulajdonságot képviseli |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | A 'extrusion.colormode' tulajdonságot képviseli |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi, hogy ez az objektum egyenlő-e egy másikkal. |
| [hashCode()](#hashCode--) | Kiszámítja és visszaadja a hash kódot a (\#getValue.getValue) tulajdonság alapján |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Megkeresi a meglévő viselkedés tulajdonságot az érték alapján, vagy új egyéni tulajdonságot hoz létre a megadott értékkel |
### getValue() {#getValue--}
```
public final String getValue()
```


A tulajdonság értéke

**Visszatér:**
java.lang.String
### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Megjeleníti, ha ez a tulajdonság nem tartozik az előre definiált tulajdonságok listájához a specifikációban: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Visszatér:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```


A 'ppt\_x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```


A 'ppt\_y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```


A 'ppt\_w' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```


A 'ppt\_h' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```


A 'ppt\_c' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```


A 'ppt\_r' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```


A 'xshear' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```


A 'yshear' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```


A 'image' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```


A 'ScaleX' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```


A 'ScaleY' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```


A 'r' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```


A 'fillcolor' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```


A 'style.opacity' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```


A 'style.rotation' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```


A 'style.visibility' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```


A 'style.color' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```


A 'style.fontSize' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```


A 'style.fontWeight' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```


A 'style.fontStyle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```


A 'style.fontFamily' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```


A 'style.textEffectEmboss' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```


A 'style.textShadow' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```


A 'style.textTransform' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```


A 'style.textDecorationUnderline' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```


A 'style.textEffectOutline' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```


A 'style.textDecorationLineThrough' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```


A 'style.sRotation' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```


A 'imageData.cropTop' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```


A 'imageData.cropBottom' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```


A 'imageData.cropLeft' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```


A 'imageData.cropRight' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```


A 'imageData.gain' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```


A 'imageData.blacklevel' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```


A 'imageData.gamma' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


A 'imageData.grayscale' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


A 'imageData.chromakey' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


A 'fill.on' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


A 'fill.type' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


A 'fill.color' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


A 'fill.opacity' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


A 'fill.color2' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


A 'fill.method' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


A 'fill.opacity2' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


A 'fill.angle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


A 'fill.focus' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


A 'fill.focusposition.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


A 'fill.focusposition.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


A 'fill.focussize.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


A 'fill.focussize.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


A 'stroke.on' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


A 'stroke.color' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


A 'stroke.weight' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


A 'stroke.opacity' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


A 'stroke.linestyle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


A 'stroke.dashstyle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


A 'stroke.filltype' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


A 'stroke.src' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


A 'stroke.color2' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


A 'stroke.imagesize.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


A 'stroke.imagesize.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


A 'stroke.startArrow' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


A 'stroke.endArrow' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public        

```


A 'stroke.startArrowWidth' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


A 'stroke.startArrowLength' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


A 'stroke.endArrowWidth' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


A 'stroke.endArrowLength' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


A 'shadow.on' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


A 'shadow.type' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


A 'shadow.color' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


A 'shadow.color2' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


A 'shadow.opacity' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


A 'shadow.offset.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


A 'shadow.offset.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


A 'shadow.offset2.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


A 'shadow.offset2.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


A 'shadow.origin.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


A 'shadow.origin.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


A 'shadow.matrix.xtox' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


A 'shadow.matrix.xtoy' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


A 'shadow.matrix.ytox' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


A 'shadow.matrix.ytoy' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


A 'shadow.matrix.perspectiveX' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


A 'shadow.matrix.perspectiveY' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


A 'skew.on' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


A 'skew.offset.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


A 'skew.offset.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


A 'skew.origin.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


A 'skew.origin.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


A 'skew.matrix.xtox' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


A 'skew.matrix.xtoy' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


A 'skew.matrix.ytox' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


A 'skew.matrix.ytoy' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


A 'skew.matrix.perspectiveX' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


A 'skew.matrix.perspectiveY' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


A 'extrusion.on' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


A 'extrusion.type' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


A 'extrusion.render' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


A 'extrusion.viewpointorigin.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


A 'extrusion.viewpointorigin.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


A 'extrusion.viewpoint.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


A 'extrusion.viewpoint.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


A 'extrusion.viewpoint.z' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


A 'extrusion.plane' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


A 'extrusion.skewangle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


A 'extrusion.skewamt' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


A 'extrusion.backdepth' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


A 'extrusion.foredepth' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


A 'extrusion.orientation.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


A 'extrusion.orientation.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


A 'extrusion.orientation.z' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


A 'extrusion.orientationangle' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


A 'extrusion.color' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


A 'extrusion.rotationangle.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


A 'extrusion.rotationangle.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


A 'extrusion.lockrotationcenter' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


A 'extrusion.autorotationcenter' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


A 'extrusion.rotationcenter.x' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


A 'extrusion.rotationcenter.y' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


A 'extrusion.rotationcenter.z' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


A 'extrusion.colormode' tulajdonságot képviseli

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ellenőrzi, hogy ez az objektum egyenlő-e egy másikkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az összehasonlítandó objektum. |

**Visszatér:**
boolean - Igaz, ha az objektumok egyenlőek.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Kiszámítja és visszaadja a hash kódot a (\#getValue.getValue) tulajdonság alapján

**Visszatér:**
int - Visszaadja az objektum hash kódját
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


Megkeresi a meglévő viselkedés tulajdonságot az érték alapján, vagy új egyéni tulajdonságot hoz létre a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - a BehaviorProperty példánya