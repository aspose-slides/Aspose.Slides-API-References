---
title: BehaviorProperty
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Eigenschaftstypen für Animationsverhalten dar.
type: docs
url: /de/com.aspose.slides/behaviorproperty/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Stellt Eigenschaftstypen für Animationsverhalten dar. Folgt der Liste von Eigenschaften aus https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx und https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Wert der Eigenschaft |
| [isCustom()](#isCustom--) | Zeigt, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftenliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Repräsentiert die Eigenschaft 'ppt_x' |
| [getPptY()](#getPptY--) | Repräsentiert die Eigenschaft 'ppt_y' |
| [getPptW()](#getPptW--) | Repräsentiert die Eigenschaft 'ppt_w' |
| [getPptH()](#getPptH--) | Repräsentiert die Eigenschaft 'ppt_h' |
| [getPptC()](#getPptC--) | Repräsentiert die Eigenschaft 'ppt_c' |
| [getPptR()](#getPptR--) | Repräsentiert die Eigenschaft 'ppt_r' |
| [getXShear()](#getXShear--) | Repräsentiert die Eigenschaft 'xshear' |
| [getYShear()](#getYShear--) | Repräsentiert die Eigenschaft 'yshear' |
| [getImage()](#getImage--) | Repräsentiert die Eigenschaft 'image' |
| [getScaleX()](#getScaleX--) | Repräsentiert die Eigenschaft 'ScaleX' |
| [getScaleY()](#getScaleY--) | Repräsentiert die Eigenschaft 'ScaleY' |
| [getR()](#getR--) | Repräsentiert die Eigenschaft 'r' |
| [getFillColor()](#getFillColor--) | Repräsentiert die Eigenschaft 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Repräsentiert die Eigenschaft 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Repräsentiert die Eigenschaft 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Repräsentiert die Eigenschaft 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Repräsentiert die Eigenschaft 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Repräsentiert die Eigenschaft 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Repräsentiert die Eigenschaft 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Repräsentiert die Eigenschaft 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Repräsentiert die Eigenschaft 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Repräsentiert die Eigenschaft 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Repräsentiert die Eigenschaft 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Repräsentiert die Eigenschaft 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Repräsentiert die Eigenschaft 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Repräsentiert die Eigenschaft 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Repräsentiert die Eigenschaft 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Repräsentiert die Eigenschaft 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Repräsentiert die Eigenschaft 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Repräsentiert die Eigenschaft 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Repräsentiert die Eigenschaft 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Repräsentiert die Eigenschaft 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Repräsentiert die Eigenschaft 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Repräsentiert die Eigenschaft 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Repräsentiert die Eigenschaft 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Repräsentiert die Eigenschaft 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Repräsentiert die Eigenschaft 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Repräsentiert die Eigenschaft 'fill.on' |
| [getFillType()](#getFillType--) | Repräsentiert die Eigenschaft 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Repräsentiert die Eigenschaft 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Repräsentiert die Eigenschaft 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Repräsentiert die Eigenschaft 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Repräsentiert die Eigenschaft 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Repräsentiert die Eigenschaft 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Repräsentiert die Eigenschaft 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Repräsentiert die Eigenschaft 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Repräsentiert die Eigenschaft 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Repräsentiert die Eigenschaft 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Repräsentiert die Eigenschaft 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Repräsentiert die Eigenschaft 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Repräsentiert die Eigenschaft 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Repräsentiert die Eigenschaft 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Repräsentiert die Eigenschaft 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Repräsentiert die Eigenschaft 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Repräsentiert die Eigenschaft 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Repräsentiert die Eigenschaft 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Repräsentiert die Eigenschaft 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Repräsentiert die Eigenschaft 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Repräsentiert die Eigenschaft 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Repräsentiert die Eigenschaft 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Repräsentiert die Eigenschaft 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Repräsentiert die Eigenschaft 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Repräsentiert die Eigenschaft 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Repräsentiert die Eigenschaft 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Repräsentiert die Eigenschaft 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Repräsentiert die Eigenschaft 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Repräsentiert die Eigenschaft 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Repräsentiert die Eigenschaft 'shadow.on' |
| [getShadowType()](#getShadowType--) | Repräsentiert die Eigenschaft 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Repräsentiert die Eigenschaft 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Repräsentiert die Eigenschaft 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Repräsentiert die Eigenschaft 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Repräsentiert die Eigenschaft 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Repräsentiert die Eigenschaft 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Repräsentiert die Eigenschaft 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Repräsentiert die Eigenschaft 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Repräsentiert die Eigenschaft 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Repräsentiert die Eigenschaft 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Repräsentiert die Eigenschaft 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Repräsentiert die Eigenschaft 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Repräsentiert die Eigenschaft 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Repräsentiert die Eigenschaft 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Repräsentiert die Eigenschaft 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Repräsentiert die Eigenschaft 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Repräsentiert die Eigenschaft 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Repräsentiert die Eigenschaft 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Repräsentiert die Eigenschaft 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Repräsentiert die Eigenschaft 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Repräsentiert die Eigenschaft 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Repräsentiert die Eigenschaft 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Repräsentiert die Eigenschaft 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Repräsentiert die Eigenschaft 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Repräsentiert die Eigenschaft 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Repräsentiert die Eigenschaft 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Repräsentiert die Eigenschaft 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Repräsentiert die Eigenschaft 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Repräsentiert die Eigenschaft 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Repräsentiert die Eigenschaft 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Repräsentiert die Eigenschaft 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Repräsentiert die Eigenschaft 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Repräsentiert die Eigenschaft 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Repräsentiert die Eigenschaft 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Repräsentiert die Eigenschaft 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Repräsentiert die Eigenschaft 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Repräsentiert die Eigenschaft 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Repräsentiert die Eigenschaft 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Repräsentiert die Eigenschaft 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Repräsentiert die Eigenschaft 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Repräsentiert die Eigenschaft 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Repräsentiert die Eigenschaft 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Repräsentiert die Eigenschaft 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Repräsentiert die Eigenschaft 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Repräsentiert die Eigenschaft 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Repräsentiert die Eigenschaft 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Repräsentiert die Eigenschaft 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Repräsentiert die Eigenschaft 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Repräsentiert die Eigenschaft 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Repräsentiert die Eigenschaft 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Repräsentiert die Eigenschaft 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Repräsentiert die Eigenschaft 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Repräsentiert die Eigenschaft 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Überprüft, ob dieses Objekt einem anderen gleich ist. |
| [hashCode()](#hashCode--) | Berechnet und gibt den Hashcode basierend auf der (\#getValue.getValue) Eigenschaft zurück |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Sucht nach einer vorhandenen Verhaltenseigenschaft anhand des Werts oder erstellt eine neue benutzerdefinierte mit dem angegebenen Wert |

### getValue() {#getValue--}
```
public final String getValue()
```

Wert der Eigenschaft

**Rückgabe:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Zeigt, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftenliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Rückgabe:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Repräsentiert die Eigenschaft 'ppt_x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Repräsentiert die Eigenschaft 'ppt_y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Repräsentiert die Eigenschaft 'ppt_w'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Repräsentiert die Eigenschaft 'ppt_h'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Repräsentiert die Eigenschaft 'ppt_c'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Repräsentiert die Eigenschaft 'ppt_r'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Repräsentiert die Eigenschaft 'xshear'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Repräsentiert die Eigenschaft 'yshear'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Repräsentiert die Eigenschaft 'image'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Repräsentiert die Eigenschaft 'ScaleX'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Repräsentiert die Eigenschaft 'ScaleY'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Repräsentiert die Eigenschaft 'r'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Repräsentiert die Eigenschaft 'fillcolor'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Repräsentiert die Eigenschaft 'style.opacity'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Repräsentiert die Eigenschaft 'style.rotation'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Repräsentiert die Eigenschaft 'style.visibility'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Repräsentiert die Eigenschaft 'style.color'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Repräsentiert die Eigenschaft 'style.fontSize'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Repräsentiert die Eigenschaft 'style.fontWeight'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Repräsentiert die Eigenschaft 'style.fontStyle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Repräsentiert die Eigenschaft 'style.fontFamily'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Repräsentiert die Eigenschaft 'style.textEffectEmboss'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Repräsentiert die Eigenschaft 'style.textShadow'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Repräsentiert die Eigenschaft 'style.textTransform'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Repräsentiert die Eigenschaft 'style.textDecorationUnderline'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Repräsentiert die Eigenschaft 'style.textEffectOutline'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Repräsentiert die Eigenschaft 'style.textDecorationLineThrough'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Repräsentiert die Eigenschaft 'style.sRotation'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Repräsentiert die Eigenschaft 'imageData.cropTop'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Repräsentiert die Eigenschaft 'imageData.cropBottom'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Repräsentiert die Eigenschaft 'imageData.cropLeft'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Repräsentiert die Eigenschaft 'imageData.cropRight'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Repräsentiert die Eigenschaft 'imageData.gain'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Repräsentiert die Eigenschaft 'imageData.blacklevel'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public

```


Repräsentiert die Eigenschaft 'imageData.gamma'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Repräsentiert die Eigenschaft 'imageData.grayscale'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Repräsentiert die Eigenschaft 'imageData.chromakey'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Repräsentiert die Eigenschaft 'fill.on'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Repräsentiert die Eigenschaft 'fill.type'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Repräsentiert die Eigenschaft 'fill.color'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Repräsentiert die Eigenschaft 'fill.opacity'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Repräsentiert die Eigenschaft 'fill.color2'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Repräsentiert die Eigenschaft 'fill.method'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Repräsentiert die Eigenschaft 'fill.opacity2'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Repräsentiert die Eigenschaft 'fill.angle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Repräsentiert die Eigenschaft 'fill.focus'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Repräsentiert die Eigenschaft 'fill.focusposition.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Repräsentiert die Eigenschaft 'fill.focusposition.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Repräsentiert die Eigenschaft 'fill.focussize.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Repräsentiert die Eigenschaft 'fill.focussize.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Repräsentiert die Eigenschaft 'stroke.on'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Repräsentiert die Eigenschaft 'stroke.color'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Repräsentiert die Eigenschaft 'stroke.weight'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Repräsentiert die Eigenschaft 'stroke.opacity'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Repräsentiert die Eigenschaft 'stroke.linestyle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Repräsentiert die Eigenschaft 'stroke.dashstyle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Repräsentiert die Eigenschaft 'stroke.filltype'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Repräsentiert die Eigenschaft 'stroke.src'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Repräsentiert die Eigenschaft 'stroke.color2'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Repräsentiert die Eigenschaft 'stroke.imagesize.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Repräsentiert die Eigenschaft 'stroke.imagesize.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Repräsentiert die Eigenschaft 'stroke.startArrow'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Repräsentiert die Eigenschaft 'stroke.endArrow'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Repräsentiert die Eigenschaft 'stroke.startArrowWidth'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Repräsentiert die Eigenschaft 'stroke.startArrowLength'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Repräsentiert die Eigenschaft 'stroke.endArrowWidth'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Repräsentiert die Eigenschaft 'stroke.endArrowLength'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Repräsentiert die Eigenschaft 'shadow.on'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Repräsentiert die Eigenschaft 'shadow.type'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Repräsentiert die Eigenschaft 'shadow.color'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Repräsentiert die Eigenschaft 'shadow.color2'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Repräsentiert die Eigenschaft 'shadow.opacity'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Repräsentiert die Eigenschaft 'shadow.offset.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Repräsentiert die Eigenschaft 'shadow.offset.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Repräsentiert die Eigenschaft 'shadow.offset2.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Repräsentiert die Eigenschaft 'shadow.offset2.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Repräsentiert die Eigenschaft 'shadow.origin.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Repräsentiert die Eigenschaft 'shadow.origin.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public 

```

Repräsentiert die Eigenschaft 'shadow.matrix.xtox'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Repräsentiert die Eigenschaft 'shadow.matrix.xtoy'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Repräsentiert die Eigenschaft 'shadow.matrix.ytox'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Repräsentiert die Eigenschaft 'shadow.matrix.ytoy'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Repräsentiert die Eigenschaft 'shadow.matrix.perspectiveX'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public

```

Repräsentiert die Eigenschaft 'shadow.matrix.perspectiveY'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Repräsentiert die Eigenschaft 'skew.on'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Repräsentiert die Eigenschaft 'skew.offset.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Repräsentiert die Eigenschaft 'skew.offset.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Repräsentiert die Eigenschaft 'skew.origin.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Repräsentiert die Eigenschaft 'skew.origin.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Repräsentiert die Eigenschaft 'skew.matrix.xtox'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Repräsentiert die Eigenschaft 'skew.matrix.xtoy'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Repräsentiert die Eigenschaft 'skew.matrix.ytox'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Repräsentiert die Eigenschaft 'skew.matrix.ytoy'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Repräsentiert die Eigenschaft 'skew.matrix.perspectiveX'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Repräsentiert die Eigenschaft 'skew.matrix.perspectiveY'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Repräsentiert die Eigenschaft 'extrusion.on'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Repräsentiert die Eigenschaft 'extrusion.type'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Repräsentiert die Eigenschaft 'extrusion.render'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Repräsentiert die Eigenschaft 'extrusion.viewpointorigin.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Repräsentiert die Eigenschaft 'extrusion.viewpointorigin.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Repräsentiert die Eigenschaft 'extrusion.viewpoint.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```




```

Repräsentiert die Eigenschaft 'extrusion.viewpoint.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Repräsentiert die Eigenschaft 'extrusion.viewpoint.z'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Repräsentiert die Eigenschaft 'extrusion.plane'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```

```

Repräsentiert die Eigenschaft 'extrusion.skewangle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Repräsentiert die Eigenschaft 'extrusion.skewamt'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Repräsentiert die Eigenschaft 'extrusion.backdepth'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Repräsentiert die Eigenschaft 'extrusion.foredepth'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Repräsentiert die Eigenschaft 'extrusion.orientation.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Repräsentiert die Eigenschaft 'extrusion.orientation.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Repräsentiert die Eigenschaft 'extrusion.orientation.z'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Repräsentiert die Eigenschaft 'extrusion.orientationangle'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public 

```

Repräsentiert die Eigenschaft 'extrusion.color'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Repräsentiert die Eigenschaft 'extrusion.rotationangle.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Repräsentiert die Eigenschaft 'extrusion.rotationangle.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Repräsentiert die Eigenschaft 'extrusion.lockrotationcenter'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Repräsentiert die Eigenschaft 'extrusion.autorotationcenter'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Repräsentiert die Eigenschaft 'extrusion.rotationcenter.x'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Repräsentiert die Eigenschaft 'extrusion.rotationcenter.y'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Repräsentiert die Eigenschaft 'extrusion.rotationcenter.z'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Repräsentiert die Eigenschaft 'extrusion.colormode'

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Überprüft, ob dieses Objekt einem anderen gleich ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das zu vergleichende Objekt. |

**Rückgabe:**
boolean - True, wenn Objekte gleich sind.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Berechnet und gibt den Hashcode basierend auf der (\#getValue.getValue) Eigenschaft zurück

**Rückgabe:**
int - Gibt den Hashcode für dieses Objekt zurück

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Sucht nach einer vorhandenen Verhaltenseigenschaft anhand des Werts oder erstellt eine neue benutzerdefinierte mit dem angegebenen Wert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der Eigenschaft |

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - Instanz von BehaviorProperty