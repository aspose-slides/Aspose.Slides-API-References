---
title: BehaviorProperty
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente les types de propriétés pour le comportement d'animation.
type: docs
url: /fr/com.aspose.slides/behaviorproperty/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)  
```
public class BehaviorProperty implements IBehaviorProperty
```

Représente les types de propriétés pour le comportement d’animation. Suivi la liste des propriétés provenant de https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx et https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx  

## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue()](#getValue--) | Valeur de la propriété |
| [isCustom()](#isCustom--) | Indique si cette propriété n’appartient pas à la liste des propriétés prédéfinies dans la spécification : https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Représente la propriété 'ppt_x' |
| [getPptY()](#getPptY--) | Représente la propriété 'ppt_y' |
| [getPptW()](#getPptW--) | Représente la propriété 'ppt_w' |
| [getPptH()](#getPptH--) | Représente la propriété 'ppt_h' |
| [getPptC()](#getPptC--) | Représente la propriété 'ppt_c' |
| [getPptR()](#getPptR--) | Représente la propriété 'ppt_r' |
| [getXShear()](#getXShear--) | Représente la propriété 'xshear' |
| [getYShear()](#getYShear--) | Représente la propriété 'yshear' |
| [getImage()](#getImage--) | Représente la propriété 'image' |
| [getScaleX()](#getScaleX--) | Représente la propriété 'ScaleX' |
| [getScaleY()](#getScaleY--) | Représente la propriété 'ScaleY' |
| [getR()](#getR--) | Représente la propriété 'r' |
| [getFillColor()](#getFillColor--) | Représente la propriété 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Représente la propriété 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Représente la propriété 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Représente la propriété 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Représente la propriété 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Représente la propriété 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Représente la propriété 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Représente la propriété 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Représente la propriété 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Représente la propriété 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Représente la propriété 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Représente la propriété 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Représente la propriété 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Représente la propriété 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Représente la propriété 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Représente la propriété 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Représente la propriété 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Représente la propriété 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Représente la propriété 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Représente la propriété 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Représente la propriété 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Représente la propriété 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Représente la propriété 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Représente la propriété 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Représente la propriété 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Représente la propriété 'fill.on' |
| [getFillType()](#getFillType--) | Représente la propriété 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Représente la propriété 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Représente la propriété 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Représente la propriété 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Représente la propriété 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Représente la propriété 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Représente la propriété 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Représente la propriété 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Représente la propriété 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Représente la propriété 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Représente la propriété 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Représente la propriété 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Représente la propriété 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Représente la propriété 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Représente la propriété 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Représente la propriété 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Représente la propriété 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Représente la propriété 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Représente la propriété 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Représente la propriété 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Représente la propriété 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Représente la propriété 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Représente la propriété 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Représente la propriété 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Représente la propriété 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Représente la propriété 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Représente la propriété 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Représente la propriété 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Représente la propriété 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Représente la propriété 'shadow.on' |
| [getShadowType()](#getShadowType--) | Représente la propriété 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Représente la propriété 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Représente la propriété 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Représente la propriété 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Représente la propriété 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Représente la propriété 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Représente la propriété 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Représente la propriété 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Représente la propriété 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Représente la propriété 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Représente la propriété 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Représente la propriété 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Représente la propriété 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Représente la propriété 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Représente la propriété 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Représente la propriété 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Représente la propriété 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Représente la propriété 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Représente la propriété 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Représente la propriété 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Représente la propriété 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Représente la propriété 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Représente la propriété 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Représente la propriété 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Représente la propriété 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Représente la propriété 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Représente la propriété 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Représente la propriété 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Représente la propriété 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Représente la propriété 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Représente la propriété 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Représente la propriété 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Représente la propriété 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Représente la propriété 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Représente la propriété 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Représente la propriété 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Représente la propriété 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Représente la propriété 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Représente la propriété 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Représente la propriété 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Représente la propriété 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Représente la propriété 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Représente la propriété 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Représente la propriété 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Représente la propriété 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Représente la propriété 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Représente la propriété 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Représente la propriété 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Représente la propriété 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Représente la propriété 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Représente la propriété 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Représente la propriété 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Représente la propriété 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifie si cet objet est égal à un autre. |
| [hashCode()](#hashCode--) | Calcule et renvoie le code de hachage basé sur la propriété (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Recherche une propriété de comportement existante par valeur ou crée une nouvelle propriété personnalisée avec la valeur spécifiée |

### getValue() {#getValue--}
```
public final String getValue()
```

Valeur de la propriété  

**Renvoie :**  
java.lang.String  

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Indique si cette propriété n’appartient pas à la liste des propriétés prédéfinies dans la spécification : https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx  

**Renvoie :**  
boolean  

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Représente la propriété 'ppt_x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Représente la propriété 'ppt_y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Représente la propriété 'ppt_w'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Représente la propriété 'ppt_h'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Représente la propriété 'ppt_c'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Représente la propriété 'ppt_r'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Représente la propriété 'xshear'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Représente la propriété 'yshear'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Représente la propriété 'image'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Représente la propriété 'ScaleX'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Représente la propriété 'ScaleY'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Représente la propriété 'r'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Représente la propriété 'fillcolor'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Représente la propriété 'style.opacity'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Représente la propriété 'style.rotation'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Représente la propriété 'style.visibility'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Représente la propriété 'style.color'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Représente la propriété 'style.fontSize'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Représente la propriété 'style.fontWeight'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Représente la propriété 'style.fontStyle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Représente la propriété 'style.fontFamily'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Représente la propriété 'style.textEffectEmboss'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Représente la propriété 'style.textShadow'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Représente la propriété 'style.textTransform'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Représente la propriété 'style.textDecorationUnderline'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Représente la propriété 'style.textEffectOutline'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Représente la propriété 'style.textDecorationLineThrough'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Représente la propriété 'style.sRotation'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Représente la propriété 'imageData.cropTop'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Représente la propriété 'imageData.cropBottom'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
``` 
public static BehaviorProperty getImageDataCropLeft()
```

Représente la propriété 'imageData.cropLeft'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Représente la propriété 'imageData.cropRight'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Représente la propriété 'imageData.gain'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Représente la propriété 'imageData.blacklevel'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Représente la propriété 'imageData.gamma'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Représente la propriété 'imageData.grayscale'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Représente la propriété 'imageData.chromakey'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Représente la propriété 'fill.on'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Représente la propriété 'fill.type'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Représente la propriété 'fill.color'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Représente la propriété 'fill.opacity'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Représente la propriété 'fill.color2'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Représente la propriété 'fill.method'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Représente la propriété 'fill.opacity2'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Représente la propriété 'fill.angle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Représente la propriété 'fill.focus'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Représente la propriété 'fill.focusposition.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Représente la propriété 'fill.focusposition.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Représente la propriété 'fill.focussize.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Représente la propriété 'fill.focussize.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Représente la propriété 'stroke.on'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Représente la propriété 'stroke.color'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Représente la propriété 'stroke.weight'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Représente la propriété 'stroke.opacity'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Représente la propriété 'stroke.linestyle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Représente la propriété 'stroke.dashstyle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Représente la propriété 'stroke.filltype'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Représente la propriété 'stroke.src'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Représente la propriété 'stroke.color2'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Représente la propriété 'stroke.imagesize.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Représente la propriété 'stroke.imagesize.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Représente la propriété 'stroke.startArrow'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public
```

Représente la propriété 'stroke.endArrow'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Représente la propriété 'stroke.startArrowWidth'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Représente la propriété 'stroke.startArrowLength'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public 
```

Représente la propriété 'stroke.endArrowWidth'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Représente la propriété 'stroke.endArrowLength'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Représente la propriété 'shadow.on'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Représente la propriété 'shadow.type'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Représente la propriété 'shadow.color'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Représente la propriété 'shadow.color2'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Représente la propriété 'shadow.opacity'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Représente la propriété 'shadow.offset.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Représente la propriété 'shadow.offset.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Représente la propriété 'shadow.offset2.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Représente la propriété 'shadow.offset2.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Représente la propriété 'shadow.origin.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Représente la propriété 'shadow.origin.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Représente la propriété 'shadow.matrix.xtox'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Représente la propriété 'shadow.matrix.xtoy'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Représente la propriété 'shadow.matrix.ytox'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
...
```

Représente la propriété 'shadow.matrix.ytoy'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Représente la propriété 'shadow.matrix.perspectiveX'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Représente la propriété 'shadow.matrix.perspectiveY'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Représente la propriété 'skew.on'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Représente la propriété 'skew.offset.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Représente la propriété 'skew.offset.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Représente la propriété 'skew.origin.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Représente la propriété 'skew.origin.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Représente la propriété 'skew.matrix.xtox'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Représente la propriété 'skew.matrix.xtoy'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Représente la propriété 'skew.matrix.ytox'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Représente la propriété 'skew.matrix.ytoy'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Représente la propriété 'skew.matrix.perspectiveX'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
...
```

Représente la propriété 'skew.matrix.perspectiveY'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Représente la propriété 'extrusion.on'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Représente la propriété 'extrusion.type'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Représente la propriété 'extrusion.render'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Représente la propriété 'extrusion.viewpointorigin.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Représente la propriété 'extrusion.viewpointorigin.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Représente la propriété 'extrusion.viewpoint.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Représente la propriété 'extrusion.viewpoint.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Représente la propriété 'extrusion.viewpoint.z'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Représente la propriété 'extrusion.plane'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Représente la propriété 'extrusion.skewangle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Représente la propriété 'extrusion.skewamt'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Représente la propriété 'extrusion.backdepth'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Représente la propriété 'extrusion.foredepth'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Représente la propriété 'extrusion.orientation.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Représente la propriété 'extrusion.orientation.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Représente la propriété 'extrusion.orientation.z'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Représente la propriété 'extrusion.orientationangle'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Représente la propriété 'extrusion.color'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Représente la propriété 'extrusion.rotationangle.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Représente la propriété 'extrusion.rotationangle.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Représente la propriété 'extrusion.lockrotationcenter'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Représente la propriété 'extrusion.autorotationcenter'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Représente la propriété 'extrusion.rotationcenter.x'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Représente la propriété 'extrusion.rotationcenter.y'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Représente la propriété 'extrusion.rotationcenter.z'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Représente la propriété 'extrusion.colormode'  

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vérifie si cet objet est égal à un autre.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet à comparer. |

**Renvoie :**  
boolean - Vrai si les objets sont égaux.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Calcule et renvoie le code de hachage basé sur la propriété (\#getValue.getValue)

**Renvoie :**  
int - Retourne le code de hachage pour cet objet

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Recherche une propriété de comportement existante par valeur ou crée une nouvelle propriété personnalisée avec la valeur spécifiée

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | valeur de la propriété |

**Renvoie :**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance de BehaviorProperty