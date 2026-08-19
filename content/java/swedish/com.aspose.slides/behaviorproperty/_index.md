---
title: BehaviorProperty
second_title: Aspose.Slides för Java API-referens
description: Representerar egenskapstyper för animationsbeteende.
type: docs
url: /sv/com.aspose.slides/behaviorproperty/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Representerar egenskapstyper för animationsbeteende. Följer listan över egenskaper från https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx och https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue()](#getValue--) | Värde av egenskapen |
| [isCustom()](#isCustom--) | Visar om denna egenskap inte tillhör den fördefinierade egenskapslistan i specifikationen: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Representerar 'ppt\_x' egenskap |
| [getPptY()](#getPptY--) | Representerar 'ppt\_y' egenskap |
| [getPptW()](#getPptW--) | Representerar 'ppt\_w' egenskap |
| [getPptH()](#getPptH--) | Representerar 'ppt\_h' egenskap |
| [getPptC()](#getPptC--) | Representerar 'ppt\_c' egenskap |
| [getPptR()](#getPptR--) | Representerar 'ppt\_r' egenskap |
| [getXShear()](#getXShear--) | Representerar 'xshear' egenskap |
| [getYShear()](#getYShear--) | Representerar 'yshear' egenskap |
| [getImage()](#getImage--) | Representerar 'image' egenskap |
| [getScaleX()](#getScaleX--) | Representerar 'ScaleX' egenskap |
| [getScaleY()](#getScaleY--) | Representerar 'ScaleY' egenskap |
| [getR()](#getR--) | Representerar 'r' egenskap |
| [getFillColor()](#getFillColor--) | Representerar 'fillcolor' egenskap |
| [getStyleOpacity()](#getStyleOpacity--) | Representerar 'style.opacity' egenskap |
| [getStyleRotation()](#getStyleRotation--) | Representerar 'style.rotation' egenskap |
| [getStyleVisibility()](#getStyleVisibility--) | Representerar 'style.visibility' egenskap |
| [getStyleColor()](#getStyleColor--) | Representerar 'style.color' egenskap |
| [getStyleFontSize()](#getStyleFontSize--) | Representerar 'style.fontSize' egenskap |
| [getStyleFontWeight()](#getStyleFontWeight--) | Representerar 'style.fontWeight' egenskap |
| [getStyleFontStyle()](#getStyleFontStyle--) | Representerar 'style.fontStyle' egenskap |
| [getStyleFontFamily()](#getStyleFontFamily--) | Representerar 'style.fontFamily' egenskap |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Representerar 'style.textEffectEmboss' egenskap |
| [getStyleTextShadow()](#getStyleTextShadow--) | Representerar 'style.textShadow' egenskap |
| [getStyleTextTransform()](#getStyleTextTransform--) | Representerar 'style.textTransform' egenskap |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Representerar 'style.textDecorationUnderline' egenskap |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Representerar 'style.textEffectOutline' egenskap |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Representerar 'style.textDecorationLineThrough' egenskap |
| [getStyleSRotation()](#getStyleSRotation--) | Representerar 'style.sRotation' egenskap |
| [getImageDataCropTop()](#getImageDataCropTop--) | Representerar 'imageData.cropTop' egenskap |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Representerar 'imageData.cropBottom' egenskap |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Representerar 'imageData.cropLeft' egenskap |
| [getImageDataCropRight()](#getImageDataCropRight--) | Representerar 'imageData.cropRight' egenskap |
| [getImageDataGain()](#getImageDataGain--) | Representerar 'imageData.gain' egenskap |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Representerar 'imageData.blacklevel' egenskap |
| [getImageDataGamma()](#getImageDataGamma--) | Representerar 'imageData.gamma' egenskap |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Representerar 'imageData.grayscale' egenskap |
| [getImageDataChromakey()](#getImageDataChromakey--) | Representerar 'imageData.chromakey' egenskap |
| [getFillOn()](#getFillOn--) | Representerar 'fill.on' egenskap |
| [getFillType()](#getFillType--) | Representerar 'fill.type' egenskap |
| [getFill_Color()](#getFill-Color--) | Representerar 'fill.color' egenskap |
| [getFillOpacity()](#getFillOpacity--) | Representerar 'fill.opacity' egenskap |
| [getFillColor2()](#getFillColor2--) | Representerar 'fill.color2' egenskap |
| [getFillMethod()](#getFillMethod--) | Representerar 'fill.method' egenskap |
| [getFillOpacity2()](#getFillOpacity2--) | Representerar 'fill.opacity2' egenskap |
| [getFillAngle()](#getFillAngle--) | Representerar 'fill.angle' egenskap |
| [getFillFocus()](#getFillFocus--) | Representerar 'fill.focus' egenskap |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Representerar 'fill.focusposition.x' egenskap |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Representerar 'fill.focusposition.y' egenskap |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Representerar 'fill.focussize.x' egenskap |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Representerar 'fill.focussize.y' egenskap |
| [getStrokeOn()](#getStrokeOn--) | Representerar 'stroke.on' egenskap |
| [getStrokeColor()](#getStrokeColor--) | Representerar 'stroke.color' egenskap |
| [getStrokeWeight()](#getStrokeWeight--) | Representerar 'stroke.weight' egenskap |
| [getStrokeOpacity()](#getStrokeOpacity--) | Representerar 'stroke.opacity' egenskap |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Representerar 'stroke.linestyle' egenskap |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Representerar 'stroke.dashstyle' egenskap |
| [getStrokeFillType()](#getStrokeFillType--) | Representerar 'stroke.filltype' egenskap |
| [getStrokeSrc()](#getStrokeSrc--) | Representerar 'stroke.src' egenskap |
| [getStrokeColor2()](#getStrokeColor2--) | Representerar 'stroke.color2' egenskap |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Representerar 'stroke.imagesize.x' egenskap |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Representerar 'stroke.imagesize.y' egenskap |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Representerar 'stroke.startArrow' egenskap |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Representerar 'stroke.endArrow' egenskap |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Representerar 'stroke.startArrowWidth' egenskap |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Representerar 'stroke.startArrowLength' egenskap |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Representerar 'stroke.endArrowWidth' egenskap |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Representerar 'stroke.endArrowLength' egenskap |
| [getShadowOn()](#getShadowOn--) | Representerar 'shadow.on' egenskap |
| [getShadowType()](#getShadowType--) | Representerar 'shadow.type' egenskap |
| [getShadowColor()](#getShadowColor--) | Representerar 'shadow.color' egenskap |
| [getShadowColor2()](#getShadowColor2--) | Representerar 'shadow.color2' egenskap |
| [getShadowOpacity()](#getShadowOpacity--) | Representerar 'shadow.opacity' egenskap |
| [getShadowOffsetX()](#getShadowOffsetX--) | Representerar 'shadow.offset.x' egenskap |
| [getShadowOffsetY()](#getShadowOffsetY--) | Representerar 'shadow.offset.y' egenskap |
| [getShadowOffset2X()](#getShadowOffset2X--) | Representerar 'shadow.offset2.x' egenskap |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Representerar 'shadow.offset2.y' egenskap |
| [getShadowOriginX()](#getShadowOriginX--) | Representerar 'shadow.origin.x' egenskap |
| [getShadowOriginY()](#getShadowOriginY--) | Representerar 'shadow.origin.y' egenskap |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Representerar 'shadow.matrix.xtox' egenskap |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Representerar 'shadow.matrix.xtoy' egenskap |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Representerar 'shadow.matrix.ytox' egenskap |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Representerar 'shadow.matrix.ytoy' egenskap |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Representerar 'shadow.matrix.perspectiveX' egenskap |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Representerar 'shadow.matrix.perspectiveY' egenskap |
| [getSkewOn()](#getSkewOn--) | Representerar 'skew.on' egenskap |
| [getSkewOffsetX()](#getSkewOffsetX--) | Representerar 'skew.offset.x' egenskap |
| [getSkewOffsetY()](#getSkewOffsetY--) | Representerar 'skew.offset.y' egenskap |
| [getSkewOriginX()](#getSkewOriginX--) | Representerar 'skew.origin.x' egenskap |
| [getSkewOriginY()](#getSkewOriginY--) | Representerar 'skew.origin.y' egenskap |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Representerar 'skew.matrix.xtox' egenskap |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Representerar 'skew.matrix.xtoy' egenskap |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Representerar 'skew.matrix.ytox' egenskap |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Representerar 'skew.matrix.ytoy' egenskap |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Representerar 'skew.matrix.perspectiveX' egenskap |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Representerar 'skew.matrix.perspectiveY' egenskap |
| [getExtrusionOn()](#getExtrusionOn--) | Representerar 'extrusion.on' egenskap |
| [getExtrusionType()](#getExtrusionType--) | Representerar 'extrusion.type' egenskap |
| [getExtrusionRender()](#getExtrusionRender--) | Representerar 'extrusion.render' egenskap |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Representerar 'extrusion.viewpointorigin.x' egenskap |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Representerar 'extrusion.viewpointorigin.y' egenskap |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Representerar 'extrusion.viewpoint.x' egenskap |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Representerar 'extrusion.viewpoint.y' egenskap |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Representerar 'extrusion.viewpoint.z' egenskap |
| [getExtrusionPlane()](#getExtrusionPlane--) | Representerar 'extrusion.plane' egenskap |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Representerar 'extrusion.skewangle' egenskap |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Representerar 'extrusion.skewamt' egenskap |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Representerar 'extrusion.backdepth' egenskap |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Representerar 'extrusion.foredepth' egenskap |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Representerar 'extrusion.orientation.x' egenskap |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Representerar 'extrusion.orientation.y' egenskap |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Representerar 'extrusion.orientation.z' egenskap |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Representerar 'extrusion.orientationangle' egenskap |
| [getExtrusionColor()](#getExtrusionColor--) | Representerar 'extrusion.color' egenskap |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Representerar 'extrusion.rotationangle.x' egenskap |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Representerar 'extrusion.rotationangle.y' egenskap |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Representerar 'extrusion.lockrotationcenter' egenskap |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Representerar 'extrusion.autorotationcenter' egenskap |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Representerar 'extrusion.rotationcenter.x' egenskap |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Representerar 'extrusion.rotationcenter.y' egenskap |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Representerar 'extrusion.rotationcenter.z' egenskap |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Representerar 'extrusion.colormode' egenskap |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollerar om detta objekt är lika med ett annat. |
| [hashCode()](#hashCode--) | Beräknar och returnerar hashkod baserat på egenskapen (#getValue.getValue). |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Söker efter befintlig beteendeegenskap efter värde eller skapar en ny anpassad med det angivna värdet. |

### getValue() {#getValue--}
```
public final String getValue()
```

Värde av egenskapen

**Returnerar:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Visar om denna egenskap inte tillhör den fördefinierade egenskapslistan i specifikationen: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Returnerar:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Representerar 'ppt\_x' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Representerar 'ppt\_y' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Representerar 'ppt\_w' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Representerar 'ppt\_h' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Representerar 'ppt\_c' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Representerar 'ppt\_r' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Representerar 'xshear' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Representerar 'yshear' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Representerar 'image' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Representerar 'ScaleX' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Representerar 'ScaleY' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Representerar 'r' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Representerar 'fillcolor' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Representerar 'style.opacity' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Representerar 'style.rotation' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Representerar 'style.visibility' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Representerar 'style.color' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Representerar 'style.fontSize' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Representerar 'style.fontWeight' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Representerar 'style.fontStyle' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Representerar 'style.fontFamily' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Representerar 'style.textEffectEmboss' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Representerar 'style.textShadow' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Representerar 'style.textTransform' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Representerar 'style.textDecorationUnderline' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Representerar 'style.textEffectOutline' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Representerar 'style.textDecorationLineThrough' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Representerar 'style.sRotation' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Representerar 'imageData.cropTop' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Representerar 'imageData.cropBottom' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Representerar 'imageData.cropLeft' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Representerar 'imageData.cropRight' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Representerar 'imageData.gain' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Representerar 'imageData.blacklevel' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Representerar 'imageData.gamma' egenskap

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


Representerar 'imageData.grayscale' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


Representerar 'imageData.chromakey' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


Representerar 'fill.on' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


Representerar 'fill.type' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


Representerar 'fill.color' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


Representerar 'fill.opacity' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


Representerar 'fill.color2' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


Representerar 'fill.method' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


Representerar 'fill.opacity2' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


Representerar 'fill.angle' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


Representerar 'fill.focus' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


Representerar 'fill.focusposition.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


Representerar 'fill.focusposition.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


Representerar 'fill.focussize.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


Representerar 'fill.focussize.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


Representerar 'stroke.on' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


Representerar 'stroke.color' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


Representerar 'stroke.weight' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


Representerar 'stroke.opacity' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


Representerar 'stroke.linestyle' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


Representerar 'stroke.dashstyle' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


Representerar 'stroke.filltype' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


Representerar 'stroke.src' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


Representerar 'stroke.color2' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


Representerar 'stroke.imagesize.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


Representerar 'stroke.imagesize.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


Representerar 'stroke.startArrow' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


Representerar 'stroke.endArrow' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


Representerar 'stroke.startArrowWidth' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


Representerar 'stroke.startArrowLength' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


Representerar 'stroke.endArrowWidth' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


Representerar 'stroke.endArrowLength' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


Representerar 'shadow.on' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


Representerar 'shadow.type' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


Representerar 'shadow.color' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


Representerar 'shadow.color2' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


Representerar 'shadow.opacity' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


Representerar 'shadow.offset.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


Representerar 'shadow.offset.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


Representerar 'shadow.offset2.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


Representerar 'shadow.offset2.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


Representerar 'shadow.origin.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


Representerar 'shadow.origin.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Representerar 'shadow.matrix.xtox' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Representerar 'shadow.matrix.xtoy' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


Representerar 'shadow.matrix.ytox' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


Representerar 'shadow.matrix.ytoy' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


Representerar 'shadow.matrix.perspectiveX' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


Representerar 'shadow.matrix.perspectiveY' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


Representerar 'skew.on' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


Representerar 'skew.offset.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


Representerar 'skew.offset.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


Representerar 'skew.origin.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


Representerar 'skew.origin.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


Representerar 'skew.matrix.xtox' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


Representerar 'skew.matrix.xtoy' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


Representerar 'skew.matrix.ytox' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


Representerar 'skew.matrix.ytoy' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


Representerar 'skew.matrix.perspectiveX' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


Representerar 'skew.matrix.perspectiveY' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


Representerar 'extrusion.on' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


Representerar 'extrusion.type' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


Representerar 'extrusion.render' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


Representerar 'extrusion.viewpointorigin.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


Representerar 'extrusion.viewpointorigin.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


Representerar 'extrusion.viewpoint.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


Representerar 'extrusion.viewpoint.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


Representerar 'extrusion.viewpoint.z' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


Representerar 'extrusion.plane' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


Representerar 'extrusion.skewangle' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


Representerar 'extrusion.skewamt' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


Representerar 'extrusion.backdepth' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


Representerar 'extrusion.foredepth' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


Representerar 'extrusion.orientation.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


Representerar 'extrusion.orientation.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


Representerar 'extrusion.orientation.z' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


Representerar 'extrusion.orientationangle' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


Representerar 'extrusion.color' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


Representerar 'extrusion.rotationangle.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


Representerar 'extrusion.rotationangle.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


Representerar 'extrusion.lockrotationcenter' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


Representerar 'extrusion.autorotationcenter' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


Representerar 'extrusion.rotationcenter.x' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


Representerar 'extrusion.rotationcenter.y' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


Representerar 'extrusion.rotationcenter.z' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


Representerar 'extrusion.colormode' property

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kontrollerar om detta objekt är lika med ett annat.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objekt att jämföra. |

**Returnerar:**
boolean - Sant om objekten är lika.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar och returnerar hashkod baserat på egenskapen (\#getValue.getValue) property

**Returnerar:**
int - Returnerar hashkod för detta objekt
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


Söker efter befintlig beteendeegenskap efter värde eller skapar en ny anpassad med det angivna värdet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyValue | java.lang.String | värde av egenskapen |

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instans av BehaviorProperty