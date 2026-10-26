---
title: BehaviorProperty
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนประเภทของคุณสมบัติสำหรับพฤติกรรมแอนิเมชัน
type: docs
url: /th/com.aspose.slides/behaviorproperty/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

เป็นตัวแทนประเภทคุณสมบัติสำหรับพฤติกรรมแอนิเมชัน ตามรายการคุณสมบัติจาก https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx และ https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getValue()](#getValue--) | ค่าของคุณสมบัติ |
| [isCustom()](#isCustom--) | แสดงว่าคุณสมบัตินี้ไม่ได้อยู่ในรายการคุณสมบัติมาตรฐานตามสเปค: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | แสดงถึงคุณสมบัติ 'ppt\_x' |
| [getPptY()](#getPptY--) | แสดงถึงคุณสมบัติ 'ppt\_y' |
| [getPptW()](#getPptW--) | แสดงถึงคุณสมบัติ 'ppt\_w' |
| [getPptH()](#getPptH--) | แสดงถึงคุณสมบัติ 'ppt\_h' |
| [getPptC()](#getPptC--) | แสดงถึงคุณสมบัติ 'ppt\_c' |
| [getPptR()](#getPptR--) | แสดงถึงคุณสมบัติ 'ppt\_r' |
| [getXShear()](#getXShear--) | แสดงถึงคุณสมบัติ 'xshear' |
| [getYShear()](#getYShear--) | แสดงถึงคุณสมบัติ 'yshear' |
| [getImage()](#getImage--) | แสดงถึงคุณสมบัติ 'image' |
| [getScaleX()](#getScaleX--) | แสดงถึงคุณสมบัติ 'ScaleX' |
| [getScaleY()](#getScaleY--) | แสดงถึงคุณสมบัติ 'ScaleY' |
| [getR()](#getR--) | แสดงถึงคุณสมบัติ 'r' |
| [getFillColor()](#getFillColor--) | แสดงถึงคุณสมบัติ 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | แสดงถึงคุณสมบัติ 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | แสดงถึงคุณสมบัติ 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | แสดงถึงคุณสมบัติ 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | แสดงถึงคุณสมบัติ 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | แสดงถึงคุณสมบัติ 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | แสดงถึงคุณสมบัติ 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | แสดงถึงคุณสมบัติ 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | แสดงถึงคุณสมบัติ 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | แสดงถึงคุณสมบัติ 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | แสดงถึงคุณสมบัติ 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | แสดงถึงคุณสมบัติ 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | แสดงถึงคุณสมบัติ 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | แสดงถึงคุณสมบัติ 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | แสดงถึงคุณสมบัติ 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | แสดงถึงคุณสมบัติ 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | แสดงถึงคุณสมบัติ 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | แสดงถึงคุณสมบัติ 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | แสดงถึงคุณสมบัติ 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | แสดงถึงคุณสมบัติ 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | แสดงถึงคุณสมบัติ 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | แสดงถึงคุณสมบัติ 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | แสดงถึงคุณสมบัติ 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | แสดงถึงคุณสมบัติ 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | แสดงถึงคุณสมบัติ 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | แสดงถึงคุณสมบัติ 'fill.on' |
| [getFillType()](#getFillType--) | แสดงถึงคุณสมบัติ 'fill.type' |
| [getFill_Color()](#getFill-Color--) | แสดงถึงคุณสมบัติ 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | แสดงถึงคุณสมบัติ 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | แสดงถึงคุณสมบัติ 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | แสดงถึงคุณสมบัติ 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | แสดงถึงคุณสมบัติ 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | แสดงถึงคุณสมบัติ 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | แสดงถึงคุณสมบัติ 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | แสดงถึงคุณสมบัติ 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | แสดงถึงคุณสมบัติ 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | แสดงถึงคุณสมบัติ 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | แสดงถึงคุณสมบัติ 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | แสดงถึงคุณสมบัติ 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | แสดงถึงคุณสมบัติ 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | แสดงถึงคุณสมบัติ 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | แสดงถึงคุณสมบัติ 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | แสดงถึงคุณสมบัติ 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | แสดงถึงคุณสมบัติ 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | แสดงถึงคุณสมบัติ 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | แสดงถึงคุณสมบัติ 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | แสดงถึงคุณสมบัติ 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | แสดงถึงคุณสมบัติ 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | แสดงถึงคุณสมบัติ 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | แสดงถึงคุณสมบัติ 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | แสดงถึงคุณสมบัติ 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | แสดงถึงคุณสมบัติ 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | แสดงถึงคุณสมบัติ 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | แสดงถึงคุณสมบัติ 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | แสดงถึงคุณสมบัติ 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | แสดงถึงคุณสมบัติ 'shadow.on' |
| [getShadowType()](#getShadowType--) | แสดงถึงคุณสมบัติ 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | แสดงถึงคุณสมบัติ 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | แสดงถึงคุณสมบัติ 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | แสดงถึงคุณสมบัติ 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | แสดงถึงคุณสมบัติ 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | แสดงถึงคุณสมบัติ 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | แสดงถึงคุณสมบัติ 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | แสดงถึงคุณสมบัติ 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | แสดงถึงคุณสมบัติ 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | แสดงถึงคุณสมบัติ 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | แสดงถึงคุณสมบัติ 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | แสดงถึงคุณสมบัติ 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | แสดงถึงคุณสมบัติ 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | แสดงถึงคุณสมบัติ 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | แสดงถึงคุณสมบัติ 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | แสดงถึงคุณสมบัติ 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | แสดงถึงคุณสมบัติ 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | แสดงถึงคุณสมบัติ 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | แสดงถึงคุณสมบัติ 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | แสดงถึงคุณสมบัติ 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | แสดงถึงคุณสมบัติ 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | แสดงถึงคุณสมบัติ 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | แสดงถึงคุณสมบัติ 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | แสดงถึงคุณสมบัติ 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | แสดงถึงคุณสมบัติ 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | แสดงถึงคุณสมบัติ 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | แสดงถึงคุณสมบัติ 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | แสดงถึงคุณสมบัติ 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | แสดงถึงคุณสมบัติ 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | แสดงถึงคุณสมบัติ 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | แสดงถึงคุณสมบัติ 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | แสดงถึงคุณสมบัติ 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | แสดงถึงคุณสมบัติ 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | แสดงถึงคุณสมบัติ 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | แสดงถึงคุณสมบัติ 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | แสดงถึงคุณสมบัติ 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | แสดงถึงคุณสมบัติ 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | แสดงถึงคุณสมบัติ 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | แสดงถึงคุณสมบัติ 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | แสดงถึงคุณสมบัติ 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | แสดงถึงคุณสมบัติ 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | แสดงถึงคุณสมบัติ 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | แสดงถึงคุณสมบัติ 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | แสดงถึงคุณสมบัติ 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | แสดงถึงคุณสมบัติ 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | แสดงถึงคุณสมบัติ 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | แสดงถึงคุณสมบัติ 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | แสดงถึงคุณสมบัติ 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | แสดงถึงคุณสมบัติ 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | แสดงถึงคุณสมบัติ 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่าอ็อบเจกต์นี้เท่ากับอ็อบเจกต์อื่นหรือไม่ |
| [hashCode()](#hashCode--) | คำนวณและคืนค่า hash code ตามคุณสมบัติ (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | ค้นหาคุณสมบัติพฤติกรรมที่มีอยู่ตามค่า หรือสร้างใหม่ที่กำหนดค่าเองด้วยค่าที่ระบุ |

### getValue() {#getValue--}
```
public final String getValue()
```

ค่าของคุณสมบัติ

**คืนค่า:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

แสดงว่าคุณสมบัตินี้ไม่ได้อยู่ในรายการคุณสมบัติมาตรฐานตามสเปค: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**คืนค่า:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

แสดงถึงคุณสมบัติ 'ppt\_x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

แสดงถึงคุณสมบัติ 'ppt\_y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

แสดงถึงคุณสมบัติ 'ppt\_w'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

แสดงถึงคุณสมบัติ 'ppt\_h'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

แสดงถึงคุณสมบัติ 'ppt\_c'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

แสดงถึงคุณสมบัติ 'ppt\_r'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

แสดงถึงคุณสมบัติ 'xshear'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

แสดงถึงคุณสมบัติ 'yshear'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

แสดงถึงคุณสมบัติ 'image'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

แสดงถึงคุณสมบัติ 'ScaleX'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

แสดงถึงคุณสมบัติ 'ScaleY'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

แสดงถึงคุณสมบัติ 'r'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

แสดงถึงคุณสมบัติ 'fillcolor'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

แสดงถึงคุณสมบัติ 'style.opacity'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

แสดงถึงคุณสมบัติ 'style.rotation'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

แสดงถึงคุณสมบัติ 'style.visibility'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

แสดงถึงคุณสมบัติ 'style.color'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

แสดงถึงคุณสมบัติ 'style.fontSize'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

แสดงถึงคุณสมบัติ 'style.fontWeight'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

แสดงถึงคุณสมบัติ 'style.fontStyle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

แสดงถึงคุณสมบัติ 'style.fontFamily'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

แสดงถึงคุณสมบัติ 'style.textEffectEmboss'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

แสดงถึงคุณสมบัติ 'style.textShadow'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

แสดงถึงคุณสมบัติ 'style.textTransform'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

แสดงถึงคุณสมบัติ 'style.textDecorationUnderline'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

แสดงถึงคุณสมบัติ 'style.textEffectOutline'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

แสดงถึงคุณสมบัติ 'style.textDecorationLineThrough'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

แสดงถึงคุณสมบัติ 'style.sRotation'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

แสดงถึงคุณสมบัติ 'imageData.cropTop'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

แสดงถึงคุณสมบัติ 'imageData.cropBottom'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

แสดงถึงคุณสมบัติ 'imageData.cropLeft'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

แสดงถึงคุณสมบัติ 'imageData.cropRight'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

แสดงถึงคุณสมบัติ 'imageData.gain'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

แสดงถึงคุณสมบัติ 'imageData.blacklevel'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

แสดงถึงคุณสมบัติ 'imageData.gamma'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

แสดงถึงคุณสมบัติ 'imageData.grayscale'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public  static BehaviorProperty getImageDataChromakey()
```

แสดงถึงคุณสมบัติ 'imageData.chromakey'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

แสดงถึงคุณสมบัติ 'fill.on'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

แสดงถึงคุณสมบัติ 'fill.type'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

แสดงถึงคุณสมบัติ 'fill.color'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

แสดงถึงคุณสมบัติ 'fill.opacity'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

แสดงถึงคุณสมบัติ 'fill.color2'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

แสดงถึงคุณสมบัติ 'fill.method'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

แสดงถึงคุณสมบัติ 'fill.opacity2'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

แสดงถึงคุณสมบัติ 'fill.angle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

แสดงถึงคุณสมบัติ 'fill.focus'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

แสดงถึงคุณสมบัติ 'fill.focusposition.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

แสดงถึงคุณสมบัติ 'fill.focusposition.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

แสดงถึงคุณสมบัติ 'fill.focussize.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

แสดงถึงคุณสมบัติ 'fill.focussize.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

แสดงถึงคุณสมบัติ 'stroke.on'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

แสดงถึงคุณสมบัติ 'stroke.color'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

แสดงถึงคุณสมบัติ 'stroke.weight'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

แสดงถึงคุณสมบัติ 'stroke.opacity'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

แสดงถึงคุณสมบัติ 'stroke.linestyle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

แสดงถึงคุณสมบัติ 'stroke.dashstyle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

แสดงถึงคุณสมบัติ 'stroke.filltype'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

แสดงถึงคุณสมบัติ 'stroke.src'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

แสดงถึงคุณสมบัติ 'stroke.color2'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

แสดงถึงคุณสมบัติ 'stroke.imagesize.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

แสดงถึงคุณสมบัติ 'stroke.imagesize.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

แสดงถึงคุณสมบัติ 'stroke.startArrow'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

แสดงถึงคุณสมบัติ 'stroke.endArrow'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

แสดงถึงคุณสมบัติ 'stroke.startArrowWidth'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

แสดงถึงคุณสมบัติ 'stroke.startArrowLength'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

แสดงถึงคุณสมบัติ 'stroke.endArrowWidth'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

แสดงถึงคุณสมบัติ 'stroke.endArrowLength'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

แสดงถึงคุณสมบัติ 'shadow.on'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

แสดงถึงคุณสมบัติ 'shadow.type'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

แสดงถึงคุณสมบัติ 'shadow.color'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

แสดงถึงคุณสมบัติ 'shadow.color2'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

แสดงถึงคุณสมบัติ 'shadow.opacity'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

แสดงถึงคุณสมบัติ 'shadow.offset.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

แสดงถึงคุณสมบัติ 'shadow.offset.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

แสดงถึงคุณสมบัติ 'shadow.offset2.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

แสดงถึงคุณสมบัติ 'shadow.offset2.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

แสดงถึงคุณสมบัติ 'shadow.origin.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

แสดงถึงคุณสมบัติ 'shadow.origin.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.xtox'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.xtoy'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.ytox'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.ytoy'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.perspectiveX'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

แสดงถึงคุณสมบัติ 'shadow.matrix.perspectiveY'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

แสดงถึงคุณสมบัติ 'skew.on'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

แสดงถึงคุณสมบัติ 'skew.offset.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

แสดงถึงคุณสมบัติ 'skew.offset.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

แสดงถึงคุณสมบัติ 'skew.origin.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

แสดงถึงคุณสมบัติ 'skew.origin.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

แสดงถึงคุณสมบัติ 'skew.matrix.xtox'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

แสดงถึงคุณสมบัติ 'skew.matrix.xtoy'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

แสดงถึงคุณสมบัติ 'skew.matrix.ytox'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

แสดงถึงคุณสมบัติ 'skew.matrix.ytoy'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

แสดงถึงคุณสมบัติ 'skew.matrix.perspectiveX'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

แสดงถึงคุณสมบัติ 'skew.matrix.perspectiveY'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

แสดงถึงคุณสมบัติ 'extrusion.on'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

แสดงถึงคุณสมบัติ 'extrusion.type'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

แสดงถึงคุณสมบัติ 'extrusion.render'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

แสดงถึงคุณสมบัติ 'extrusion.viewpointorigin.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

แสดงถึงคุณสมบัติ 'extrusion.viewpointorigin.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

แสดงถึงคุณสมบัติ 'extrusion.viewpoint.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

แสดงถึงคุณสมบัติ 'extrusion.viewpoint.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

แสดงถึงคุณสมบัติ 'extrusion.viewpoint.z'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

แสดงถึงคุณสมบัติ 'extrusion.plane'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

แสดงถึงคุณสมบัติ 'extrusion.skewangle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

แสดงถึงคุณสมบัติ 'extrusion.skewamt'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

แสดงถึงคุณสมบัติ 'extrusion.backdepth'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

แสดงถึงคุณสมบัติ 'extrusion.foredepth'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

แสดงถึงคุณสมบัติ 'extrusion.orientation.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

แสดงถึงคุณสมบัติ 'extrusion.orientation.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

แสดงถึงคุณสมบัติ 'extrusion.orientation.z'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

แสดงถึงคุณสมบัติ 'extrusion.orientationangle'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

แสดงถึงคุณสมบัติ 'extrusion.color'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

แสดงถึงคุณสมบัติ 'extrusion.rotationangle.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

แสดงถึงคุณสมบัติ 'extrusion.rotationangle.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

แสดงถึงคุณสมบัติ 'extrusion.lockrotationcenter'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

แสดงถึงคุณสมบัติ 'extrusion.autorotationcenter'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.x'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.y'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

แสดงถึงคุณสมบัติ 'extrusion.rotationcenter.z'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

แสดงถึงคุณสมบัติ 'extrusion.colormode'

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่าอ็อบเจกต์นี้เท่ากับอ็อบเจกต์อื่นหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจกต์ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - True หากอ็อบเจกต์เท่ากัน

### hashCode() {#hashCode--}
```
public int hashCode()
```

คำนวณและคืนค่า hash code ตามคุณสมบัติ (\#getValue.getValue)

**คืนค่า:**
int - คืนค่า hash code สำหรับอ็อบเจกต์นี้

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

ค้นหาคุณสมบัติพฤติกรรมที่มีอยู่ตามค่า หรือสร้างใหม่ที่กำหนดค่าเองด้วยค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| propertyValue | java.lang.String | ค่าของคุณสมบัติ |

**คืนค่า:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - อินสแตนซ์ของ BehaviorProperty