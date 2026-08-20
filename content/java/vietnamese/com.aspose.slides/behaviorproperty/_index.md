---
title: BehaviorProperty
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các loại thuộc tính cho hành vi hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/behaviorproperty/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)
```
public class BehaviorProperty implements IBehaviorProperty
```

Đại diện cho các kiểu thuộc tính của hành vi hoạt ảnh. Tuân theo danh sách các thuộc tính từ https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx và https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Phương thức

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Giá trị của thuộc tính |
| [isCustom()](#isCustom--) | Hiển thị nếu thuộc tính này không thuộc danh sách các thuộc tính được định nghĩa trước trong thông số kỹ thuật: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Biểu diễn thuộc tính 'ppt\_x' |
| [getPptY()](#getPptY--) | Biểu diễn thuộc tính 'ppt\_y' |
| [getPptW()](#getPptW--) | Biểu diễn thuộc tính 'ppt\_w' |
| [getPptH()](#getPptH--) | Biểu diễn thuộc tính 'ppt\_h' |
| [getPptC()](#getPptC--) | Biểu diễn thuộc tính 'ppt\_c' |
| [getPptR()](#getPptR--) | Biểu diễn thuộc tính 'ppt\_r' |
| [getXShear()](#getXShear--) | Biểu diễn thuộc tính 'xshear' |
| [getYShear()](#getYShear--) | Biểu diễn thuộc tính 'yshear' |
| [getImage()](#getImage--) | Biểu diễn thuộc tính 'image' |
| [getScaleX()](#getScaleX--) | Biểu diễn thuộc tính 'ScaleX' |
| [getScaleY()](#getScaleY--) | Biểu diễn thuộc tính 'ScaleY' |
| [getR()](#getR--) | Biểu diễn thuộc tính 'r' |
| [getFillColor()](#getFillColor--) | Biểu diễn thuộc tính 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Biểu diễn thuộc tính 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Biểu diễn thuộc tính 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Biểu diễn thuộc tính 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Biểu diễn thuộc tính 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Biểu diễn thuộc tính 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Biểu diễn thuộc tính 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Biểu diễn thuộc tính 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Biểu diễn thuộc tính 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Biểu diễn thuộc tính 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Biểu diễn thuộc tính 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Biểu diễn thuộc tính 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Biểu diễn thuộc tính 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Biểu diễn thuộc tính 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Biểu diễn thuộc tính 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Biểu diễn thuộc tính 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Biểu diễn thuộc tính 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Biểu diễn thuộc tính 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Biểu diễn thuộc tính 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Biểu diễn thuộc tính 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Biểu diễn thuộc tính 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Biểu diễn thuộc tính 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Biểu diễn thuộc tính 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Biểu diễn thuộc tính 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Biểu diễn thuộc tính 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Biểu diễn thuộc tính 'fill.on' |
| [getFillType()](#getFillType--) | Biểu diễn thuộc tính 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Biểu diễn thuộc tính 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Biểu diễn thuộc tính 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Biểu diễn thuộc tính 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Biểu diễn thuộc tính 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Biểu diễn thuộc tính 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Biểu diễn thuộc tính 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Biểu diễn thuộc tính 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Biểu diễn thuộc tính 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Biểu diễn thuộc tính 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Biểu diễn thuộc tính 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Biểu diễn thuộc tính 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Biểu diễn thuộc tính 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Biểu diễn thuộc tính 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Biểu diễn thuộc tính 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Biểu diễn thuộc tính 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Biểu diễn thuộc tính 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Biểu diễn thuộc tính 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Biểu diễn thuộc tính 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Biểu diễn thuộc tính 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Biểu diễn thuộc tính 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Biểu diễn thuộc tính 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Biểu diễn thuộc tính 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Biểu diễn thuộc tính 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Biểu diễn thuộc tính 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Biểu diễn thuộc tính 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Biểu diễn thuộc tính 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Biểu diễn thuộc tính 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Biểu diễn thuộc tính 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Biểu diễn thuộc tính 'shadow.on' |
| [getShadowType()](#getShadowType--) | Biểu diễn thuộc tính 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Biểu diễn thuộc tính 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Biểu diễn thuộc tính 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Biểu diễn thuộc tính 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Biểu diễn thuộc tính 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Biểu diễn thuộc tính 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Biểu diễn thuộc tính 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Biểu diễn thuộc tính 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Biểu diễn thuộc tính 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Biểu diễn thuộc tính 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Biểu diễn thuộc tính 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Biểu diễn thuộc tính 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Biểu diễn thuộc tính 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Biểu diễn thuộc tính 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Biểu diễn thuộc tính 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Biểu diễn thuộc tính 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Biểu diễn thuộc tính 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Biểu diễn thuộc tính 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Biểu diễn thuộc tính 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Biểu diễn thuộc tính 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Biểu diễn thuộc tính 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Biểu diễn thuộc tính 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Biểu diễn thuộc tính 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Biểu diễn thuộc tính 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Biểu diễn thuộc tính 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Biểu diễn thuộc tính 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Biểu diễn thuộc tính 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Biểu diễn thuộc tính 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Biểu diễn thuộc tính 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Biểu diễn thuộc tính 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Biểu diễn thuộc tính 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Biểu diễn thuộc tính 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Biểu diễn thuộc tính 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Biểu diễn thuộc tính 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Biểu diễn thuộc tính 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Biểu diễn thuộc tính 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Biểu diễn thuộc tính 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Biểu diễn thuộc tính 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Biểu diễn thuộc tính 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Biểu diễn thuộc tính 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Biểu diễn thuộc tính 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Biểu diễn thuộc tính 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Biểu diễn thuộc tính 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Biểu diễn thuộc tính 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Biểu diễn thuộc tính 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Biểu diễn thuộc tính 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Biểu diễn thuộc tính 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Biểu diễn thuộc tính 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Biểu diễn thuộc tính 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Biểu diễn thuộc tính 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Biểu diễn thuộc tính 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Biểu diễn thuộc tính 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Biểu diễn thuộc tính 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Kiểm tra xem đối tượng này có bằng với đối tượng khác hay không. |
| [hashCode()](#hashCode--) | Tính toán và trả về mã hash dựa trên thuộc tính (\#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Tìm thuộc tính hành vi hiện có theo giá trị hoặc tạo mới tùy chỉnh với giá trị đã chỉ định |

### getValue() {#getValue--}
```
public final String getValue()
```

Giá trị của thuộc tính

**Trả về:**
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

Hiển thị nếu thuộc tính này không thuộc danh sách các thuộc tính được định nghĩa trước trong thông số kỹ thuật: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Trả về:**
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Biểu diễn thuộc tính 'ppt\_x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Biểu diễn thuộc tính 'ppt\_y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Biểu diễn thuộc tính 'ppt\_w'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Biểu diễn thuộc tính 'ppt\_h'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Biểu diễn thuộc tính 'ppt\_c'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Biểu diễn thuộc tính 'ppt\_r'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Biểu diễn thuộc tính 'xshear'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Biểu diễn thuộc tính 'yshear'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Biểu diễn thuộc tính 'image'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Biểu diễn thuộc tính 'ScaleX'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Biểu diễn thuộc tính 'ScaleY'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Biểu diễn thuộc tính 'r'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Biểu diễn thuộc tính 'fillcolor'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Biểu diễn thuộc tính 'style.opacity'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Biểu diễn thuộc tính 'style.rotation'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Biểu diễn thuộc tính 'style.visibility'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Biểu diễn thuộc tính 'style.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Biểu diễn thuộc tính 'style.fontSize'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Biểu diễn thuộc tính 'style.fontWeight'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Biểu diễn thuộc tính 'style.fontStyle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Biểu diễn thuộc tính 'style.fontFamily'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Biểu diễn thuộc tính 'style.textEffectEmboss'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Biểu diễn thuộc tính 'style.textShadow'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Biểu diễn thuộc tính 'style.textTransform'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Biểu diễn thuộc tính 'style.textDecorationUnderline'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Biểu diễn thuộc tính 'style.textEffectOutline'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Biểu diễn thuộc tính 'style.textDecorationLineThrough'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Biểu diễn thuộc tính 'style.sRotation'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Biểu diễn thuộc tính 'imageData.cropTop'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Biểu diễn thuộc tính 'imageData.cropBottom'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Biểu diễn thuộc tính 'imageData.cropLeft'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Biểu diễn thuộc tính 'imageData.cropRight'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Biểu diễn thuộc tính 'imageData.gain'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Biểu diễn thuộc tính 'imageData.blacklevel'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Biểu diễn thuộc tính 'imageData.gamma'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Biểu diễn thuộc tính 'imageData.grayscale' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Biểu diễn thuộc tính 'imageData.chromakey' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Biểu diễn thuộc tính 'fill.on' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Biểu diễn thuộc tính 'fill.type' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Biểu diễn thuộc tính 'fill.color' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Biểu diễn thuộc tính 'fill.opacity' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Biểu diễn thuộc tính 'fill.color2' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Biểu diễn thuộc tính 'fill.method' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Biểu diễn thuộc tính 'fill.opacity2' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Biểu diễn thuộc tính 'fill.angle' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Biểu diễn thuộc tính 'fill.focus' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Biểu diễn thuộc tính 'fill.focusposition.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Biểu diễn thuộc tính 'fill.focusposition.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Biểu diễn thuộc tính 'fill.focussize.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Biểu diễn thuộc tính 'fill.focussize.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Biểu diễn thuộc tính 'stroke.on' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Biểu diễn thuộc tính 'stroke.color' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Biểu diễn thuộc tính 'stroke.weight' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Biểu diễn thuộc tính 'stroke.opacity' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Biểu diễn thuộc tính 'stroke.linestyle' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Biểu diễn thuộc tính 'stroke.dashstyle' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Biểu diễn thuộc tính 'stroke.filltype' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Biểu diễn thuộc tính 'stroke.src' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Biểu diễn thuộc tính 'stroke.color2' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Biểu diễn thuộc tính 'stroke.imagesize.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Biểu diễn thuộc tính 'stroke.imagesize.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Biểu diễn thuộc tính 'stroke.startArrow' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Biểu diễn thuộc tính 'stroke.endArrow' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Biểu diễn thuộc tính 'stroke.startArrowWidth' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Biểu diễn thuộc tính 'stroke.startArrowLength' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Biểu diễn thuộc tính 'stroke.endArrowWidth' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Biểu diễn thuộc tính 'stroke.endArrowLength' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Biểu diễn thuộc tính 'shadow.on' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Biểu diễn thuộc tính 'shadow.type' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Biểu diễn thuộc tính 'shadow.color' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Biểu diễn thuộc tính 'shadow.color2' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Biểu diễn thuộc tính 'shadow.opacity' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Biểu diễn thuộc tính 'shadow.offset.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Biểu diễn thuộc tính 'shadow.offset.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Biểu diễn thuộc tính 'shadow.offset2.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Biểu diễn thuộc tính 'shadow.offset2.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Biểu diễn thuộc tính 'shadow.origin.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Biểu diễn thuộc tính 'shadow.origin.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Biểu diễn thuộc tính 'shadow.matrix.xtox' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Biểu diễn thuộc tính 'shadow.matrix.xtoy' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Biểu diễn thuộc tính 'shadow.matrix.ytox' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Biểu diễn thuộc tính 'shadow.matrix.ytoy' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Biểu diễn thuộc tính 'shadow.matrix.perspectiveX' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Biểu diễn thuộc tính 'shadow.matrix.perspectiveY' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Biểu diễn thuộc tính 'skew.on' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Biểu diễn thuộc tính 'skew.offset.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Biểu diễn thuộc tính 'skew.offset.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Biểu diễn thuộc tính 'skew.origin.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Biểu diễn thuộc tính 'skew.origin.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Biểu diễn thuộc tính 'skew.matrix.xtox' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Biểu diễn thuộc tính 'skew.matrix.xtoy' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Biểu diễn thuộc tính 'skew.matrix.ytox' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Biểu diễn thuộc tính 'skew.matrix.ytoy' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Biểu diễn thuộc tính 'skew.matrix.perspectiveX' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Biểu diễn thuộc tính 'skew.matrix.perspectiveY' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Biểu diễn thuộc tính 'extrusion.on' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Biểu diễn thuộc tính 'extrusion.type' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Biểu diễn thuộc tính 'extrusion.render' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Biểu diễn thuộc tính 'extrusion.viewpointorigin.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Biểu diễn thuộc tính 'extrusion.viewpointorigin.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Biểu diễn thuộc tính 'extrusion.viewpoint.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Biểu diễn thuộc tính 'extrusion.viewpoint.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Biểu diễn thuộc tính 'extrusion.viewpoint.z' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Biểu diễn thuộc tính 'extrusion.plane' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Biểu diễn thuộc tính 'extrusion.skewangle' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Biểu diễn thuộc tính 'extrusion.skewamt' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Biểu diễn thuộc tính 'extrusion.backdepth' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Biểu diễn thuộc tính 'extrusion.foredepth' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Biểu diễn thuộc tính 'extrusion.orientation.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Biểu diễn thuộc tính 'extrusion.orientation.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Biểu diễn thuộc tính 'extrusion.orientation.z' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Biểu diễn thuộc tính 'extrusion.orientationangle' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Biểu diễn thuộc tính 'extrusion.color' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Biểu diễn thuộc tính 'extrusion.rotationangle.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Biểu diễn thuộc tính 'extrusion.rotationangle.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Biểu diễn thuộc tính 'extrusion.lockrotationcenter' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Biểu diễn thuộc tính 'extrusion.autorotationcenter' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Biểu diễn thuộc tính 'extrusion.rotationcenter.x' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Biểu diễn thuộc tính 'extrusion.rotationcenter.y' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Biểu diễn thuộc tính 'extrusion.rotationcenter.z' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Biểu diễn thuộc tính 'extrusion.colormode' property

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kiểm tra xem đối tượng này có bằng với đối tượng khác hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh. |

**Trả về:**
boolean - Đúng nếu các đối tượng bằng nhau.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Tính toán và trả về mã băm dựa trên thuộc tính (\#getValue.getValue) property

**Trả về:**
int - Trả về mã băm cho đối tượng này
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Tìm thuộc tính hành vi hiện có theo giá trị hoặc tạo mới một thuộc tính tùy chỉnh với giá trị đã chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | giá trị của thuộc tính |

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - đối tượng của BehaviorProperty