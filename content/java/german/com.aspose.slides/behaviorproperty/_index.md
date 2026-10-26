---
title: BehaviorProperty
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Eigenschaftstypen für das Animationsverhalten dar.
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

Stellt Property-Typen für Animationsverhalten dar. Folgt der Liste der Eigenschaften von https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx und https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Wert der Eigenschaft |
| [isCustom()](#isCustom--) | Zeigt an, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftsliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Stellt die Eigenschaft 'ppt\_x' dar |
| [getPptY()](#getPptY--) | Stellt die Eigenschaft 'ppt\_y' dar |
| [getPptW()](#getPptW--) | Stellt die Eigenschaft 'ppt\_w' dar |
| [getPptH()](#getPptH--) | Stellt die Eigenschaft 'ppt\_h' dar |
| [getPptC()](#getPptC--) | Stellt die Eigenschaft 'ppt\_c' dar |
| [getPptR()](#getPptR--) | Stellt die Eigenschaft 'ppt\_r' dar |
| [getXShear()](#getXShear--) | Stellt die Eigenschaft 'xshear' dar |
| [getYShear()](#getYShear--) | Stellt die Eigenschaft 'yshear' dar |
| [getImage()](#getImage--) | Stellt die Eigenschaft 'image' dar |
| [getScaleX()](#getScaleX--) | Stellt die Eigenschaft 'ScaleX' dar |
| [getScaleY()](#getScaleY--) | Stellt die Eigenschaft 'ScaleY' dar |
| [getR()](#getR--) | Stellt die Eigenschaft 'r' dar |
| [getFillColor()](#getFillColor--) | Stellt die Eigenschaft 'fillcolor' dar |
| [getStyleOpacity()](#getStyleOpacity--) | Stellt die Eigenschaft 'style.opacity' dar |
| [getStyleRotation()](#getStyleRotation--) | Stellt die Eigenschaft 'style.rotation' dar |
| [getStyleVisibility()](#getStyleVisibility--) | Stellt die Eigenschaft 'style.visibility' dar |
| [getStyleColor()](#getStyleColor--) | Stellt die Eigenschaft 'style.color' dar |
| [getStyleFontSize()](#getStyleFontSize--) | Stellt die Eigenschaft 'style.fontSize' dar |
| [getStyleFontWeight()](#getStyleFontWeight--) | Stellt die Eigenschaft 'style.fontWeight' dar |
| [getStyleFontStyle()](#getStyleFontStyle--) | Stellt die Eigenschaft 'style.fontStyle' dar |
| [getStyleFontFamily()](#getStyleFontFamily--) | Stellt die Eigenschaft 'style.fontFamily' dar |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Stellt die Eigenschaft 'style.textEffectEmboss' dar |
| [getStyleTextShadow()](#getStyleTextShadow--) | Stellt die Eigenschaft 'style.textShadow' dar |
| [getStyleTextTransform()](#getStyleTextTransform--) | Stellt die Eigenschaft 'style.textTransform' dar |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Stellt die Eigenschaft 'style.textDecorationUnderline' dar |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Stellt die Eigenschaft 'style.textEffectOutline' dar |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Stellt die Eigenschaft 'style.textDecorationLineThrough' dar |
| [getStyleSRotation()](#getStyleSRotation--) | Stellt die Eigenschaft 'style.sRotation' dar |
| [getImageDataCropTop()](#getImageDataCropTop--) | Stellt die Eigenschaft 'imageData.cropTop' dar |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Stellt die Eigenschaft 'imageData.cropBottom' dar |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Stellt die Eigenschaft 'imageData.cropLeft' dar |
| [getImageDataCropRight()](#getImageDataCropRight--) | Stellt die Eigenschaft 'imageData.cropRight' dar |
| [getImageDataGain()](#getImageDataGain--) | Stellt die Eigenschaft 'imageData.gain' dar |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Stellt die Eigenschaft 'imageData.blacklevel' dar |
| [getImageDataGamma()](#getImageDataGamma--) | Stellt die Eigenschaft 'imageData.gamma' dar |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Stellt die Eigenschaft 'imageData.grayscale' dar |
| [getImageDataChromakey()](#getImageDataChromakey--) | Stellt die Eigenschaft 'imageData.chromakey' dar |
| [getFillOn()](#getFillOn--) | Stellt die Eigenschaft 'fill.on' dar |
| [getFillType()](#getFillType--) | Stellt die Eigenschaft 'fill.type' dar |
| [getFill_Color()](#getFill-Color--) | Stellt die Eigenschaft 'fill.color' dar |
| [getFillOpacity()](#getFillOpacity--) | Stellt die Eigenschaft 'fill.opacity' dar |
| [getFillColor2()](#getFillColor2--) | Stellt die Eigenschaft 'fill.color2' dar |
| [getFillMethod()](#getFillMethod--) | Stellt die Eigenschaft 'fill.method' dar |
| [getFillOpacity2()](#getFillOpacity2--) | Stellt die Eigenschaft 'fill.opacity2' dar |
| [getFillAngle()](#getFillAngle--) | Stellt die Eigenschaft 'fill.angle' dar |
| [getFillFocus()](#getFillFocus--) | Stellt die Eigenschaft 'fill.focus' dar |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Stellt die Eigenschaft 'fill.focusposition.x' dar |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Stellt die Eigenschaft 'fill.focusposition.y' dar |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Stellt die Eigenschaft 'fill.focussize.x' dar |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Stellt die Eigenschaft 'fill.focussize.y' dar |
| [getStrokeOn()](#getStrokeOn--) | Stellt die Eigenschaft 'stroke.on' dar |
| [getStrokeColor()](#getStrokeColor--) | Stellt die Eigenschaft 'stroke.color' dar |
| [getStrokeWeight()](#getStrokeWeight--) | Stellt die Eigenschaft 'stroke.weight' dar |
| [getStrokeOpacity()](#getStrokeOpacity--) | Stellt die Eigenschaft 'stroke.opacity' dar |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Stellt die Eigenschaft 'stroke.linestyle' dar |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Stellt die Eigenschaft 'stroke.dashstyle' dar |
| [getStrokeFillType()](#getStrokeFillType--) | Stellt die Eigenschaft 'stroke.filltype' dar |
| [getStrokeSrc()](#getStrokeSrc--) | Stellt die Eigenschaft 'stroke.src' dar |
| [getStrokeColor2()](#getStrokeColor2--) | Stellt die Eigenschaft 'stroke.color2' dar |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Stellt die Eigenschaft 'stroke.imagesize.x' dar |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Stellt die Eigenschaft 'stroke.imagesize.y' dar |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Stellt die Eigenschaft 'stroke.startArrow' dar |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Stellt die Eigenschaft 'stroke.endArrow' dar |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Stellt die Eigenschaft 'stroke.startArrowWidth' dar |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Stellt die Eigenschaft 'stroke.startArrowLength' dar |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Stellt die Eigenschaft 'stroke.endArrowWidth' dar |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Stellt die Eigenschaft 'stroke.endArrowLength' dar |
| [getShadowOn()](#getShadowOn--) | Stellt die Eigenschaft 'shadow.on' dar |
| [getShadowType()](#getShadowType--) | Stellt die Eigenschaft 'shadow.type' dar |
| [getShadowColor()](#getShadowColor--) | Stellt die Eigenschaft 'shadow.color' dar |
| [getShadowColor2()](#getShadowColor2--) | Stellt die Eigenschaft 'shadow.color2' dar |
| [getShadowOpacity()](#getShadowOpacity--) | Stellt die Eigenschaft 'shadow.opacity' dar |
| [getShadowOffsetX()](#getShadowOffsetX--) | Stellt die Eigenschaft 'shadow.offset.x' dar |
| [getShadowOffsetY()](#getShadowOffsetY--) | Stellt die Eigenschaft 'shadow.offset.y' dar |
| [getShadowOffset2X()](#getShadowOffset2X--) | Stellt die Eigenschaft 'shadow.offset2.x' dar |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Stellt die Eigenschaft 'shadow.offset2.y' dar |
| [getShadowOriginX()](#getShadowOriginX--) | Stellt die Eigenschaft 'shadow.origin.x' dar |
| [getShadowOriginY()](#getShadowOriginY--) | Stellt die Eigenschaft 'shadow.origin.y' dar |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Stellt die Eigenschaft 'shadow.matrix.xtox' dar |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Stellt die Eigenschaft 'shadow.matrix.xtoy' dar |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Stellt die Eigenschaft 'shadow.matrix.ytox' dar |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Stellt die Eigenschaft 'shadow.matrix.ytoy' dar |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Stellt die Eigenschaft 'shadow.matrix.perspectiveX' dar |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Stellt die Eigenschaft 'shadow.matrix.perspectiveY' dar |
| [getSkewOn()](#getSkewOn--) | Stellt die Eigenschaft 'skew.on' dar |
| [getSkewOffsetX()](#getSkewOffsetX--) | Stellt die Eigenschaft 'skew.offset.x' dar |
| [getSkewOffsetY()](#getSkewOffsetY--) | Stellt die Eigenschaft 'skew.offset.y' dar |
| [getSkewOriginX()](#getSkewOriginX--) | Stellt die Eigenschaft 'skew.origin.x' dar |
| [getSkewOriginY()](#getSkewOriginY--) | Stellt die Eigenschaft 'skew.origin.y' dar |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Stellt die Eigenschaft 'skew.matrix.xtox' dar |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Stellt die Eigenschaft 'skew.matrix.xtoy' dar |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Stellt die Eigenschaft 'skew.matrix.ytox' dar |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Stellt die Eigenschaft 'skew.matrix.ytoy' dar |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Stellt die Eigenschaft 'skew.matrix.perspectiveX' dar |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Stellt die Eigenschaft 'skew.matrix.perspectiveY' dar |
| [getExtrusionOn()](#getExtrusionOn--) | Stellt die Eigenschaft 'extrusion.on' dar |
| [getExtrusionType()](#getExtrusionType--) | Stellt die Eigenschaft 'extrusion.type' dar |
| [getExtrusionRender()](#getExtrusionRender--) | Stellt die Eigenschaft 'extrusion.render' dar |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Stellt die Eigenschaft 'extrusion.viewpointorigin.x' dar |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Stellt die Eigenschaft 'extrusion.viewpointorigin.y' dar |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Stellt die Eigenschaft 'extrusion.viewpoint.x' dar |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Stellt die Eigenschaft 'extrusion.viewpoint.y' dar |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Stellt die Eigenschaft 'extrusion.viewpoint.z' dar |
| [getExtrusionPlane()](#getExtrusionPlane--) | Stellt die Eigenschaft 'extrusion.plane' dar |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Stellt die Eigenschaft 'extrusion.skewangle' dar |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Stellt die Eigenschaft 'extrusion.skewamt' dar |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Stellt die Eigenschaft 'extrusion.backdepth' dar |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Stellt die Eigenschaft 'extrusion.foredepth' dar |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Stellt die Eigenschaft 'extrusion.orientation.x' dar |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Stellt die Eigenschaft 'extrusion.orientation.y' dar |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Stellt die Eigenschaft 'extrusion.orientation.z' dar |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Stellt die Eigenschaft 'extrusion.orientationangle' dar |
| [getExtrusionColor()](#getExtrusionColor--) | Stellt die Eigenschaft 'extrusion.color' dar |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Stellt die Eigenschaft 'extrusion.rotationangle.x' dar |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Stellt die Eigenschaft 'extrusion.rotationangle.y' dar |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Stellt die Eigenschaft 'extrusion.lockrotationcenter' dar |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Stellt die Eigenschaft 'extrusion.autorotationcenter' dar |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Stellt die Eigenschaft 'extrusion.rotationcenter.x' dar |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Stellt die Eigenschaft 'extrusion.rotationcenter.y' dar |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Stellt die Eigenschaft 'extrusion.rotationcenter.z' dar |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Stellt die Eigenschaft 'extrusion.colormode' dar |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob dieses Objekt einem anderen gleich ist. |
| [hashCode()](#hashCode--) | Berechnet und gibt den Hashcode basierend auf der (\#getValue.getValue) Eigenschaft zurück |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Sucht nach einer bestehenden Verhaltens-Eigenschaft nach Wert oder erstellt eine neue benutzerdefinierte mit dem angegebenen Wert |

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

Zeigt an, ob diese Eigenschaft nicht zur vordefinierten Eigenschaftsliste in der Spezifikation gehört: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Rückgabe:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Stellt die Eigenschaft 'ppt\_x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Stellt die Eigenschaft 'ppt\_y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Stellt die Eigenschaft 'ppt\_w' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Stellt die Eigenschaft 'ppt\_h' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Stellt die Eigenschaft 'ppt\_c' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Stellt die Eigenschaft 'ppt\_r' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Stellt die Eigenschaft 'xshear' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Stellt die Eigenschaft 'yshear' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Stellt die Eigenschaft 'image' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Stellt die Eigenschaft 'ScaleX' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Stellt die Eigenschaft 'ScaleY' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Stellt die Eigenschaft 'r' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Stellt die Eigenschaft 'fillcolor' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Stellt die Eigenschaft 'style.opacity' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Stellt die Eigenschaft 'style.rotation' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Stellt die Eigenschaft 'style.visibility' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Stellt die Eigenschaft 'style.color' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Stellt die Eigenschaft 'style.fontSize' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Stellt die Eigenschaft 'style.fontWeight' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Stellt die Eigenschaft 'style.fontStyle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Stellt die Eigenschaft 'style.fontFamily' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Stellt die Eigenschaft 'style.textEffectEmboss' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Stellt die Eigenschaft 'style.textShadow' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Stellt die Eigenschaft 'style.textTransform' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Stellt die Eigenschaft 'style.textDecorationUnderline' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Stellt die Eigenschaft 'style.textEffectOutline' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Stellt die Eigenschaft 'style.textDecorationLineThrough' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Stellt die Eigenschaft 'style.sRotation' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Stellt die Eigenschaft 'imageData.cropTop' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Stellt die Eigenschaft 'imageData.cropBottom' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Stellt die Eigenschaft 'imageData.cropLeft' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Stellt die Eigenschaft 'imageData.cropRight' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Stellt die Eigenschaft 'imageData.gain' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Stellt die Eigenschaft 'imageData.blacklevel' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Stellt die Eigenschaft 'imageData.gamma' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Stellt die Eigenschaft 'imageData.grayscale' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Stellt die Eigenschaft 'imageData.chromakey' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Stellt die Eigenschaft 'fill.on' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Stellt die Eigenschaft 'fill.type' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Stellt die Eigenschaft 'fill.color' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Stellt die Eigenschaft 'fill.opacity' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Stellt die Eigenschaft 'fill.color2' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Stellt die Eigenschaft 'fill.method' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Stellt die Eigenschaft 'fill.opacity2' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Stellt die Eigenschaft 'fill.angle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Stellt die Eigenschaft 'fill.focus' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Stellt die Eigenschaft 'fill.focusposition.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Stellt die Eigenschaft 'fill.focusposition.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Stellt die Eigenschaft 'fill.focussize.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Stellt die Eigenschaft 'fill.focussize.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Stellt die Eigenschaft 'stroke.on' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Stellt die Eigenschaft 'stroke.color' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Stellt die Eigenschaft 'stroke.weight' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Stellt die Eigenschaft 'stroke.opacity' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Stellt die Eigenschaft 'stroke.linestyle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Stellt die Eigenschaft 'stroke.dashstyle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Stellt die Eigenschaft 'stroke.filltype' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Stellt die Eigenschaft 'stroke.src' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Stellt die Eigenschaft 'stroke.color2' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Stellt die Eigenschaft 'stroke.imagesize.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Stellt die Eigenschaft 'stroke.imagesize.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Stellt die Eigenschaft 'stroke.startArrow' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Stellt die Eigenschaft 'stroke.endArrow' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Stellt die Eigenschaft 'stroke.startArrowWidth' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Stellt die Eigenschaft 'stroke.startArrowLength' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Stellt die Eigenschaft 'stroke.endArrowWidth' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Stellt die Eigenschaft 'stroke.endArrowLength' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Stellt die Eigenschaft 'shadow.on' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Stellt die Eigenschaft 'shadow.type' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Stellt die Eigenschaft 'shadow.color' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Stellt die Eigenschaft 'shadow.color2' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Stellt die Eigenschaft 'shadow.opacity' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Stellt die Eigenschaft 'shadow.offset.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Stellt die Eigenschaft 'shadow.offset.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Stellt die Eigenschaft 'shadow.offset2.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Stellt die Eigenschaft 'shadow.offset2.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Stellt die Eigenschaft 'shadow.origin.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Stellt die Eigenschaft 'shadow.origin.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Stellt die Eigenschaft 'shadow.matrix.xtox' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Stellt die Eigenschaft 'shadow.matrix.xtoy' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Stellt die Eigenschaft 'shadow.matrix.ytox' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Stellt die Eigenschaft 'shadow.matrix.ytoy' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Stellt die Eigenschaft 'shadow.matrix.perspectiveX' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Stellt die Eigenschaft 'shadow.matrix.perspectiveY' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Stellt die Eigenschaft 'skew.on' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Stellt die Eigenschaft 'skew.offset.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Stellt die Eigenschaft 'skew.offset.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Stellt die Eigenschaft 'skew.origin.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Stellt die Eigenschaft 'skew.origin.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Stellt die Eigenschaft 'skew.matrix.xtox' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Stellt die Eigenschaft 'skew.matrix.xtoy' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Stellt die Eigenschaft 'skew.matrix.ytox' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Stellt die Eigenschaft 'skew.matrix.ytoy' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Stellt die Eigenschaft 'skew.matrix.perspectiveX' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Stellt die Eigenschaft 'skew.matrix.perspectiveY' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Stellt die Eigenschaft 'extrusion.on' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Stellt die Eigenschaft 'extrusion.type' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Stellt die Eigenschaft 'extrusion.render' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Stellt die Eigenschaft 'extrusion.viewpointorigin.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Stellt die Eigenschaft 'extrusion.viewpointorigin.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Stellt die Eigenschaft 'extrusion.viewpoint.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Stellt die Eigenschaft 'extrusion.viewpoint.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Stellt die Eigenschaft 'extrusion.viewpoint.z' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Stellt die Eigenschaft 'extrusion.plane' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Stellt die Eigenschaft 'extrusion.skewangle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Stellt die Eigenschaft 'extrusion.skewamt' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Stellt die Eigenschaft 'extrusion.backdepth' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Stellt die Eigenschaft 'extrusion.foredepth' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Stellt die Eigenschaft 'extrusion.orientation.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Stellt die Eigenschaft 'extrusion.orientation.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Stellt die Eigenschaft 'extrusion.orientation.z' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Stellt die Eigenschaft 'extrusion.orientationangle' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Stellt die Eigenschaft 'extrusion.color' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Stellt die Eigenschaft 'extrusion.rotationangle.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Stellt die Eigenschaft 'extrusion.rotationangle.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Stellt die Eigenschaft 'extrusion.lockrotationcenter' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Stellt die Eigenschaft 'extrusion.autorotationcenter' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Stellt die Eigenschaft 'extrusion.rotationcenter.x' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Stellt die Eigenschaft 'extrusion.rotationcenter.y' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Stellt die Eigenschaft 'extrusion.rotationcenter.z' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Stellt die Eigenschaft 'extrusion.colormode' dar

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Überprüft, ob dieses Objekt einem anderen Objekt entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Zu vergleichendes Objekt. |

**Rückgabe:**
boolean - true, wenn die Objekte gleich sind.
### hashCode() {#hashCode--}
```
public boolean equals(Object obj)
```

Berechnet und gibt den Hash-Code basierend auf der (\#getValue.getValue) Eigenschaft zurück.

**Rückgabe:**
int - Gibt den Hash-Code für dieses Objekt zurück
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Sucht nach einer vorhandenen Verhaltenseigenschaft nach Wert oder erstellt eine neue benutzerdefinierte mit dem angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der Eigenschaft |

**Rückgabe:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - Instanz von BehaviorProperty