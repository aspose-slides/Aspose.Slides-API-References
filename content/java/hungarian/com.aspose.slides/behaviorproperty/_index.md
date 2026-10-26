---
title: BehaviorProperty
second_title: Aspose.Slides Java API referencia
description: Az animációs viselkedés tulajdonságtípusainak ábrázolása.
type: docs
url: /hu/com.aspose.slides/behaviorproperty/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Az animáció viselkedésének tulajdonságtípusait képviseli. Követi a tulajdonságok listáját a https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx és https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx oldalról
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getValue()](#getValue--) | A tulajdonság értéke |
| [isCustom()](#isCustom--) | Megmutatja, ha ez a tulajdonság nem tartozik a specifikáció előre definiált tulajdonságlistájához: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | A 'ppt_x' tulajdonságot képviseli |
| [getPptY()](#getPptY--) | A 'ppt_y' tulajdonságot képviseli |
| [getPptW()](#getPptW--) | A 'ppt_w' tulajdonságot képviseli |
| [getPptH()](#getPptH--) | A 'ppt_h' tulajdonságot képviseli |
| [getPptC()](#getPptC--) | A 'ppt_c' tulajdonságot képviseli |
| [getPptR()](#getPptR--) | A 'ppt_r' tulajdonságot képviseli |
| [getXShear()](#getXShear--) | Az 'xshear' tulajdonságot képviseli |
| [getYShear()](#getYShear--) | Az 'yshear' tulajdonságot képviseli |
| [getImage()](#getImage--) | Az 'image' tulajdonságot képviseli |
| [getScaleX()](#getScaleX--) | A 'ScaleX' tulajdonságot képviseli |
| [getScaleY()](#getScaleY--) | A 'ScaleY' tulajdonságot képviseli |
| [getR()](#getR--) | Az 'r' tulajdonságot képviseli |
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
| [getImageDataCropTop()](#getImageDataCropTop--) | Az 'imageData.cropTop' tulajdonságot képviseli |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Az 'imageData.cropBottom' tulajdonságot képviseli |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Az 'imageData.cropLeft' tulajdonságot képviseli |
| [getImageDataCropRight()](#getImageDataCropRight--) | Az 'imageData.cropRight' tulajdonságot képviseli |
| [getImageDataGain()](#getImageDataGain--) | Az 'imageData.gain' tulajdonságot képviseli |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Az 'imageData.blacklevel' tulajdonságot képviseli |
| [getImageDataGamma()](#getImageDataGamma--) | Az 'imageData.gamma' tulajdonságot képviseli |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Az 'imageData.grayscale' tulajdonságot képviseli |
| [getImageDataChromakey()](#getImageDataChromakey--) | Az 'imageData.chromakey' tulajdonságot képviseli |
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
| [getExtrusionOn()](#getExtrusionOn--) | Az 'extrusion.on' tulajdonságot képviseli |
| [getExtrusionType()](#getExtrusionType--) | Az 'extrusion.type' tulajdonságot képviseli |
| [getExtrusionRender()](#getExtrusionRender--) | Az 'extrusion.render' tulajdonságot képviseli |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Az 'extrusion.viewpointorigin.x' tulajdonságot képviseli |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Az 'extrusion.viewpointorigin.y' tulajdonságot képviseli |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Az 'extrusion.viewpoint.x' tulajdonságot képviseli |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Az 'extrusion.viewpoint.y' tulajdonságot képviseli |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Az 'extrusion.viewpoint.z' tulajdonságot képviseli |
| [getExtrusionPlane()](#getExtrusionPlane--) | Az 'extrusion.plane' tulajdonságot képviseli |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Az 'extrusion.skewangle' tulajdonságot képviseli |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Az 'extrusion.skewamt' tulajdonságot képviseli |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Az 'extrusion.backdepth' tulajdonságot képviseli |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Az 'extrusion.foredepth' tulajdonságot képviseli |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Az 'extrusion.orientation.x' tulajdonságot képviseli |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Az 'extrusion.orientation.y' tulajdonságot képviseli |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Az 'extrusion.orientation.z' tulajdonságot képviseli |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Az 'extrusion.orientationangle' tulajdonságot képviseli |
| [getExtrusionColor()](#getExtrusionColor--) | Az 'extrusion.color' tulajdonságot képviseli |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Az 'extrusion.rotationangle.x' tulajdonságot képviseli |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Az 'extrusion.rotationangle.y' tulajdonságot képviseli |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Az 'extrusion.lockrotationcenter' tulajdonságot képviseli |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Az 'extrusion.autorotationcenter' tulajdonságot képviseli |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Az 'extrusion.rotationcenter.x' tulajdonságot képviseli |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Az 'extrusion.rotationcenter.y' tulajdonságot képviseli |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Az 'extrusion.rotationcenter.z' tulajdonságot képviseli |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Az 'extrusion.colormode' tulajdonságot képviseli |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi, hogy ez az objektum egyenlő-e egy másikkal. |
| [hashCode()](#hashCode--) | Számolja ki és adja vissza a hach kódot a (\#getValue.getValue) tulajdonság alapján |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Megkeresi a meglévő viselkedéstulajdonságot érték alapján, vagy létrehozza az új egyedi tulajdonságot a megadott értékkel |

### getValue() {#getValue--}
```
public final String getValue()
```

A tulajdonság értéke

**Visszaad:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Megmutatja, ha ez a tulajdonság nem tartozik a specifikáció előre definiált tulajdonságlistájához: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Visszaad:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

A 'ppt_x' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

A 'ppt_y' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

A 'ppt_w' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

A 'ppt_h' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

A 'ppt_c' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

A 'ppt_r' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Az 'xshear' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Az 'yshear' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Az 'image' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

A 'ScaleX' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

A 'ScaleY' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Az 'r' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

A 'fillcolor' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

A 'style.opacity' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

A 'style.rotation' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

A 'style.visibility' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

A 'style.color' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

A 'style.fontSize' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

A 'style.fontWeight' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

A 'style.fontStyle' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

A 'style.fontFamily' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

A 'style.textEffectEmboss' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

A 'style.textShadow' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

A 'style.textTransform' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

A 'style.textDecorationUnderline' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

A 'style.textEffectOutline' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

A 'style.textDecorationLineThrough' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

A 'style.sRotation' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Az 'imageData.cropTop' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Az 'imageData.cropBottom' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Az 'imageData.cropLeft' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Az 'imageData.cropRight' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Az 'imageData.gain' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Az 'imageData.blacklevel' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Az 'imageData.gamma' tulajdonságot képviseli

**Visszaad:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


Representálja az 'imageData.grayscale' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


Representálja az 'imageData.chromakey' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


Representálja a 'fill.on' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


Representálja a 'fill.type' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


Representálja a 'fill.color' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


Representálja a 'fill.opacity' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


Representálja a 'fill.color2' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


Representálja a 'fill.method' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


Representálja a 'fill.opacity2' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


Representálja a 'fill.angle' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


Representálja a 'fill.focus' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


Representálja a 'fill.focusposition.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


Representálja a 'fill.focusposition.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


Representálja a 'fill.focussize.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


Representálja a 'fill.focussize.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


Representálja a 'stroke.on' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


Representálja a 'stroke.color' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


Representálja a 'stroke.weight' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


Representálja a 'stroke.opacity' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


Representálja a 'stroke.linestyle' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


Representálja a 'stroke.dashstyle' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


Representálja a 'stroke.filltype' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


Representálja a 'stroke.src' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


Representálja a 'stroke.color2' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


Representálja a 'stroke.imagesize.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


Representálja a 'stroke.imagesize.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


Representálja a 'stroke.startArrow' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


Representálja a 'stroke.endArrow' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


Representálja a 'stroke.startArrowWidth' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


Representálja a 'stroke.startArrowLength' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


Representálja a 'stroke.endArrowWidth' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


Representálja a 'stroke.endArrowLength' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


Representálja a 'shadow.on' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


Representálja a 'shadow.type' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


Representálja a 'shadow.color' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


Representálja a 'shadow.color2' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


Representálja a 'shadow.opacity' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


Representálja a 'shadow.offset.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


Representálja a 'shadow.offset.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


Representálja a 'shadow.offset2.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


Representálja a 'shadow.offset2.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


Representálja a 'shadow.origin.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


Representálja a 'shadow.origin.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Representálja a 'shadow.matrix.xtox' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


Representálja a 'shadow.matrix.xtoy' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


Representálja a 'shadow.matrix.ytox' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


Representálja a 'shadow.matrix.ytoy' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


Representálja a 'shadow.matrix.perspectiveX' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


Representálja a 'shadow.matrix.perspectiveY' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


Representálja a 'skew.on' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


Representálja a 'skew.offset.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


Representálja a 'skew.offset.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


Representálja a 'skew.origin.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


Representálja a 'skew.origin.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


Representálja a 'skew.matrix.xtox' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


Representálja a 'skew.matrix.xtoy' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


Representálja a 'skew.matrix.ytox' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


Representálja a 'skew.matrix.ytoy' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


Representálja a 'skew.matrix.perspectiveX' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


Representálja a 'skew.matrix.perspectiveY' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


Representálja az 'extrusion.on' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


Representálja az 'extrusion.type' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


Representálja az 'extrusion.render' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


Representálja az 'extrusion.viewpointorigin.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


Representálja az 'extrusion.viewpointorigin.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


Representálja az 'extrusion.viewpoint.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


Representálja az 'extrusion.viewpoint.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


Representálja az 'extrusion.viewpoint.z' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


Representálja az 'extrusion.plane' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


Representálja az 'extrusion.skewangle' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


Representálja az 'extrusion.skewamt' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


Representálja az 'extrusion.backdepth' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


Representálja az 'extrusion.foredepth' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


Representálja az 'extrusion.orientation.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


Representálja az 'extrusion.orientation.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


Representálja az 'extrusion.orientation.z' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


Representálja az 'extrusion.orientationangle' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


Representálja az 'extrusion.color' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


Representálja az 'extrusion.rotationangle.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


Representálja az 'extrusion.rotationangle.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


Representálja az 'extrusion.lockrotationcenter' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


Representálja az 'extrusion.autorotationcenter' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


Representálja az 'extrusion.rotationcenter.x' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


Representálja az 'extrusion.rotationcenter.y' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


Representálja az 'extrusion.rotationcenter.z' tulajdonságot

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


Representálja az 'extrusion.colormode' tulajdonságot

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
| obj | java.lang.Object | Összehasonlítandó objektum. |

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


Megkeresi a meglévő viselkedéstulajdonságot az érték alapján, vagy létrehoz egy új egyéni tulajdonságot a megadott értékkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |

**Visszatér:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - a BehaviorProperty példány