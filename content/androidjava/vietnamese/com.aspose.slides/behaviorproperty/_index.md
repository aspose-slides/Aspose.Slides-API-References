---
title: BehaviorProperty
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các kiểu thuộc tính cho hành vi hoạt hình.
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

Biểu thị các kiểu thuộc tính cho hành vi hoạt ảnh. Tuân theo danh sách các thuộc tính từ https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx và https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getValue()](#getValue--) | Giá trị của thuộc tính |
| [isCustom()](#isCustom--) | Hiển thị nếu thuộc tính này không thuộc danh sách các thuộc tính đã định nghĩa trước trong đặc tả: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | Biểu thị thuộc tính 'ppt\_x' |
| [getPptY()](#getPptY--) | Biểu thị thuộc tính 'ppt\_y' |
| [getPptW()](#getPptW--) | Biểu thị thuộc tính 'ppt\_w' |
| [getPptH()](#getPptH--) | Biểu thị thuộc tính 'ppt\_h' |
| [getPptC()](#getPptC--) | Biểu thị thuộc tính 'ppt\_c' |
| [getPptR()](#getPptR--) | Biểu thị thuộc tính 'ppt\_r' |
| [getXShear()](#getXShear--) | Biểu thị thuộc tính 'xshear' |
| [getYShear()](#getYShear--) | Biểu thị thuộc tính 'yshear' |
| [getImage()](#getImage--) | Biểu thị thuộc tính 'image' |
| [getScaleX()](#getScaleX--) | Biểu thị thuộc tính 'ScaleX' |
| [getScaleY()](#getScaleY--) | Biểu thị thuộc tính 'ScaleY' |
| [getR()](#getR--) | Biểu thị thuộc tính 'r' |
| [getFillColor()](#getFillColor--) | Biểu thị thuộc tính 'fillcolor' |
| [getStyleOpacity()](#getStyleOpacity--) | Biểu thị thuộc tính 'style.opacity' |
| [getStyleRotation()](#getStyleRotation--) | Biểu thị thuộc tính 'style.rotation' |
| [getStyleVisibility()](#getStyleVisibility--) | Biểu thị thuộc tính 'style.visibility' |
| [getStyleColor()](#getStyleColor--) | Biểu thị thuộc tính 'style.color' |
| [getStyleFontSize()](#getStyleFontSize--) | Biểu thị thuộc tính 'style.fontSize' |
| [getStyleFontWeight()](#getStyleFontWeight--) | Biểu thị thuộc tính 'style.fontWeight' |
| [getStyleFontStyle()](#getStyleFontStyle--) | Biểu thị thuộc tính 'style.fontStyle' |
| [getStyleFontFamily()](#getStyleFontFamily--) | Biểu thị thuộc tính 'style.fontFamily' |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | Biểu thị thuộc tính 'style.textEffectEmboss' |
| [getStyleTextShadow()](#getStyleTextShadow--) | Biểu thị thuộc tính 'style.textShadow' |
| [getStyleTextTransform()](#getStyleTextTransform--) | Biểu thị thuộc tính 'style.textTransform' |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | Biểu thị thuộc tính 'style.textDecorationUnderline' |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | Biểu thị thuộc tính 'style.textEffectOutline' |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | Biểu thị thuộc tính 'style.textDecorationLineThrough' |
| [getStyleSRotation()](#getStyleSRotation--) | Biểu thị thuộc tính 'style.sRotation' |
| [getImageDataCropTop()](#getImageDataCropTop--) | Biểu thị thuộc tính 'imageData.cropTop' |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | Biểu thị thuộc tính 'imageData.cropBottom' |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | Biểu thị thuộc tính 'imageData.cropLeft' |
| [getImageDataCropRight()](#getImageDataCropRight--) | Biểu thị thuộc tính 'imageData.cropRight' |
| [getImageDataGain()](#getImageDataGain--) | Biểu thị thuộc tính 'imageData.gain' |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | Biểu thị thuộc tính 'imageData.blacklevel' |
| [getImageDataGamma()](#getImageDataGamma--) | Biểu thị thuộc tính 'imageData.gamma' |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | Biểu thị thuộc tính 'imageData.grayscale' |
| [getImageDataChromakey()](#getImageDataChromakey--) | Biểu thị thuộc tính 'imageData.chromakey' |
| [getFillOn()](#getFillOn--) | Biểu thị thuộc tính 'fill.on' |
| [getFillType()](#getFillType--) | Biểu thị thuộc tính 'fill.type' |
| [getFill_Color()](#getFill-Color--) | Biểu thị thuộc tính 'fill.color' |
| [getFillOpacity()](#getFillOpacity--) | Biểu thị thuộc tính 'fill.opacity' |
| [getFillColor2()](#getFillColor2--) | Biểu thị thuộc tính 'fill.color2' |
| [getFillMethod()](#getFillMethod--) | Biểu thị thuộc tính 'fill.method' |
| [getFillOpacity2()](#getFillOpacity2--) | Biểu thị thuộc tính 'fill.opacity2' |
| [getFillAngle()](#getFillAngle--) | Biểu thị thuộc tính 'fill.angle' |
| [getFillFocus()](#getFillFocus--) | Biểu thị thuộc tính 'fill.focus' |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | Biểu thị thuộc tính 'fill.focusposition.x' |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | Biểu thị thuộc tính 'fill.focusposition.y' |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | Biểu thị thuộc tính 'fill.focussize.x' |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | Biểu thị thuộc tính 'fill.focussize.y' |
| [getStrokeOn()](#getStrokeOn--) | Biểu thị thuộc tính 'stroke.on' |
| [getStrokeColor()](#getStrokeColor--) | Biểu thị thuộc tính 'stroke.color' |
| [getStrokeWeight()](#getStrokeWeight--) | Biểu thị thuộc tính 'stroke.weight' |
| [getStrokeOpacity()](#getStrokeOpacity--) | Biểu thị thuộc tính 'stroke.opacity' |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | Biểu thị thuộc tính 'stroke.linestyle' |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | Biểu thị thuộc tính 'stroke.dashstyle' |
| [getStrokeFillType()](#getStrokeFillType--) | Biểu thị thuộc tính 'stroke.filltype' |
| [getStrokeSrc()](#getStrokeSrc--) | Biểu thị thuộc tính 'stroke.src' |
| [getStrokeColor2()](#getStrokeColor2--) | Biểu thị thuộc tính 'stroke.color2' |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | Biểu thị thuộc tính 'stroke.imagesize.x' |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | Biểu thị thuộc tính 'stroke.imagesize.y' |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | Biểu thị thuộc tính 'stroke.startArrow' |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | Biểu thị thuộc tính 'stroke.endArrow' |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | Biểu thị thuộc tính 'stroke.startArrowWidth' |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | Biểu thị thuộc tính 'stroke.startArrowLength' |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | Biểu thị thuộc tính 'stroke.endArrowWidth' |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | Biểu thị thuộc tính 'stroke.endArrowLength' |
| [getShadowOn()](#getShadowOn--) | Biểu thị thuộc tính 'shadow.on' |
| [getShadowType()](#getShadowType--) | Biểu thị thuộc tính 'shadow.type' |
| [getShadowColor()](#getShadowColor--) | Biểu thị thuộc tính 'shadow.color' |
| [getShadowColor2()](#getShadowColor2--) | Biểu thị thuộc tính 'shadow.color2' |
| [getShadowOpacity()](#getShadowOpacity--) | Biểu thị thuộc tính 'shadow.opacity' |
| [getShadowOffsetX()](#getShadowOffsetX--) | Biểu thị thuộc tính 'shadow.offset.x' |
| [getShadowOffsetY()](#getShadowOffsetY--) | Biểu thị thuộc tính 'shadow.offset.y' |
| [getShadowOffset2X()](#getShadowOffset2X--) | Biểu thị thuộc tính 'shadow.offset2.x' |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | Biểu thị thuộc tính 'shadow.offset2.y' |
| [getShadowOriginX()](#getShadowOriginX--) | Biểu thị thuộc tính 'shadow.origin.x' |
| [getShadowOriginY()](#getShadowOriginY--) | Biểu thị thuộc tính 'shadow.origin.y' |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | Biểu thị thuộc tính 'shadow.matrix.xtox' |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | Biểu thị thuộc tính 'shadow.matrix.xtoy' |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | Biểu thị thuộc tính 'shadow.matrix.ytox' |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | Biểu thị thuộc tính 'shadow.matrix.ytoy' |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | Biểu thị thuộc tính 'shadow.matrix.perspectiveX' |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | Biểu thị thuộc tính 'shadow.matrix.perspectiveY' |
| [getSkewOn()](#getSkewOn--) | Biểu thị thuộc tính 'skew.on' |
| [getSkewOffsetX()](#getSkewOffsetX--) | Biểu thị thuộc tính 'skew.offset.x' |
| [getSkewOffsetY()](#getSkewOffsetY--) | Biểu thị thuộc tính 'skew.offset.y' |
| [getSkewOriginX()](#getSkewOriginX--) | Biểu thị thuộc tính 'skew.origin.x' |
| [getSkewOriginY()](#getSkewOriginY--) | Biểu thị thuộc tính 'skew.origin.y' |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | Biểu thị thuộc tính 'skew.matrix.xtox' |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | Biểu thị thuộc tính 'skew.matrix.xtoy' |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | Biểu thị thuộc tính 'skew.matrix.ytox' |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | Biểu thị thuộc tính 'skew.matrix.ytoy' |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | Biểu thị thuộc tính 'skew.matrix.perspectiveX' |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | Biểu thị thuộc tính 'skew.matrix.perspectiveY' |
| [getExtrusionOn()](#getExtrusionOn--) | Biểu thị thuộc tính 'extrusion.on' |
| [getExtrusionType()](#getExtrusionType--) | Biểu thị thuộc tính 'extrusion.type' |
| [getExtrusionRender()](#getExtrusionRender--) | Biểu thị thuộc tính 'extrusion.render' |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | Biểu thị thuộc tính 'extrusion.viewpointorigin.x' |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | Biểu thị thuộc tính 'extrusion.viewpointorigin.y' |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | Biểu thị thuộc tính 'extrusion.viewpoint.x' |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | Biểu thị thuộc tính 'extrusion.viewpoint.y' |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | Biểu thị thuộc tính 'extrusion.viewpoint.z' |
| [getExtrusionPlane()](#getExtrusionPlane--) | Biểu thị thuộc tính 'extrusion.plane' |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | Biểu thị thuộc tính 'extrusion.skewangle' |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | Biểu thị thuộc tính 'extrusion.skewamt' |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | Biểu thị thuộc tính 'extrusion.backdepth' |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | Biểu thị thuộc tính 'extrusion.foredepth' |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | Biểu thị thuộc tính 'extrusion.orientation.x' |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | Biểu thị thuộc tính 'extrusion.orientation.y' |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | Biểu thị thuộc tính 'extrusion.orientation.z' |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | Biểu thị thuộc tính 'extrusion.orientationangle' |
| [getExtrusionColor()](#getExtrusionColor--) | Biểu thị thuộc tính 'extrusion.color' |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | Biểu thị thuộc tính 'extrusion.rotationangle.x' |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | Biểu thị thuộc tính 'extrusion.rotationangle.y' |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | Biểu thị thuộc tính 'extrusion.lockrotationcenter' |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | Biểu thị thuộc tính 'extrusion.autorotationcenter' |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | Biểu thị thuộc tính 'extrusion.rotationcenter.x' |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | Biểu thị thuộc tính 'extrusion.rotationcenter.y' |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | Biểu thị thuộc tính 'extrusion.rotationcenter.z' |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | Biểu thị thuộc tính 'extrusion.colormode' |
| [equals(Object obj)](#equals-java.lang.Object-) | Kiểm tra nếu đối tượng này bằng với đối tượng khác. |
| [hashCode()](#hashCode--) | Tính toán và trả về mã hash dựa trên thuộc tính (#getValue.getValue) |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | Tìm kiếm thuộc tính hành vi đã tồn tại theo giá trị hoặc tạo mới một thuộc tính tùy chỉnh với giá trị được chỉ định |
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

Hiển thị nếu thuộc tính này không thuộc danh sách các thuộc tính đã định nghĩa trước trong đặc tả: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**Trả về:**
boolean
### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

Biểu thị thuộc tính 'ppt\_x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

Biểu thị thuộc tính 'ppt\_y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

Biểu thị thuộc tính 'ppt\_w'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

Biểu thị thuộc tính 'ppt\_h'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

Biểu thị thuộc tính 'ppt\_c'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

Biểu thị thuộc tính 'ppt\_r'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

Biểu thị thuộc tính 'xshear'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

Biểu thị thuộc tính 'yshear'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

Biểu thị thuộc tính 'image'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

Biểu thị thuộc tính 'ScaleX'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

Biểu thị thuộc tính 'ScaleY'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getR() {#getR--}
```
public static BehaviorProperty getR()
```

Biểu thị thuộc tính 'r'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

Biểu thị thuộc tính 'fillcolor'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

Biểu thị thuộc tính 'style.opacity'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

Biểu thị thuộc tính 'style.rotation'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

Biểu thị thuộc tính 'style.visibility'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

Biểu thị thuộc tính 'style.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

Biểu thị thuộc tính 'style.fontSize'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

Biểu thị thuộc tính 'style.fontWeight'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

Biểu thị thuộc tính 'style.fontStyle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

Biểu thị thuộc tính 'style.fontFamily'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

Biểu thị thuộc tính 'style.textEffectEmboss'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

Biểu thị thuộc tính 'style.textShadow'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

Biểu thị thuộc tính 'style.textTransform'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

Biểu thị thuộc tính 'style.textDecorationUnderline'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

Biểu thị thuộc tính 'style.textEffectOutline'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

Biểu thị thuộc tính 'style.textDecorationLineThrough'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

Biểu thị thuộc tính 'style.sRotation'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

Biểu thị thuộc tính 'imageData.cropTop'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

Biểu thị thuộc tính 'imageData.cropBottom'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

Biểu thị thuộc tính 'imageData.cropLeft'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

Biểu thị thuộc tính 'imageData.cropRight'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

Biểu thị thuộc tính 'imageData.gain'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

Biểu thị thuộc tính 'imageData.blacklevel'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

Biểu thị thuộc tính 'imageData.gamma'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

Biểu thị thuộc tính 'imageData.grayscale'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

Biểu thị thuộc tính 'imageData.chromakey'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

Biểu thị thuộc tính 'fill.on'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

Biểu thị thuộc tính 'fill.type'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

Biểu thị thuộc tính 'fill.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

Biểu thị thuộc tính 'fill.opacity'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

Biểu thị thuộc tính 'fill.color2'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

Biểu thị thuộc tính 'fill.method'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

Biểu thị thuộc tính 'fill.opacity2'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

Biểu thị thuộc tính 'fill.angle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

Biểu thị thuộc tính 'fill.focus'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

Biểu thị thuộc tính 'fill.focusposition.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

Biểu thị thuộc tính 'fill.focusposition.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

Biểu thị thuộc tính 'fill.focussize.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

Biểu thị thuộc tính 'fill.focussize.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

Biểu thị thuộc tính 'stroke.on'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

Biểu thị thuộc tính 'stroke.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

Biểu thị thuộc tính 'stroke.weight'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

Biểu thị thuộc tính 'stroke.opacity'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

Biểu thị thuộc tính 'stroke.linestyle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

Biểu thị thuộc tính 'stroke.dashstyle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

Biểu thị thuộc tính 'stroke.filltype'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

Biểu thị thuộc tính 'stroke.src'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

Biểu thị thuộc tính 'stroke.color2'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

Biểu thị thuộc tính 'stroke.imagesize.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

Biểu thị thuộc tính 'stroke.imagesize.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

Biểu thị thuộc tính 'stroke.startArrow'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

Biểu thị thuộc tính 'stroke.endArrow'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

Biểu thị thuộc tính 'stroke.startArrowWidth'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

Biểu thị thuộc tính 'stroke.startArrowLength'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

Biểu thị thuộc tính 'stroke.endArrowWidth'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

Biểu thị thuộc tính 'stroke.endArrowLength'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

Biểu thị thuộc tính 'shadow.on'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

Biểu thị thuộc tính 'shadow.type'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

Biểu thị thuộc tính 'shadow.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

Biểu thị thuộc tính 'shadow.color2'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

Biểu thị thuộc tính 'shadow.opacity'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

Biểu thị thuộc tính 'shadow.offset.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

Biểu thị thuộc tính 'shadow.offset.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

Biểu thị thuộc tính 'shadow.offset2.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

Biểu thị thuộc tính 'shadow.offset2.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

Biểu thị thuộc tính 'shadow.origin.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

Biểu thị thuộc tính 'shadow.origin.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

Biểu thị thuộc tính 'shadow.matrix.xtox'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

Biểu thị thuộc tính 'shadow.matrix.xtoy'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

Biểu thị thuộc tính 'shadow.matrix.ytox'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

Biểu thị thuộc tính 'shadow.matrix.ytoy'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

Biểu thị thuộc tính 'shadow.matrix.perspectiveX'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

Biểu thị thuộc tính 'shadow.matrix.perspectiveY'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

Biểu thị thuộc tính 'skew.on'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

Biểu thị thuộc tính 'skew.offset.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

Biểu thị thuộc tính 'skew.offset.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

Biểu thị thuộc tính 'skew.origin.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

Biểu thị thuộc tính 'skew.origin.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

Biểu thị thuộc tính 'skew.matrix.xtox'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

Biểu thị thuộc tính 'skew.matrix.xtoy'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

Biểu thị thuộc tính 'skew.matrix.ytox'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

Biểu thị thuộc tính 'skew.matrix.ytoy'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

Biểu thị thuộc tính 'skew.matrix.perspectiveX'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

Biểu thị thuộc tính 'skew.matrix.perspectiveY'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

Biểu thị thuộc tính 'extrusion.on'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

Biểu thị thuộc tính 'extrusion.type'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

Biểu thị thuộc tính 'extrusion.render'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

Biểu thị thuộc tính 'extrusion.viewpointorigin.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

Biểu thị thuộc tính 'extrusion.viewpointorigin.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

Biểu thị thuộc tính 'extrusion.viewpoint.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

Biểu thị thuộc tính 'extrusion.viewpoint.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

Biểu thị thuộc tính 'extrusion.viewpoint.z'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

Biểu thị thuộc tính 'extrusion.plane'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

Biểu thị thuộc tính 'extrusion.skewangle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

Biểu thị thuộc tính 'extrusion.skewamt'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

Biểu thị thuộc tính 'extrusion.backdepth'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

Biểu thị thuộc tính 'extrusion.foredepth'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

Biểu thị thuộc tính 'extrusion.orientation.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

Biểu thị thuộc tính 'extrusion.orientation.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

Biểu thị thuộc tính 'extrusion.orientation.z'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

Biểu thị thuộc tính 'extrusion.orientationangle'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

Biểu thị thuộc tính 'extrusion.color'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

Biểu thị thuộc tính 'extrusion.rotationangle.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

Biểu thị thuộc tính 'extrusion.rotationangle.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

Biểu thị thuộc tính 'extrusion.lockrotationcenter'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

Biểu thị thuộc tính 'extrusion.autorotationcenter'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

Biểu thị thuộc tính 'extrusion.rotationcenter.x'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

Biểu thị thuộc tính 'extrusion.rotationcenter.y'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

Biểu thị thuộc tính 'extrusion.rotationcenter.z'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

Biểu thị thuộc tính 'extrusion.colormode'

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kiểm tra nếu đối tượng này bằng với đối tượng khác.

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

Tính toán và trả về mã hash dựa trên thuộc tính (#getValue.getValue)

**Trả về:**
int - Trả về mã băm cho đối tượng này
### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

Tìm kiếm thuộc tính hành vi đã tồn tại theo giá trị hoặc tạo mới một thuộc tính tùy chỉnh với giá trị được chỉ định

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | giá trị của thuộc tính |

**Trả về:**
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - instance of BehaviorProperty