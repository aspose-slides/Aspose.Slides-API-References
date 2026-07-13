---
title: BehaviorProperty
second_title: Aspose.Slides för Android via Java API-referens
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
| [getValue()](#getValue--) | Värde för egenskapen |
| [isCustom()](#isCustom--) | Visar om denna egenskap inte tillhör den fördefinierade egenskapslistan i specifikationen: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Representerar 'ppt_x' egenskapen |
| [getPptY()](#getPptY--) | Representerar 'ppt_y' egenskapen |
| [getPptW()](#getPptW--) | Representerar 'ppt_w' egenskapen |
| [getPptH()](#getPptH--) | Representerar 'ppt_h' egenskapen |
| [getPptC()](#getPptC--) | Representerar 'ppt_c' egenskapen |
| [getPptR()](#getPptR--) | Representerar 'ppt_r' egenskapen |
| [getXShear()](#getXShear--) | Representerar 'xshear' egenskapen |
| [getYShear()](#getYShear--) | Representerar 'yshear' egenskapen |
| [getImage()](#getImage--) | Representerar 'image' egenskapen |
| [getScaleX()](#getScaleX--) | Representerar 'ScaleX' egenskapen |
| [getScaleY()](#getScaleY--) | Representerar 'ScaleY' egenskapen |
| [getR()](#getR--) | Representerar 'r' egenskapen |
| [getFillColor()](#getFillColor--) | Representerar 'fillcolor' egenskapen |
| [getStyleOpacity()](#getStyleOpacity--) | Representerar 'style.opacity' egenskapen |
| [getStyleRotation()](#getStyleRotation--) | Representerar 'style.rotation' egenskapen |
| [getStyleVisibility()](#getStyleVisibility--) | Representerar 'style.visibility' egenskapen |
| [getStyleColor()](#getStyleColor--) | Representerar 'style.color' egenskapen |
| [getStyleFontSize()](#getStyleFontSize--) | Representerar 'style.fontSize' egenskapen |
| [getStyleFontWeight()](#getStyleFontWeight--) | Representerar 'style.fontWeight' egenskapen |
| [getStyleFontStyle()](#getStyleFontStyle--) | Representerar 'style.fontStyle' egenskapen |
| [getStyleFontFamily()](#getStyleFontFamily--) | Representerar 'style.fontFamily' egenskapen |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Representerar 'style.textEffectEmboss' egenskapen |
| [getStyleTextShadow()](#getStyleTextShadow--) | Representerar 'style.textShadow' egenskapen |
| [getStyleTextTransform()](#getStyleTextTransform--) | Representerar 'style.textTransform' egenskapen |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Representerar 'style.textDecorationUnderline' egenskapen |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Representerar 'style.textEffectOutline' egenskapen |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Representerar 'style.textDecorationLineThrough' egenskapen |
| [getStyleSRotation()](#getStyleSRotation--) | Representerar 'style.sRotation' egenskapen |
| [getImageDataCropTop()](#getImageDataCropTop--) | Representerar 'imageData.cropTop' egenskapen |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Representerar 'imageData.cropBottom' egenskapen |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Representerar 'imageData.cropLeft' egenskapen |
| [getImageDataCropRight()](#getImageDataCropRight--) | Representerar 'imageData.cropRight' egenskapen |
| [getImageDataGain()](#getImageDataGain--) | Representerar 'imageData.gain' egenskapen |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Representerar 'imageData.blacklevel' egenskapen |
| [getImageDataGamma()](#getImageDataGamma--) | Representerar 'imageData.gamma' egenskapen |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Representerar 'imageData.grayscale' egenskapen |
| [getImageDataChromakey()](#getImageDataChromakey--) | Representerar 'imageData.chromakey' egenskapen |
| [getFillOn()](#getFillOn--) | Representerar 'fill.on' egenskapen |
| [getFillType()](#getFillType--) | Representerar 'fill.type' egenskapen |
| [getFill_Color()](#getFill-Color--) | Representerar 'fill.color' egenskapen |
| [getFillOpacity()](#getFillOpacity--) | Representerar 'fill.opacity' egenskapen |
| [getFillColor2()](#getFillColor2--) | Representerar 'fill.color2' egenskapen |
| [getFillMethod()](#getFillMethod--) | Representerar 'fill.method' egenskapen |
| [getFillOpacity2()](#getFillOpacity2--) | Representerar 'fill.opacity2' egenskapen |
| [getFillAngle()](#getFillAngle--) | Representerar 'fill.angle' egenskapen |
| [getFillFocus()](#getFillFocus--) | Representerar 'fill.focus' egenskapen |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Representerar 'fill.focusposition.x' egenskapen |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Representerar 'fill.focusposition.y' egenskapen |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Representerar 'fill.focussize.x' egenskapen |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Representerar 'fill.focussize.y' egenskapen |
| [getStrokeOn()](#getStrokeOn--) | Representerar 'stroke.on' egenskapen |
| [getStrokeColor()](#getStrokeColor--) | Representerar 'stroke.color' egenskapen |
| [getStrokeWeight()](#getStrokeWeight--) | Representerar 'stroke.weight' egenskapen |
| [getStrokeOpacity()](#getStrokeOpacity--) | Representerar 'stroke.opacity' egenskapen |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Representerar 'stroke.linestyle' egenskapen |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Representerar 'stroke.dashstyle' egenskapen |
| [getStrokeFillType()](#getStrokeFillType--) | Representerar 'stroke.filltype' egenskapen |
| [getStrokeSrc()](#getStrokeSrc--) | Representerar 'stroke.src' egenskapen |
| [getStrokeColor2()](#getStrokeColor2--) | Representerar 'stroke.color2' egenskapen |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Representerar 'stroke.imagesize.x' egenskapen |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Representerar 'stroke.imagesize.y' egenskapen |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Representerar 'stroke.startArrow' egenskapen |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Representerar 'stroke.endArrow' egenskapen |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Representerar 'stroke.startArrowWidth' egenskapen |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Representerar 'stroke.startArrowLength' egenskapen |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Representerar 'stroke.endArrowWidth' egenskapen |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Representerar 'stroke.endArrowLength' egenskapen |
| [getShadowOn()](#getShadowOn--) | Representerar 'shadow.on' egenskapen |
| [getShadowType()](#getShadowType--) | Representerar 'shadow.type' egenskapen |
| [getShadowColor()](#getShadowColor--) | Representerar 'shadow.color' egenskapen |
| [getShadowColor2()](#getShadowColor2--) | Representerar 'shadow.color2' egenskapen |
| [getShadowOpacity()](#getShadowOpacity--) | Representerar 'shadow.opacity' egenskapen |
| [getShadowOffsetX()](#getShadowOffsetX--) | Representerar 'shadow.offset.x' egenskapen |
| [getShadowOffsetY()](#getShadowOffsetY--) | Representerar 'shadow.offset.y' egenskapen |
| [getShadowOffset2X()](#getShadowOffset2X--) | Representerar 'shadow.offset2.x' egenskapen |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Representerar 'shadow.offset2.y' egenskapen |
| [getShadowOriginX()](#getShadowOriginX--) | Representerar 'shadow.origin.x' egenskapen |
| [getShadowOriginY()](#getShadowOriginY--) | Representerar 'shadow.origin.y' egenskapen |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Representerar 'shadow.matrix.xtox' egenskapen |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Representerar 'shadow.matrix.xtoy' egenskapen |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Representerar 'shadow.matrix.ytox' egenskapen |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Representerar 'shadow.matrix.ytoy' egenskapen |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Representerar 'shadow.matrix.perspectiveX' egenskapen |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Representerar 'shadow.matrix.perspectiveY' egenskapen |
| [getSkewOn()](#getSkewOn--) | Representerar 'skew.on' egenskapen |
| [getSkewOffsetX()](#getSkewOffsetX--) | Representerar 'skew.offset.x' egenskapen |
| [getSkewOffsetY()](#getSkewOffsetY--) | Representerar 'skew.offset.y' egenskapen |
| [getSkewOriginX()](#getSkewOriginX--) | Representerar 'skew.origin.x' egenskapen |
| [getSkewOriginY()](#getSkewOriginY--) | Representerar 'skew.origin.y' egenskapen |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Representerar 'skew.matrix.xtox' egenskapen |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Representerar 'skew.matrix.xtoy' egenskapen |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Representerar 'skew.matrix.ytox' egenskapen |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Representerar 'skew.matrix.ytoy' egenskapen |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Representerar 'skew.matrix.perspectiveX' egenskapen |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Representerar 'skew.matrix.perspectiveY' egenskapen |
| [getExtrusionOn()](#getExtrusionOn--) | Representerar 'extrusion.on' egenskapen |
| [getExtrusionType()](#getExtrusionType--) | Representerar 'extrusion.type' egenskapen |
| [getExtrusionRender()](#getExtrusionRender--) | Representerar 'extrusion.render' egenskapen |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Representerar 'extrusion.viewpointorigin.x' egenskapen |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Representerar 'extrusion.viewpointorigin.y' egenskapen |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Representerar 'extrusion.viewpoint.x' egenskapen |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Representerar 'extrusion.viewpoint.y' egenskapen |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Representerar 'extrusion.viewpoint.z' egenskapen |
| [getExtrusionPlane()](#getExtrusionPlane--) | Representerar 'extrusion.plane' egenskapen |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Representerar 'extrusion.skewangle' egenskapen |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Representerar 'extrusion.skewamt' egenskapen |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Representerar 'extrusion.backdepth' egenskapen |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Representerar 'extrusion.foredepth' egenskapen |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Representerar 'extrusion.orientation.x' egenskapen |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Representerar 'extrusion.orientation.y' egenskapen |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Representerar 'extrusion.orientation.z' egenskapen |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Representerar 'extrusion.orientationangle' egenskapen |
| [getExtrusionColor()](#getExtrusionColor--) | Representerar 'extrusion.color' egenskapen |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Representerar 'extrusion.rotationangle.x' egenskapen |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Representerar 'extrusion.rotationangle.y' egenskapen |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Representerar 'extrusion.lockrotationcenter' egenskapen |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Representerar 'extrusion.autorotationcenter' egenskapen |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Representerar 'extrusion.rotationcenter.x' egenskapen |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Representerar 'extrusion.rotationcenter.y' egenskapen |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Representerar 'extrusion.rotationcenter.z' egenskapen |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Representerar 'extrusion.colormode' egenskapen |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollerar om detta objekt är lika med ett annat. |
| [hashCode()](#hashCode--) | Beräknar och returnerar hashkod baserat på (\#getValue.getValue) egenskapen |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Söker efter befintlig beteendeegenskap efter värde eller skapar en ny anpassad med det angivna värdet |

### getValue() {#getValue--}
```
public final String getValue()
```

Värde för egenskapen

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

Representerar 'ppt_x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Representerar 'ppt_y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Representerar 'ppt_w' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Representerar 'ppt_h' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Representerar 'ppt_c' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Representerar 'ppt_r' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Representerar 'xshear' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Representerar 'yshear' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Representerar 'image' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Representerar 'ScaleX' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Representerar 'ScaleY' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Representerar 'r' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Representerar 'fillcolor' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Representerar 'style.opacity' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Representerar 'style.rotation' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Representerar 'style.visibility' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Representerar 'style.color' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Representerar 'style.fontSize' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Representerar 'style.fontWeight' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Representerar 'style.fontStyle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Representerar 'style.fontFamily' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Representerar 'style.textEffectEmboss' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Representerar 'style.textShadow' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Representerar 'style.textTransform' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Representerar 'style.textDecorationUnderline' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Representerar 'style.textEffectOutline' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Representerar 'style.textDecorationLineThrough' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Representerar 'style.sRotation' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Representerar 'imageData.cropTop' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Representerar 'imageData.cropBottom' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Representerar 'imageData.cropLeft' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Representerar 'imageData.cropRight' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Representerar 'imageData.gain' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Representerar 'imageData.blacklevel' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Representerar 'imageData.gamma' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Representerar 'imageData.grayscale' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Representerar 'imageData.chromakey' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Representerar 'fill.on' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Representerar 'fill.type' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Representerar 'fill.color' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Representerar 'fill.opacity' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Representerar 'fill.color2' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Representerar 'fill.method' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Representerar 'fill.opacity2' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Representerar 'fill.angle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Representerar 'fill.focus' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Representerar 'fill.focusposition.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Representerar 'fill.focusposition.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Representerar 'fill.focussize.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Representerar 'fill.focussize.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Representerar 'stroke.on' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Representerar 'stroke.color' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Representerar 'stroke.weight' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Representerar 'stroke.opacity' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Representerar 'stroke.linestyle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Representerar 'stroke.dashstyle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Representerar 'stroke.filltype' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Representerar 'stroke.src' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Representerar 'stroke.color2' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Representerar 'stroke.imagesize.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Representerar 'stroke.imagesize.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Representerar 'stroke.startArrow' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Representerar 'stroke.endArrow' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Representerar 'stroke.startArrowWidth' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Representerar 'stroke.startArrowLength' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Representerar 'stroke.endArrowWidth' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Representerar 'stroke.endArrowLength' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Representerar 'shadow.on' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Representerar 'shadow.type' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Representerar 'shadow.color' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Representerar 'shadow.color2' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Representerar 'shadow.opacity' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Representerar 'shadow.offset.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Representerar 'shadow.offset.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Representerar 'shadow.offset2.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Representerar 'shadow.offset2.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Representerar 'shadow.origin.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Representerar 'shadow.origin.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Representerar 'shadow.matrix.xtox' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Representerar 'shadow.matrix.xtoy' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Representerar 'shadow.matrix.ytox' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Representerar 'shadow.matrix.ytoy' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Representerar 'shadow.matrix.perspectiveX' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Representerar 'shadow.matrix.perspectiveY' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Representerar 'skew.on' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Representerar 'skew.offset.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Representerar 'skew.offset.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Representerar 'skew.origin.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Representerar 'skew.origin.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Representerar 'skew.matrix.xtox' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Representerar 'skew.matrix.xtoy' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Representerar 'skew.matrix.ytox' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Representerar 'skew.matrix.ytoy' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Representerar 'skew.matrix.perspectiveX' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Representerar 'skew.matrix.perspectiveY' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Representerar 'extrusion.on' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Representerar 'extrusion.type' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Representerar 'extrusion.render' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Representerar 'extrusion.viewpointorigin.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Representerar 'extrusion.viewpointorigin.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Representerar 'extrusion.viewpoint.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Representerar 'extrusion.viewpoint.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Representerar 'extrusion.viewpoint.z' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Representerar 'extrusion.plane' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Representerar 'extrusion.skewangle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Representerar 'extrusion.skewamt' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Representerar 'extrusion.backdepth' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Representerar 'extrusion.foredepth' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Representerar 'extrusion.orientation.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Representerar 'extrusion.orientation.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Representerar 'extrusion.orientation.z' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Representerar 'extrusion.orientationangle' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Representerar 'extrusion.color' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Representerar 'extrusion.rotationangle.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Representerar 'extrusion.rotationangle.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Representerar 'extrusion.lockrotationcenter' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Representerar 'extrusion.autorotationcenter' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Representerar 'extrusion.rotationcenter.x' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Representerar 'extrusion.rotationcenter.y' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Representerar 'extrusion.rotationcenter.z' egenskapen

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Representerar 'extrusion.colormode' egenskapen

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

Beräknar och returnerar hashkod baserat på (\#getValue.getValue) egenskapen

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
| propertyValue | java.lang.String | värde på egenskapen |

**Returnerar:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instans av BehaviorProperty