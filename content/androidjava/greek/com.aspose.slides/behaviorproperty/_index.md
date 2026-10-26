---
title: BehaviorProperty
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τύπους ιδιοτήτων για τη συμπεριφορά του animation.
type: docs
url: /el/com.aspose.slides/behaviorproperty/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Αντιπροσωπεύει τύπους ιδιοτήτων για τη συμπεριφορά του animation. Ακολουθεί τη λίστα ιδιοτήτων από https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx και https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Τιμή της ιδιότητας |
| [isCustom()](#isCustom--) | Εμφανίζει εάν αυτή η ιδιότητα δεν ανήκει στη λίστα προκαθορισμένων ιδιοτήτων στην προδιαγραφή: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Αντιπροσωπεύει την ιδιότητα 'ppt_x' |
| [getPptY()](#getPptY--) | Αντιπροσωπεύει την ιδιότητα 'ppt_y' |
| [getPptW()](#getPptW--) | Αντιπροσωπεύει την ιδιότητα 'ppt_w' |
| [getPptH()](#getPptH--) | Αντιπροσωπεύει την ιδιότητα 'ppt_h' |
| [getPptC()](#getPptC--) | Αντιπροσωπεύει την ιδιότητα 'ppt_c' |
| [getPptR()](#getPptR--) | Αντιπροσωπεύει την ιδιότητα 'ppt_r' |
| [getXShear()](#getXShear--) | Αντιπροσωπεύει την ιδιότητα 'xshear' |
| [getYShear()](#getYShear--) | Αντιπροσωπεύει την ιδιότητα 'yshear' |
| [getImage()](#getImage--) | Αντιπροσωπεύει την ιδιότητα 'image' |
| [getScaleX()](#getScaleX--) | Αντιπροσωπεύει την ιδιότητα 'ScaleX' |
| [getScaleY()](#getScaleY--) | Αντιπροσωπεύει την ιδιότητα 'ScaleY' |
| [getR()](#getR--) | Αντιπροσωπεύει την ιδιότητα 'r' |
| [getFillColor()](#getFillColor--) | Αντιπροσωπεύει την ιδιότητα 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Αντιπροσωπεύει την ιδιότητα 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Αντιπροσωπεύει την ιδιότητα 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Αντιπροσωπεύει την ιδιότητα 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Αντιπροσωπεύει την ιδιότητα 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Αντιπροσωπεύει την ιδιότητα 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Αντιπροσωπεύει την ιδιότητα 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Αντιπροσωπεύει την ιδιότητα 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Αντιπροσωπεύει την ιδιότητα 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Αντιπροσωπεύει την ιδιότητα 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Αντιπροσωπεύει την ιδιότητα 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Αντιπροσωπεύει την ιδιότητα 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Αντιπροσωπεύει την ιδιότητα 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Αντιπροσωπεύει την ιδιότητα 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Αντιπροσωπεύει την ιδιότητα 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Αντιπροσωπεύει την ιδιότητα 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Αντιπροσωπεύει την ιδιότητα 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Αντιπροσωπεύει την ιδιότητα 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Αντιπροσωπεύει την ιδιότητα 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Αντιπροσωπεύει την ιδιότητα 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Αντιπροσωπεύει την ιδιότητα 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Αντιπροσωπεύει την ιδιότητα 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Αντιπροσωπεύει την ιδιότητα 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Αντιπροσωπεύει την ιδιότητα 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Αντιπροσωπεύει την ιδιότητα 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Αντιπροσωπεύει την ιδιότητα 'fill.on' |
| [getFillType()](#getFillType--) | Αντιπροσωπεύει την ιδιότητα 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Αντιπροσωπεύει την ιδιότητα 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Αντιπροσωπεύει την ιδιότητα 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Αντιπροσωπεύει την ιδιότητα 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Αντιπροσωπεύει την ιδιότητα 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Αντιπροσωπεύει την ιδιότητα 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Αντιπροσωπεύει την ιδιότητα 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Αντιπροσωπεύει την ιδιότητα 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Αντιπροσωπεύει την ιδιότητα 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Αντιπροσωπεύει την ιδιότητα 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Αντιπροσωπεύει την ιδιότητα 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Αντιπροσωπεύει την ιδιότητα 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Αντιπροσωπεύει την ιδιότητα 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Αντιπροσωπεύει την ιδιότητα 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Αντιπροσωπεύει την ιδιότητα 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Αντιπροσωπεύει την ιδιότητα 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Αντιπροσωπεύει την ιδιότητα 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Αντιπροσωπεύει την ιδιότητα 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Αντιπροσωπεύει την ιδιότητα 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Αντιπροσωπεύει την ιδιότητα 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Αντιπροσωπεύει την ιδιότητα 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Αντιπροσωπεύει την ιδιότητα 'shadow.on' |
| [getShadowType()](#getShadowType--) | Αντιπροσωπεύει την ιδιότητα 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Αντιπροσωπεύει την ιδιότητα 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Αντιπροσωπεύει την ιδιότητα 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Αντιπροσωπεύει την ιδιότητα 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Αντιπροσωπεύει την ιδιότητα 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Αντιπροσωπεύει την ιδιότητα 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Αντιπροσωπεύει την ιδιότητα 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Αντιπροσωπεύει την ιδιότητα 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Αντιπροσωπεύει την ιδιότητα 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Αντιπροσωπεύει την ιδιότητα 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Αντιπροσωπεύει την ιδιότητα 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Αντιπροσωπεύει την ιδιότητα 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Αντιπροσωπεύει την ιδιότητα 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Αντιπροσωπεύει την ιδιότητα 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Ελέγχει εάν αυτό το αντικείμενο είναι ίσο με ένα άλλο. |
| [hashCode()](#hashCode--) | Υπολογίζει και επιστρέφει κωδικό hash βασισμένο στην ιδιότητα (\#getValue.getValue) |
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

Εμφανίζει εάν αυτή η ιδιότητα δεν ανήκει στη λίστα προκαθορισμένων ιδιοτήτων στην προδιαγραφή: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Επιστρέφει:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_x'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_y'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_w'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_h'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_c'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Αντιπροσωπεύει την ιδιότητα 'ppt_r'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Αντιπροσωπεύει την ιδιότητα 'xshear'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Αντιπροσωπεύει την ιδιότητα 'yshear'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Αντιπροσωπεύει την ιδιότητα 'image'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Αντιπροσωπεύει την ιδιότητα 'ScaleX'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Αντιπροσωπεύει την ιδιότητα 'ScaleY'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Αντιπροσωπεύει την ιδιότητα 'r'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Αντιπροσωπεύει την ιδιότητα 'fillcolor'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Αντιπροσωπεύει την ιδιότητα 'style.opacity'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Αντιπροσωπεύει την ιδιότητα 'style.rotation'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Αντιπροσωπεύει την ιδιότητα 'style.visibility'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Αντιπροσωπεύει την ιδιότητα 'style.color'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Αντιπροσωπεύει την ιδιότητα 'style.fontSize'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Αντιπροσωπεύει την ιδιότητα 'style.fontWeight'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Αντιπροσωπεύει την ιδιότητα 'style.fontStyle'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Αντιπροσωπεύει την ιδιότητα 'style.fontFamily'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Αντιπροσωπεύει την ιδιότητα 'style.textEffectEmboss'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Αντιπροσωπεύει την ιδιότητα 'style.textShadow'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Αντιπροσωπεύει την ιδιότητα 'style.textTransform'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Αντιπροσωπεύει την ιδιότητα 'style.textDecorationUnderline'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Αντιπροσωπεύει την ιδιότητα 'style.textEffectOutline'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Αντιπροσωπεύει την ιδιότητα 'style.textDecorationLineThrough'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Αντιπροσωπεύει την ιδιότητα 'style.sRotation'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.cropTop'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.cropBottom'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.cropLeft'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.cropRight'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.gain'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.blacklevel'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.gamma'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.grayscale'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Αντιπροσωπεύει την ιδιότητα 'imageData.chromakey'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Αντιπροσωπεύει την ιδιότητα 'fill.on'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Αντιπροσωπεύει την ιδιότητα 'fill.type'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Αντιπροσωπεύει την ιδιότητα 'fill.color'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Αντιπροσωπεύει την ιδιότητα 'fill.opacity'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Αντιπροσωπεύει την ιδιότητα 'fill.color2'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Αντιπροσωπεύει την ιδιότητα 'fill.method'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Αντιπροσωπεύει την ιδιότητα 'fill.opacity2'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Αντιπροσωπεύει την ιδιότητα 'fill.angle'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Αντιπροσωπεύει την ιδιότητα 'fill.focus'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.x'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Αντιπροσωπεύει την ιδιότητα 'fill.focusposition.y'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Αντιπροσωπεύει την ιδιότητα 'fill.focussize.x'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Αντιπροσωπεύει την ιδιότητα 'fill.focussize.y'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.on'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.color'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.weight'

**Επιστρέφει:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.opacity'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.linestyle'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.dashstyle'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.filltype'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.src'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.color2'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.imagesize.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.startArrow'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.endArrow'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowWidth'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.startArrowLength'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowWidth'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Αντιπροσωπεύει την ιδιότητα 'stroke.endArrowLength'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.on'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.type'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.color'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.color2'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.opacity'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.offset.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.offset.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.offset2.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.origin.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.origin.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtox'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.xtoy'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytox'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.ytoy'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveX'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Αντιπροσωπεύει την ιδιότητα 'shadow.matrix.perspectiveY'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Αντιπροσωπεύει την ιδιότητα 'skew.on'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Αντιπροσωπεύει την ιδιότητα 'skew.offset.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Αντιπροσωπεύει την ιδιότητα 'skew.offset.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Αντιπροσωπεύει την ιδιότητα 'skew.origin.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Αντιπροσωπεύει την ιδιότητα 'skew.origin.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtox'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.xtoy'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytox'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.ytoy'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveX'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Αντιπροσωπεύει την ιδιότητα 'skew.matrix.perspectiveY'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.on'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.type'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.render'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpointorigin.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.viewpoint.z'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.plane'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.skewangle'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.skewamt'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.backdepth'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.foredepth'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.orientation.z'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.orientationangle'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.color'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationangle.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.lockrotationcenter'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.autorotationcenter'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.x'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.y'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.rotationcenter.z'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Αντιπροσωπεύει την ιδιότητα 'extrusion.colormode'

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ελέγχει εάν αυτό το αντικείμενο είναι ίσο με ένα άλλο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Αντικείμενο για σύγκριση. |

**Επισ Returns:**
boolean - Αληθής αν τα αντικείμενα είναι ίσα.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Υπολογίζει και επισ Returns κωδικό hash βασισμένο στην ιδιότητα (\#getValue.getValue)

**Επισ Returns:**
int - Επισ Returns κωδικό hash για αυτό το αντικείμενο
### getOrCreateByValue(java.lang.String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Αναζητά υπάρχουσα ιδιότητα συμπεριφοράς με βάση την τιμή ή δημιουργεί νέα προσαρμοσμένη με την καθορισμένη τιμή

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyValue | java.lang.String | τιμή της ιδιότητας |

**Επισ Returns:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - αντίγραφο του BehaviorProperty