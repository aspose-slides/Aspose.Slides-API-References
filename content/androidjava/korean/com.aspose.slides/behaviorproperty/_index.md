---
title: BehaviorProperty
second_title: Java API를 사용한 Android용 Aspose.Slides 레퍼런스
description: 애니메이션 동작에 대한 속성 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/behaviorproperty/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty)  
```
public class BehaviorProperty implements IBehaviorProperty
```

애니메이션 동작에 대한 속성 유형을 나타냅니다. 다음 속성 목록을 따릅니다: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx 및 https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx  

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getValue()](#getValue--) | 속성의 값 |
| [isCustom()](#isCustom--) | 이 속성이 사양에 정의된 사전 정의 속성 목록에 포함되지 않는지 표시합니다: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx |
| [getPptX()](#getPptX--) | 'ppt\_x' 속성을 나타냅니다 |
| [getPptY()](#getPptY--) | 'ppt\_y' 속성을 나타냅니다 |
| [getPptW()](#getPptW--) | 'ppt\_w' 속성을 나타냅니다 |
| [getPptH()](#getPptH--) | 'ppt\_h' 속성을 나타냅니다 |
| [getPptC()](#getPptC--) | 'ppt\_c' 속성을 나타냅니다 |
| [getPptR()](#getPptR--) | 'ppt\_r' 속성을 나타냅니다 |
| [getXShear()](#getXShear--) | 'xshear' 속성을 나타냅니다 |
| [getYShear()](#getYShear--) | 'yshear' 속성을 나타냅니다 |
| [getImage()](#getImage--) | 'image' 속성을 나타냅니다 |
| [getScaleX()](#getScaleX--) | 'ScaleX' 속성을 나타냅니다 |
| [getScaleY()](#getScaleY--) | 'ScaleY' 속성을 나타냅니다 |
| [getR()](#getR--) | 'r' 속성을 나타냅니다 |
| [getFillColor()](#getFillColor--) | 'fillcolor' 속성을 나타냅니다 |
| [getStyleOpacity()](#getStyleOpacity--) | 'style.opacity' 속성을 나타냅니다 |
| [getStyleRotation()](#getStyleRotation--) | 'style.rotation' 속성을 나타냅니다 |
| [getStyleVisibility()](#getStyleVisibility--) | 'style.visibility' 속성을 나타냅니다 |
| [getStyleColor()](#getStyleColor--) | 'style.color' 속성을 나타냅니다 |
| [getStyleFontSize()](#getStyleFontSize--) | 'style.fontSize' 속성을 나타냅니다 |
| [getStyleFontWeight()](#getStyleFontWeight--) | 'style.fontWeight' 속성을 나타냅니다 |
| [getStyleFontStyle()](#getStyleFontStyle--) | 'style.fontStyle' 속성을 나타냅니다 |
| [getStyleFontFamily()](#getStyleFontFamily--) | 'style.fontFamily' 속성을 나타냅니다 |
| [getStyleTextEffectEmboss()](#getStyleTextEffectEmboss--) | 'style.textEffectEmboss' 속성을 나타냅니다 |
| [getStyleTextShadow()](#getStyleTextShadow--) | 'style.textShadow' 속성을 나타냅니다 |
| [getStyleTextTransform()](#getStyleTextTransform--) | 'style.textTransform' 속성을 나타냅니다 |
| [getStyleTextDecorationUnderline()](#getStyleTextDecorationUnderline--) | 'style.textDecorationUnderline' 속성을 나타냅니다 |
| [getStyleTextEffectOutline()](#getStyleTextEffectOutline--) | 'style.textEffectOutline' 속성을 나타냅니다 |
| [getStyleTextDecorationLineThrough()](#getStyleTextDecorationLineThrough--) | 'style.textDecorationLineThrough' 속성을 나타냅니다 |
| [getStyleSRotation()](#getStyleSRotation--) | 'style.sRotation' 속성을 나타냅니다 |
| [getImageDataCropTop()](#getImageDataCropTop--) | 'imageData.cropTop' 속성을 나타냅니다 |
| [getImageDataCropBottom()](#getImageDataCropBottom--) | 'imageData.cropBottom' 속성을 나타냅니다 |
| [getImageDataCropLeft()](#getImageDataCropLeft--) | 'imageData.cropLeft' 속성을 나타냅니다 |
| [getImageDataCropRight()](#getImageDataCropRight--) | 'imageData.cropRight' 속성을 나타냅니다 |
| [getImageDataGain()](#getImageDataGain--) | 'imageData.gain' 속성을 나타냅니다 |
| [getImageDataBlacklevel()](#getImageDataBlacklevel--) | 'imageData.blacklevel' 속성을 나타냅니다 |
| [getImageDataGamma()](#getImageDataGamma--) | 'imageData.gamma' 속성을 나타냅니다 |
| [getImageDataGrayscale()](#getImageDataGrayscale--) | 'imageData.grayscale' 속성을 나타냅니다 |
| [getImageDataChromakey()](#getImageDataChromakey--) | 'imageData.chromakey' 속성을 나타냅니다 |
| [getFillOn()](#getFillOn--) | 'fill.on' 속성을 나타냅니다 |
| [getFillType()](#getFillType--) | 'fill.type' 속성을 나타냅니다 |
| [getFill_Color()](#getFill-Color--) | 'fill.color' 속성을 나타냅니다 |
| [getFillOpacity()](#getFillOpacity--) | 'fill.opacity' 속성을 나타냅니다 |
| [getFillColor2()](#getFillColor2--) | 'fill.color2' 속성을 나타냅니다 |
| [getFillMethod()](#getFillMethod--) | 'fill.method' 속성을 나타냅니다 |
| [getFillOpacity2()](#getFillOpacity2--) | 'fill.opacity2' 속성을 나타냅니다 |
| [getFillAngle()](#getFillAngle--) | 'fill.angle' 속성을 나타냅니다 |
| [getFillFocus()](#getFillFocus--) | 'fill.focus' 속성을 나타냅니다 |
| [getFillFocusPositionX()](#getFillFocusPositionX--) | 'fill.focusposition.x' 속성을 나타냅니다 |
| [getFillFocusPositionY()](#getFillFocusPositionY--) | 'fill.focusposition.y' 속성을 나타냅니다 |
| [getFillFocusSizeX()](#getFillFocusSizeX--) | 'fill.focussize.x' 속성을 나타냅니다 |
| [getFillFocusSizeY()](#getFillFocusSizeY--) | 'fill.focussize.y' 속성을 나타냅니다 |
| [getStrokeOn()](#getStrokeOn--) | 'stroke.on' 속성을 나타냅니다 |
| [getStrokeColor()](#getStrokeColor--) | 'stroke.color' 속성을 나타냅니다 |
| [getStrokeWeight()](#getStrokeWeight--) | 'stroke.weight' 속성을 나타냅니다 |
| [getStrokeOpacity()](#getStrokeOpacity--) | 'stroke.opacity' 속성을 나타냅니다 |
| [getStrokeLineStyle()](#getStrokeLineStyle--) | 'stroke.linestyle' 속성을 나타냅니다 |
| [getStrokeDashStyle()](#getStrokeDashStyle--) | 'stroke.dashstyle' 속성을 나타냅니다 |
| [getStrokeFillType()](#getStrokeFillType--) | 'stroke.filltype' 속성을 나타냅니다 |
| [getStrokeSrc()](#getStrokeSrc--) | 'stroke.src' 속성을 나타냅니다 |
| [getStrokeColor2()](#getStrokeColor2--) | 'stroke.color2' 속성을 나타냅니다 |
| [getStrokeImageSizeX()](#getStrokeImageSizeX--) | 'stroke.imagesize.x' 속성을 나타냅니다 |
| [getStrokeImageSizeY()](#getStrokeImageSizeY--) | 'stroke.imagesize.y' 속성을 나타냅니다 |
| [getStrokeStartArrow()](#getStrokeStartArrow--) | 'stroke.startArrow' 속성을 나타냅니다 |
| [getStrokeEndArrow()](#getStrokeEndArrow--) | 'stroke.endArrow' 속성을 나타냅니다 |
| [getStrokeStartArrowWidth()](#getStrokeStartArrowWidth--) | 'stroke.startArrowWidth' 속성을 나타냅니다 |
| [getStrokeStartArrowLength()](#getStrokeStartArrowLength--) | 'stroke.startArrowLength' 속성을 나타냅니다 |
| [getStrokeEndArrowWidth()](#getStrokeEndArrowWidth--) | 'stroke.endArrowWidth' 속성을 나타냅니다 |
| [getStrokeEndArrowLength()](#getStrokeEndArrowLength--) | 'stroke.endArrowLength' 속성을 나타냅니다 |
| [getShadowOn()](#getShadowOn--) | 'shadow.on' 속성을 나타냅니다 |
| [getShadowType()](#getShadowType--) | 'shadow.type' 속성을 나타냅니다 |
| [getShadowColor()](#getShadowColor--) | 'shadow.color' 속성을 나타냅니다 |
| [getShadowColor2()](#getShadowColor2--) | 'shadow.color2' 속성을 나타냅니다 |
| [getShadowOpacity()](#getShadowOpacity--) | 'shadow.opacity' 속성을 나타냅니다 |
| [getShadowOffsetX()](#getShadowOffsetX--) | 'shadow.offset.x' 속성을 나타냅니다 |
| [getShadowOffsetY()](#getShadowOffsetY--) | 'shadow.offset.y' 속성을 나타냅니다 |
| [getShadowOffset2X()](#getShadowOffset2X--) | 'shadow.offset2.x' 속성을 나타냅니다 |
| [getShadowOffset2Y()](#getShadowOffset2Y--) | 'shadow.offset2.y' 속성을 나타냅니다 |
| [getShadowOriginX()](#getShadowOriginX--) | 'shadow.origin.x' 속성을 나타냅니다 |
| [getShadowOriginY()](#getShadowOriginY--) | 'shadow.origin.y' 속성을 나타냅니다 |
| [getShadowMatrixXtoX()](#getShadowMatrixXtoX--) | 'shadow.matrix.xtox' 속성을 나타냅니다 |
| [getShadowMatrixXtoY()](#getShadowMatrixXtoY--) | 'shadow.matrix.xtoy' 속성을 나타냅니다 |
| [getShadowMatrixYtoX()](#getShadowMatrixYtoX--) | 'shadow.matrix.ytox' 속성을 나타냅니다 |
| [getShadowMatrixYtoY()](#getShadowMatrixYtoY--) | 'shadow.matrix.ytoy' 속성을 나타냅니다 |
| [getShadowMatrixPerspectiveX()](#getShadowMatrixPerspectiveX--) | 'shadow.matrix.perspectiveX' 속성을 나타냅니다 |
| [getShadowMatrixPerspectiveY()](#getShadowMatrixPerspectiveY--) | 'shadow.matrix.perspectiveY' 속성을 나타냅니다 |
| [getSkewOn()](#getSkewOn--) | 'skew.on' 속성을 나타냅니다 |
| [getSkewOffsetX()](#getSkewOffsetX--) | 'skew.offset.x' 속성을 나타냅니다 |
| [getSkewOffsetY()](#getSkewOffsetY--) | 'skew.offset.y' 속성을 나타냅니다 |
| [getSkewOriginX()](#getSkewOriginX--) | 'skew.origin.x' 속성을 나타냅니다 |
| [getSkewOriginY()](#getSkewOriginY--) | 'skew.origin.y' 속성을 나타냅니다 |
| [getSkewMatrixXtoX()](#getSkewMatrixXtoX--) | 'skew.matrix.xtox' 속성을 나타냅니다 |
| [getSkewMatrixXtoY()](#getSkewMatrixXtoY--) | 'skew.matrix.xtoy' 속성을 나타냅니다 |
| [getSkewMatrixYtoX()](#getSkewMatrixYtoX--) | 'skew.matrix.ytox' 속성을 나타냅니다 |
| [getSkewMatrixYtoY()](#getSkewMatrixYtoY--) | 'skew.matrix.ytoy' 속성을 나타냅니다 |
| [getSkewMatrixPerspectiveX()](#getSkewMatrixPerspectiveX--) | 'skew.matrix.perspectiveX' 속성을 나타냅니다 |
| [getSkewMatrixPerspectiveY()](#getSkewMatrixPerspectiveY--) | 'skew.matrix.perspectiveY' 속성을 나타냅니다 |
| [getExtrusionOn()](#getExtrusionOn--) | 'extrusion.on' 속성을 나타냅니다 |
| [getExtrusionType()](#getExtrusionType--) | 'extrusion.type' 속성을 나타냅니다 |
| [getExtrusionRender()](#getExtrusionRender--) | 'extrusion.render' 속성을 나타냅니다 |
| [getExtrusionViewPointOriginX()](#getExtrusionViewPointOriginX--) | 'extrusion.viewpointorigin.x' 속성을 나타냅니다 |
| [getExtrusionViewPointOriginY()](#getExtrusionViewPointOriginY--) | 'extrusion.viewpointorigin.y' 속성을 나타냅니다 |
| [getExtrusionViewPointX()](#getExtrusionViewPointX--) | 'extrusion.viewpoint.x' 속성을 나타냅니다 |
| [getExtrusionViewPointY()](#getExtrusionViewPointY--) | 'extrusion.viewpoint.y' 속성을 나타냅니다 |
| [getExtrusionViewPointZ()](#getExtrusionViewPointZ--) | 'extrusion.viewpoint.z' 속성을 나타냅니다 |
| [getExtrusionPlane()](#getExtrusionPlane--) | 'extrusion.plane' 속성을 나타냅니다 |
| [getExtrusionSkewAngle()](#getExtrusionSkewAngle--) | 'extrusion.skewangle' 속성을 나타냅니다 |
| [getExtrusionSkewAmt()](#getExtrusionSkewAmt--) | 'extrusion.skewamt' 속성을 나타냅니다 |
| [getExtrusionBackDepth()](#getExtrusionBackDepth--) | 'extrusion.backdepth' 속성을 나타냅니다 |
| [getExtrusionForeDepth()](#getExtrusionForeDepth--) | 'extrusion.foredepth' 속성을 나타냅니다 |
| [getExtrusionOrientationX()](#getExtrusionOrientationX--) | 'extrusion.orientation.x' 속성을 나타냅니다 |
| [getExtrusionOrientationY()](#getExtrusionOrientationY--) | 'extrusion.orientation.y' 속성을 나타냅니다 |
| [getExtrusionOrientationZ()](#getExtrusionOrientationZ--) | 'extrusion.orientation.z' 속성을 나타냅니다 |
| [getExtrusionOrientationAngle()](#getExtrusionOrientationAngle--) | 'extrusion.orientationangle' 속성을 나타냅니다 |
| [getExtrusionColor()](#getExtrusionColor--) | 'extrusion.color' 속성을 나타냅니다 |
| [getExtrusionRotationAngleX()](#getExtrusionRotationAngleX--) | 'extrusion.rotationangle.x' 속성을 나타냅니다 |
| [getExtrusionRotationAngleY()](#getExtrusionRotationAngleY--) | 'extrusion.rotationangle.y' 속성을 나타냅니다 |
| [getExtrusionLockRotationCenter()](#getExtrusionLockRotationCenter--) | 'extrusion.lockrotationcenter' 속성을 나타냅니다 |
| [getExtrusionAutoRotationCenter()](#getExtrusionAutoRotationCenter--) | 'extrusion.autorotationcenter' 속성을 나타냅니다 |
| [getExtrusionRotationCenterX()](#getExtrusionRotationCenterX--) | 'extrusion.rotationcenter.x' 속성을 나타냅니다 |
| [getExtrusionRotationCenterY()](#getExtrusionRotationCenterY--) | 'extrusion.rotationcenter.y' 속성을 나타냅니다 |
| [getExtrusionRotationCenterZ()](#getExtrusionRotationCenterZ--) | 'extrusion.rotationcenter.z' 속성을 나타냅니다 |
| [getExtrusionColorMode()](#getExtrusionColorMode--) | 'extrusion.colormode' 속성을 나타냅니다 |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 객체가 다른 객체와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | (\#getValue.getValue) 속성을 기반으로 해시 코드를 계산하고 반환합니다 |
| [getOrCreateByValue(String propertyValue)](#getOrCreateByValue-java.lang.String-) | 값으로 기존 동작 속성을 찾거나 지정된 값으로 새 사용자 정의 속성을 생성합니다 |

### getValue() {#getValue--}
```
public final String getValue()
```

속성의 값

**반환:**  
java.lang.String

### isCustom() {#isCustom--}
```
public final boolean isCustom()
```

이 속성이 사양에 정의된 사전 정의 속성 목록에 포함되지 않는지 표시합니다: https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx

**반환:**  
boolean

### getPptX() {#getPptX--}
```
public static BehaviorProperty getPptX()
```

'ppt\_x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptY() {#getPptY--}
```
public static BehaviorProperty getPptY()
```

'ppt\_y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptW() {#getPptW--}
```
public static BehaviorProperty getPptW()
```

'ppt\_w' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptH() {#getPptH--}
```
public static BehaviorProperty getPptH()
```

'ppt\_h' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptC() {#getPptC--}
```
public static BehaviorProperty getPptC()
```

'ppt\_c' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getPptR() {#getPptR--}
```
public static BehaviorProperty getPptR()
```

'ppt\_r' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getXShear() {#getXShear--}
```
public static BehaviorProperty getXShear()
```

'xshear' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getYShear() {#getYShear--}
```
public static BehaviorProperty getYShear()
```

'yshear' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImage() {#getImage--}
```
public static BehaviorProperty getImage()
```

'image' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleX() {#getScaleX--}
```
public static BehaviorProperty getScaleX()
```

'ScaleX' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getScaleY() {#getScaleY--}
```
public static BehaviorProperty getScaleY()
```

'ScaleY' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getR() {#getR--}
```
public static BehaviorProperty getR()
```

'r' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor() {#getFillColor--}
```
public static BehaviorProperty getFillColor()
```

'fillcolor' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleOpacity() {#getStyleOpacity--}
```
public static BehaviorProperty getStyleOpacity()
```

'style.opacity' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleRotation() {#getStyleRotation--}
```
public static BehaviorProperty getStyleRotation()
```

'style.rotation' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleVisibility() {#getStyleVisibility--}
```
public static BehaviorProperty getStyleVisibility()
```

'style.visibility' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleColor() {#getStyleColor--}
```
public static BehaviorProperty getStyleColor()
```

'style.color' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontSize() {#getStyleFontSize--}
```
public static BehaviorProperty getStyleFontSize()
```

'style.fontSize' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontWeight() {#getStyleFontWeight--}
```
public static BehaviorProperty getStyleFontWeight()
```

'style.fontWeight' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontStyle() {#getStyleFontStyle--}
```
public static BehaviorProperty getStyleFontStyle()
```

'style.fontStyle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleFontFamily() {#getStyleFontFamily--}
```
public static BehaviorProperty getStyleFontFamily()
```

'style.fontFamily' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectEmboss() {#getStyleTextEffectEmboss--}
```
public static BehaviorProperty getStyleTextEffectEmboss()
```

'style.textEffectEmboss' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextShadow() {#getStyleTextShadow--}
```
public static BehaviorProperty getStyleTextShadow()
```

'style.textShadow' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextTransform() {#getStyleTextTransform--}
```
public static BehaviorProperty getStyleTextTransform()
```

'style.textTransform' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationUnderline() {#getStyleTextDecorationUnderline--}
```
public static BehaviorProperty getStyleTextDecorationUnderline()
```

'style.textDecorationUnderline' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextEffectOutline() {#getStyleTextEffectOutline--}
```
public static BehaviorProperty getStyleTextEffectOutline()
```

'style.textEffectOutline' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleTextDecorationLineThrough() {#getStyleTextDecorationLineThrough--}
```
public static BehaviorProperty getStyleTextDecorationLineThrough()
```

'style.textDecorationLineThrough' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStyleSRotation() {#getStyleSRotation--}
```
public static BehaviorProperty getStyleSRotation()
```

'style.sRotation' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropTop() {#getImageDataCropTop--}
```
public static BehaviorProperty getImageDataCropTop()
```

'imageData.cropTop' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropBottom() {#getImageDataCropBottom--}
```
public static BehaviorProperty getImageDataCropBottom()
```

'imageData.cropBottom' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropLeft() {#getImageDataCropLeft--}
```
public static BehaviorProperty getImageDataCropLeft()
```

'imageData.cropLeft' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataCropRight() {#getImageDataCropRight--}
```
public static BehaviorProperty getImageDataCropRight()
```

'imageData.cropRight' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGain() {#getImageDataGain--}
```
public static BehaviorProperty getImageDataGain()
```

'imageData.gain' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataBlacklevel() {#getImageDataBlacklevel--}
```
public static BehaviorProperty getImageDataBlacklevel()
```

'imageData.blacklevel' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGamma() {#getImageDataGamma--}
```
public static BehaviorProperty getImageDataGamma()
```

'imageData.gamma' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataGrayscale() {#getImageDataGrayscale--}
```
public static BehaviorProperty getImageDataGrayscale()
```

'imageData.grayscale' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getImageDataChromakey() {#getImageDataChromakey--}
```
public static BehaviorProperty getImageDataChromakey()
```

'imageData.chromakey' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOn() {#getFillOn--}
```
public static BehaviorProperty getFillOn()
```

'fill.on' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillType() {#getFillType--}
```
public static BehaviorProperty getFillType()
```

'fill.type' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFill_Color() {#getFill-Color--}
```
public static BehaviorProperty getFill_Color()
```

'fill.color' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity() {#getFillOpacity--}
```
public static BehaviorProperty getFillOpacity()
```

'fill.opacity' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillColor2() {#getFillColor2--}
```
public static BehaviorProperty getFillColor2()
```

'fill.color2' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillMethod() {#getFillMethod--}
```
public static BehaviorProperty getFillMethod()
```

'fill.method' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillOpacity2() {#getFillOpacity2--}
```
public static BehaviorProperty getFillOpacity2()
```

'fill.opacity2' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillAngle() {#getFillAngle--}
```
public static BehaviorProperty getFillAngle()
```

'fill.angle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocus() {#getFillFocus--}
```
public static BehaviorProperty getFillFocus()
```

'fill.focus' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionX() {#getFillFocusPositionX--}
```
public static BehaviorProperty getFillFocusPositionX()
```

'fill.focusposition.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusPositionY() {#getFillFocusPositionY--}
```
public static BehaviorProperty getFillFocusPositionY()
```

'fill.focusposition.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeX() {#getFillFocusSizeX--}
```
public static BehaviorProperty getFillFocusSizeX()
```

'fill.focussize.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getFillFocusSizeY() {#getFillFocusSizeY--}
```
public static BehaviorProperty getFillFocusSizeY()
```

'fill.focussize.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOn() {#getStrokeOn--}
```
public static BehaviorProperty getStrokeOn()
```

'stroke.on' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor() {#getStrokeColor--}
```
public static BehaviorProperty getStrokeColor()
```

'stroke.color' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeWeight() {#getStrokeWeight--}
```
public static BehaviorProperty getStrokeWeight()
```

'stroke.weight' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeOpacity() {#getStrokeOpacity--}
```
public static BehaviorProperty getStrokeOpacity()
```

'stroke.opacity' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeLineStyle() {#getStrokeLineStyle--}
```
public static BehaviorProperty getStrokeLineStyle()
```

'stroke.linestyle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeDashStyle() {#getStrokeDashStyle--}
```
public static BehaviorProperty getStrokeDashStyle()
```

'stroke.dashstyle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeFillType() {#getStrokeFillType--}
```
public static BehaviorProperty getStrokeFillType()
```

'stroke.filltype' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeSrc() {#getStrokeSrc--}
```
public static BehaviorProperty getStrokeSrc()
```

'stroke.src' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeColor2() {#getStrokeColor2--}
```
public static BehaviorProperty getStrokeColor2()
```

'stroke.color2' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeX() {#getStrokeImageSizeX--}
```
public static BehaviorProperty getStrokeImageSizeX()
```

'stroke.imagesize.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeImageSizeY() {#getStrokeImageSizeY--}
```
public static BehaviorProperty getStrokeImageSizeY()
```

'stroke.imagesize.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrow() {#getStrokeStartArrow--}
```
public static BehaviorProperty getStrokeStartArrow()
```

'stroke.startArrow' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrow() {#getStrokeEndArrow--}
```
public static BehaviorProperty getStrokeEndArrow()
```

'stroke.endArrow' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowWidth() {#getStrokeStartArrowWidth--}
```
public static BehaviorProperty getStrokeStartArrowWidth()
```

'stroke.startArrowWidth' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeStartArrowLength() {#getStrokeStartArrowLength--}
```
public static BehaviorProperty getStrokeStartArrowLength()
```

'stroke.startArrowLength' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowWidth() {#getStrokeEndArrowWidth--}
```
public static BehaviorProperty getStrokeEndArrowWidth()
```

'stroke.endArrowWidth' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getStrokeEndArrowLength() {#getStrokeEndArrowLength--}
```
public static BehaviorProperty getStrokeEndArrowLength()
```

'stroke.endArrowLength' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOn() {#getShadowOn--}
```
public static BehaviorProperty getShadowOn()
```

'shadow.on' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowType() {#getShadowType--}
```
public static BehaviorProperty getShadowType()
```

'shadow.type' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor() {#getShadowColor--}
```
public static BehaviorProperty getShadowColor()
```

'shadow.color' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowColor2() {#getShadowColor2--}
```
public static BehaviorProperty getShadowColor2()
```

'shadow.color2' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOpacity() {#getShadowOpacity--}
```
public static BehaviorProperty getShadowOpacity()
```

'shadow.opacity' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetX() {#getShadowOffsetX--}
```
public static BehaviorProperty getShadowOffsetX()
```

'shadow.offset.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffsetY() {#getShadowOffsetY--}
```
public static BehaviorProperty getShadowOffsetY()
```

'shadow.offset.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2X() {#getShadowOffset2X--}
```
public static BehaviorProperty getShadowOffset2X()
```

'shadow.offset2.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOffset2Y() {#getShadowOffset2Y--}
```
public static BehaviorProperty getShadowOffset2Y()
```

'shadow.offset2.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginX() {#getShadowOriginX--}
```
public static BehaviorProperty getShadowOriginX()
```

'shadow.origin.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowOriginY() {#getShadowOriginY--}
```
public static BehaviorProperty getShadowOriginY()
```

'shadow.origin.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoX() {#getShadowMatrixXtoX--}
```
public static BehaviorProperty getShadowMatrixXtoX()
```

'shadow.matrix.xtox' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixXtoY() {#getShadowMatrixXtoY--}
```
public static BehaviorProperty getShadowMatrixXtoY()
```

'shadow.matrix.xtoy' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoX() {#getShadowMatrixYtoX--}
```
public static BehaviorProperty getShadowMatrixYtoX()
```

'shadow.matrix.ytox' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixYtoY() {#getShadowMatrixYtoY--}
```
public static BehaviorProperty getShadowMatrixYtoY()
```

'shadow.matrix.ytoy' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveX() {#getShadowMatrixPerspectiveX--}
```
public static BehaviorProperty getShadowMatrixPerspectiveX()
```

'shadow.matrix.perspectiveX' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getShadowMatrixPerspectiveY() {#getShadowMatrixPerspectiveY--}
```
public static BehaviorProperty getShadowMatrixPerspectiveY()
```

'shadow.matrix.perspectiveY' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOn() {#getSkewOn--}
```
public static BehaviorProperty getSkewOn()
```

'skew.on' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetX() {#getSkewOffsetX--}
```
public static BehaviorProperty getSkewOffsetX()
```

'skew.offset.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOffsetY() {#getSkewOffsetY--}
```
public static BehaviorProperty getSkewOffsetY()
```

'skew.offset.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginX() {#getSkewOriginX--}
```
public static BehaviorProperty getSkewOriginX()
```

'skew.origin.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewOriginY() {#getSkewOriginY--}
```
public static BehaviorProperty getSkewOriginY()
```

'skew.origin.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoX() {#getSkewMatrixXtoX--}
```
public static BehaviorProperty getSkewMatrixXtoX()
```

'skew.matrix.xtox' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixXtoY() {#getSkewMatrixXtoY--}
```
public static BehaviorProperty getSkewMatrixXtoY()
```

'skew.matrix.xtoy' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoX() {#getSkewMatrixYtoX--}
```
public static BehaviorProperty getSkewMatrixYtoX()
```

'skew.matrix.ytox' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixYtoY() {#getSkewMatrixYtoY--}
```
public static BehaviorProperty getSkewMatrixYtoY()
```

'skew.matrix.ytoy' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveX() {#getSkewMatrixPerspectiveX--}
```
public static BehaviorProperty getSkewMatrixPerspectiveX()
```

'skew.matrix.perspectiveX' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getSkewMatrixPerspectiveY() {#getSkewMatrixPerspectiveY--}
```
public static BehaviorProperty getSkewMatrixPerspectiveY()
```

'skew.matrix.perspectiveY' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOn() {#getExtrusionOn--}
```
public static BehaviorProperty getExtrusionOn()
```

'extrusion.on' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionType() {#getExtrusionType--}
```
public static BehaviorProperty getExtrusionType()
```

'extrusion.type' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRender() {#getExtrusionRender--}
```
public static BehaviorProperty getExtrusionRender()
```

'extrusion.render' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginX() {#getExtrusionViewPointOriginX--}
```
public static BehaviorProperty getExtrusionViewPointOriginX()
```

'extrusion.viewpointorigin.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointOriginY() {#getExtrusionViewPointOriginY--}
```
public static BehaviorProperty getExtrusionViewPointOriginY()
```

'extrusion.viewpointorigin.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointX() {#getExtrusionViewPointX--}
```
public static BehaviorProperty getExtrusionViewPointX()
```

'extrusion.viewpoint.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointY() {#getExtrusionViewPointY--}
```
public static BehaviorProperty getExtrusionViewPointY()
```

'extrusion.viewpoint.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionViewPointZ() {#getExtrusionViewPointZ--}
```
public static BehaviorProperty getExtrusionViewPointZ()
```

'extrusion.viewpoint.z' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionPlane() {#getExtrusionPlane--}
```
public static BehaviorProperty getExtrusionPlane()
```

'extrusion.plane' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAngle() {#getExtrusionSkewAngle--}
```
public static BehaviorProperty getExtrusionSkewAngle()
```

'extrusion.skewangle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionSkewAmt() {#getExtrusionSkewAmt--}
```
public static BehaviorProperty getExtrusionSkewAmt()
```

'extrusion.skewamt' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionBackDepth() {#getExtrusionBackDepth--}
```
public static BehaviorProperty getExtrusionBackDepth()
```

'extrusion.backdepth' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionForeDepth() {#getExtrusionForeDepth--}
```
public static BehaviorProperty getExtrusionForeDepth()
```

'extrusion.foredepth' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationX() {#getExtrusionOrientationX--}
```
public static BehaviorProperty getExtrusionOrientationX()
```

'extrusion.orientation.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationY() {#getExtrusionOrientationY--}
```
public static BehaviorProperty getExtrusionOrientationY()
```

'extrusion.orientation.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationZ() {#getExtrusionOrientationZ--}
```
public static BehaviorProperty getExtrusionOrientationZ()
```

'extrusion.orientation.z' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionOrientationAngle() {#getExtrusionOrientationAngle--}
```
public static BehaviorProperty getExtrusionOrientationAngle()
```

'extrusion.orientationangle' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColor() {#getExtrusionColor--}
```
public static BehaviorProperty getExtrusionColor()
```

'extrusion.color' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleX() {#getExtrusionRotationAngleX--}
```
public static BehaviorProperty getExtrusionRotationAngleX()
```

'extrusion.rotationangle.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationAngleY() {#getExtrusionRotationAngleY--}
```
public static BehaviorProperty getExtrusionRotationAngleY()
```

'extrusion.rotationangle.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionLockRotationCenter() {#getExtrusionLockRotationCenter--}
```
public static BehaviorProperty getExtrusionLockRotationCenter()
```

'extrusion.lockrotationcenter' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionAutoRotationCenter() {#getExtrusionAutoRotationCenter--}
```
public static BehaviorProperty getExtrusionAutoRotationCenter()
```

'extrusion.autorotationcenter' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterX() {#getExtrusionRotationCenterX--}
```
public static BehaviorProperty getExtrusionRotationCenterX()
```

'extrusion.rotationcenter.x' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterY() {#getExtrusionRotationCenterY--}
```
public static BehaviorProperty getExtrusionRotationCenterY()
```

'extrusion.rotationcenter.y' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionRotationCenterZ() {#getExtrusionRotationCenterZ--}
```
public static BehaviorProperty getExtrusionRotationCenterZ()
```

'extrusion.rotationcenter.z' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### getExtrusionColorMode() {#getExtrusionColorMode--}
```
public static BehaviorProperty getExtrusionColorMode()
```

'extrusion.colormode' 속성을 나타냅니다

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

이 객체가 다른 객체와 같은지 확인합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교 대상 객체. |

**반환:**  
boolean - 객체가 동일하면 true.

### hashCode() {#hashCode--}
```
public int hashCode()
```

(\#getValue.getValue) 속성을 기반으로 해시 코드를 계산하고 반환합니다.

**반환:**  
int - 이 객체의 해시 코드

### getOrCreateByValue(String propertyValue) {#getOrCreateByValue-java.lang.String-}
```
public static BehaviorProperty getOrCreateByValue(String propertyValue)
```

값으로 기존 동작 속성을 찾거나 지정된 값으로 새 사용자 정의 속성을 생성합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyValue | java.lang.String | 속성 값 |

**반환:**  
[BehaviorProperty](../../com.aspose.slides/behaviorproperty) - BehaviorProperty 인스턴스