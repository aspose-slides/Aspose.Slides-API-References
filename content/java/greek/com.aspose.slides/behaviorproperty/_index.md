---
title: BehaviorProperty
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά τύπους ιδιοτήτων για τη συμπεριφορά της κίνησης.
type: docs
url: /el/com.aspose.slides/behaviorproperty/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Αντιπροσωπεύει τύπους ιδιοτήτων για τη συμπεριφορά animation. Ακολουθεί τη λίστα ιδιοτήτων από https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx και https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Τιμή της ιδιότητας |
| [isCustom()](#isCustom--) | Δείχνει αν αυτή η ιδιότητα δεν ανήκει στη λίστα προ-ορισμένων ιδιοτήτων στην προδιαγραφή: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Αναπαριστά την ιδιότητα 'ppt\_x' |
| [getPptY()](#getPptY--) | Αναπαριστά την ιδιότητα 'ppt\_y' |
| [getPptW()](#getPptW--) | Αναπαριστά την ιδιότητα 'ppt\_w' |
| [getPptH()](#getPptH--) | Αναπαριστά την ιδιότητα 'ppt\_h' |
| [getPptC()](#getPptC--) | Αναπαριστά την ιδιότητα 'ppt\_c' |
| [getPptR()](#getPptR--) | Αναπαριστά την ιδιότητα 'ppt\_r' |
| [getXShear()](#getXShear--) | Αναπαριστά την ιδιότητα 'xshear' |
| [getYShear()](#getYShear--) | Αναπαριστά την ιδιότητα 'yshear' |
| [getImage()](#getImage--) | Αναπαριστά την ιδιότητα 'image' |
| [getScaleX()](#getScaleX--) | Αναπαριστά την ιδιότητα 'ScaleX' |
| [getScaleY()](#getScaleY--) | Αναπαριστά την ιδιότητα 'ScaleY' |
| [getR()](#getR--) | Αναπαριστά την ιδιότητα 'r' |
| [getFillColor()](#getFillColor--) | Αναπαριστά την ιδιότητα 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Αναπαριστά την ιδιότητα 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Αναπαριστά την ιδιότητα 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Αναπαριστά την ιδιότητα 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Αναπαριστά την ιδιότητα 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Αναπαριστά την ιδιότητα 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Αναπαριστά την ιδιότητα 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Αναπαριστά την ιδιότητα 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Αναπαριστά την ιδιότητα 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Αναπαριστά την ιδιότητα 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Αναπαριστά την ιδιότητα 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Αναπαριστά την ιδιότητα 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Αναπαριστά την ιδιότητα 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Αναπαριστά την ιδιότητα 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Αναπαριστά την ιδιότητα 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Αναπαριστά την ιδιότητα 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Αναπαριστά την ιδιότητα 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Αναπαριστά την ιδιότητα 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Αναπαριστά την ιδιότητα 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Αναπαριστά την ιδιότητα 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Αναπαριστά την ιδιότητα 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Αναπαριστά την ιδιότητα 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Αναπαριστά την ιδιότητα 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Αναπαριστά την ιδιότητα 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Αναπαριστά την ιδιότητα 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Αναπαριστά την ιδιότητα 'fill.on' |
| [getFillType()](#getFillType--) | Αναπαριστά την ιδιότητα 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Αναπαριστά την ιδιότητα 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Αναπαριστά την ιδιότητα 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Αναπαριστά την ιδιότητα 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Αναπαριστά την ιδιότητα 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Αναπαριστά την ιδιότητα 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Αναπαριστά την ιδιότητα 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Αναπαριστά την ιδιότητα 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Αναπαριστά την ιδιότητα 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Αναπαριστά την ιδιότητα 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Αναπαριστά την ιδιότητα 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Αναπαριστά την ιδιότητα 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Αναπαριστά την ιδιότητα 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Αναπαριστά την ιδιότητα 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Αναπαριστά την ιδιότητα 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Αναπαριστά την ιδιότητα 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Αναπαριστά την ιδιότητα 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Αναπαριστά την ιδιότητα 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Αναπαριστά την ιδιότητα 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Αναπαριστά την ιδιότητα 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Αναπαριστά την ιδιότητα 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Αναπαριστά την ιδιότητα 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Αναπαριστά την ιδιότητα 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Αναπαριστά την ιδιότητα 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Αναπαριστά την ιδιότητα 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Αναπαριστά την ιδιότητα 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Αναπαριστά την ιδιότητα 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Αναπαριστά την ιδιότητα 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Αναπαριστά την ιδιότητα 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Αναπαριστά την ιδιότητα 'shadow.on' |
| [getShadowType()](#getShadowType--) | Αναπαριστά την ιδιότητα 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Αναπαριστά την ιδιότητα 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Αναπαριστά την ιδιότητα 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Αναπαριστά την ιδιότητα 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Αναπαριστά την ιδιότητα 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Αναπαριστά την ιδιότητα 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Αναπαριστά την ιδιότητα 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Αναπαριστά την ιδιότητα 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Αναπαριστά την ιδιότητα 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Αναπαριστά την ιδιότητα 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Αναπαριστά την ιδιότητα 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Αναπαριστά την ιδιότητα 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Αναπαριστά την ιδιότητα 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Αναπαριστά την ιδιότητα 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Αναπαριστά την ιδιότητα 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Αναπαριστά την ιδιότητα 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Αναπαριστά την ιδιότητα 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Αναπαριστά την ιδιότητα 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Αναπαριστά την ιδιότητα 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Αναπαριστά την ιδιότητα 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Αναπαριστά την ιδιότητα 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Αναπαριστά την ιδιότητα 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Αναπαριστά την ιδιότητα 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Αναπαριστά την ιδιότητα 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Αναπαριστά την ιδιότητα 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Αναπαριστά την ιδιότητα 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Αναπαριστά την ιδιότητα 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Αναπαριστά την ιδιότητα 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Αναπαριστά την ιδιότητα 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Αναπαριστά την ιδιότητα 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Αναπαριστά την ιδιότητα 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Αναπαριστά την ιδιότητα 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Αναπαριστά την ιδιότητα 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Αναπαριστά την ιδιότητα 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Αναπαριστά την ιδιότητα 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Αναπαριστά την ιδιότητα 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Αναπαριστά την ιδιότητα 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Αναπαριστά την ιδιότητα 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Αναπαριστά την ιδιότητα 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Αναπαριστά την ιδιότητα 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Αναπαριστά την ιδιότητα 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Αναπαριστά την ιδιότητα 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Αναπαριστά την ιδιότητα 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Αναπαριστά την ιδιότητα 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Αναπαριστά την ιδιότητα 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Αναπαριστά την ιδιότητα 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Αναπαριστά την ιδιότητα 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Αναπαριστά την ιδιότητα 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Αναπαριστά την ιδιότητα 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Αναπαριστά την ιδιότητα 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Αναπαριστά την ιδιότητα 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Αναπαριστά την ιδιότητα 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Αναπαριστά την ιδιότητα 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το αντικείμενο είναι ίσο με ένα άλλο. |
| [hashCode()](#hashCode--) | Υπολογίζει και επιστρέφει κώδικα hash βασισμένο στην ιδιότητα (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Αναζητά υπάρχουσα ιδιότητα συμπεριφοράς με βάση την τιμή ή δημιουργεί νέα προσαρμοσμένη με την καθορισμένη τιμή |

### getValue() {#getValue--}
```
public final String getValue()
```


Τιμή της ιδιότητας

**Επιστρέφει:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```


Δείχνει αν αυτή η ιδιότητα δεν ανήκει στη λίστα προ-ορισμένων ιδιοτήτων στην προδιαγραφή: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Επιστρέφει:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```


Αναπαριστά την ιδιότητα 'ppt\_x'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```


Αναπαριστά την ιδιότητα 'ppt\_y'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```


Αναπαριστά την ιδιότητα 'ppt\_w'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```


Αναπαριστά την ιδιότητα 'ppt\_h'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```


Αναπαριστά την ιδιότητα 'ppt\_c'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```


Αναπαριστά την ιδιότητα 'ppt\_r'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```


Αναπαριστά την ιδιότητα 'xshear'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```


Αναπαριστά την ιδιότητα 'yshear'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```


Αναπαριστά την ιδιότητα 'image'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```


Αναπαριστά την ιδιότητα 'ScaleX'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```


Αναπαριστά την ιδιότητα 'ScaleY'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```


Αναπαριστά την ιδιότητα 'r'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```


Αναπαριστά την ιδιότητα 'fillcolor'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```


Αναπαριστά την ιδιότητα 'style.opacity'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```


Αναπαριστά την ιδιότητα 'style.rotation'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```


Αναπαριστά την ιδιότητα 'style.visibility'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```


Αναπαριστά την ιδιότητα 'style.color'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```


Αναπαριστά την ιδιότητα 'style.fontSize'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```


Αναπαριστά την ιδιότητα 'style.fontWeight'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```


Αναπαριστά την ιδιότητα 'style.fontStyle'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```


Αναπαριστά την ιδιότητα 'style.fontFamily'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```


Αναπαριστά την ιδιότητα 'style.textEffectEmboss'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```


Αναπαριστά την ιδιότητα 'style.textShadow'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```


Αναπαριστά την ιδιότητα 'style.textTransform'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```


Αναπαριστά την ιδιότητα 'style.textDecorationUnderline'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```


Αναπαριστά την ιδιότητα 'style.textEffectOutline'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```


Αναπαριστά την ιδιότητα 'style.textDecorationLineThrough'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```


Αναπαριστά την ιδιότητα 'style.sRotation'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```


Αναπαριστά την ιδιότητα 'imageData.cropTop'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```


Αναπαριστά την ιδιότητα 'imageData.cropBottom'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```


Αναπαριστά την ιδιότητα 'imageData.cropLeft'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```


Αναπαριστά την ιδιότητα 'imageData.cropRight'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```


Αναπαριστά την ιδιότητα 'imageData.gain'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```


Αναπαριστά την ιδιότητα 'imageData.blacklevel'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```


Αναπαριστά την ιδιότητα 'imageData.gamma'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```


Αντιπροσωπεύει την ιδιότητα 'imageData.grayscale' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```


Αντιπροσωπεύει την ιδιότητα 'imageData.chromakey' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```


Αντιπροσωπεύει την ιδιότητα 'fill.on' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```


Αντιπροσωπεύει την ιδιότητα 'fill.type' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```


Αντιπροσωπεύει την ιδιότητα 'fill.color' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```


Αντιπροσωπεύει την ιδιότητα 'fill.opacity' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```


Αντιπροσωπεύει την ιδιότητα 'fill.color2' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```


Αντιπροσωπεύει την ιδιότητα 'fill.method' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```


Αντιπροσωπεύει την ιδιότητα 'fill.opacity2' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```


Αντιπροσωπεύει την ιδιότητα 'fill.angle' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```


Αντιπροσωπεύει την ιδιότητα 'fill.focus' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```


Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.x' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```


Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```


Αντιπροσωπεύει την ιδιότητα 'fill.focussize.x' property

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```


Αντιπροσωπεύει την ιδιότητα 'fill.focussize.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.on' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.color' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.weight' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.opacity' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.linestyle' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.dashstyle' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.filltype' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.src' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.color2' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.startArrow' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.endArrow' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowWidth' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowLength' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowWidth' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```


Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowLength' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.on' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.type' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.color' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.color2' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.opacity' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.offset.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.offset.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.origin.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.origin.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtox' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtoy' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytox' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytoy' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveX' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```


Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveY' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```


Αντιπροσωπεύει την ιδιότητα 'skew.on' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```


Αντιπροσωπεύει την ιδιότητα 'skew.offset.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```


Αντιπροσωπεύει την ιδιότητα 'skew.offset.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```


Αντιπροσωπεύει την ιδιότητα 'skew.origin.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```


Αντιπροσωπεύει την ιδιότητα 'skew.origin.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtox' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtoy' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytox' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytoy' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveX' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```


Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveY' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.on' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.type' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.render' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.z' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.plane' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.skewangle' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.skewamt' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.backdepth' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.foredepth' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.z' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.orientationangle' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.color' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.lockrotationcenter' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.autorotationcenter' property

**Επισ Returns::
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.x' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.y' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.z' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```


Αντιπροσωπεύει την ιδιότητα 'extrusion.colormode' property

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Ελέγχει αν αυτό το αντικείμενο είναι ίσο με ένα άλλο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Αντικείμενο προς σύγκριση. |

**Επισ Returns:**
boolean - True αν τα αντικείμενα είναι ίσα.
### hashCode() {#hashCode--}
```
public boolean equals(Object obj)
```


Υπολογίζει και επισ Returns κώδικα κατακερματισμού βάσει της (\#getValue.getValue) property

**Επισ Returns:**
int - Επισ Returns κώδικα κατακερματισμού για αυτό το αντικείμενο
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```


Αναζητά υπάρχουσα ιδιότητα συμπεριφοράς βάσει τιμής ή δημιουργεί νέα προσαρμοσμένη με την καθορισμένη τιμή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | τιμή της ιδιότητας |

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - αντικείμενο τύπου BehaviorProperty