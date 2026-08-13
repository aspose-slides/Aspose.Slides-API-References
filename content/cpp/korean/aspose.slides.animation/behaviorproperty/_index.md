---
title: BehaviorProperty
second_title: C++용 Aspose.Slides API 참조
description: 애니메이션 동작에 대한 속성 유형을 나타냅니다.  및 에서 속성 목록을 따릅니다.
type: docs
weight: 53
url: /ko/aspose.slides.animation/behaviorproperty/
---
## BehaviorProperty 클래스

애니메이션 동작에 대한 속성 유형을 나타냅니다. [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) 및 [https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx)에서 속성 목록을 따릅니다.

```cpp
class BehaviorProperty : public Aspose::Slides::Animation::IBehaviorProperty
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 이 객체가 다른 객체와 같은지 확인합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조형 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도( NaN 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동 소수점 비교를 에뮬레이트합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 전용입니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionAutoRotationCenter](./get_extrusionautorotationcenter/)() | 'extrusion.autorotationcenter' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionBackDepth](./get_extrusionbackdepth/)() | 'extrusion.backdepth' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColor](./get_extrusioncolor/)() | 'extrusion.color' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColorMode](./get_extrusioncolormode/)() | 'extrusion.colormode' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionForeDepth](./get_extrusionforedepth/)() | 'extrusion.foredepth' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionLockRotationCenter](./get_extrusionlockrotationcenter/)() | 'extrusion.lockrotationcenter' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOn](./get_extrusionon/)() | 'extrusion.on' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationAngle](./get_extrusionorientationangle/)() | 'extrusion.orientationangle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationX](./get_extrusionorientationx/)() | 'extrusion.orientation.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationY](./get_extrusionorientationy/)() | 'extrusion.orientation.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationZ](./get_extrusionorientationz/)() | 'extrusion.orientation.z' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionPlane](./get_extrusionplane/)() | 'extrusion.plane' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRender](./get_extrusionrender/)() | 'extrusion.render' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleX](./get_extrusionrotationanglex/)() | 'extrusion.rotationangle.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleY](./get_extrusionrotationangley/)() | 'extrusion.rotationangle.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterX](./get_extrusionrotationcenterx/)() | 'extrusion.rotationcenter.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterY](./get_extrusionrotationcentery/)() | 'extrusion.rotationcenter.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterZ](./get_extrusionrotationcenterz/)() | 'extrusion.rotationcenter.z' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAmt](./get_extrusionskewamt/)() | 'extrusion.skewamt' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAngle](./get_extrusionskewangle/)() | 'extrusion.skewangle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionType](./get_extrusiontype/)() | 'extrusion.type' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginX](./get_extrusionviewpointoriginx/)() | 'extrusion.viewpointorigin.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginY](./get_extrusionviewpointoriginy/)() | 'extrusion.viewpointorigin.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointX](./get_extrusionviewpointx/)() | 'extrusion.viewpoint.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointY](./get_extrusionviewpointy/)() | 'extrusion.viewpoint.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointZ](./get_extrusionviewpointz/)() | 'extrusion.viewpoint.z' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Fill_Color](./get_fill_color/)() | 'fill.color' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillAngle](./get_fillangle/)() | 'fill.angle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor](./get_fillcolor/)() | 'fillcolor' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor2](./get_fillcolor2/)() | 'fill.color2' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocus](./get_fillfocus/)() | 'fill.focus' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionX](./get_fillfocuspositionx/)() | 'fill.focusposition.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionY](./get_fillfocuspositiony/)() | 'fill.focusposition.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeX](./get_fillfocussizex/)() | 'fill.focussize.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeY](./get_fillfocussizey/)() | 'fill.focussize.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillMethod](./get_fillmethod/)() | 'fill.method' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOn](./get_fillon/)() | 'fill.on' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity](./get_fillopacity/)() | 'fill.opacity' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity2](./get_fillopacity2/)() | 'fill.opacity2' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillType](./get_filltype/)() | 'fill.type' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Image](./get_image/)() | 'image' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataBlacklevel](./get_imagedatablacklevel/)() | 'imageData.blacklevel' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataChromakey](./get_imagedatachromakey/)() | 'imageData.chromakey' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropBottom](./get_imagedatacropbottom/)() | 'imageData.cropBottom' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropLeft](./get_imagedatacropleft/)() | 'imageData.cropLeft' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropRight](./get_imagedatacropright/)() | 'imageData.cropRight' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropTop](./get_imagedatacroptop/)() | 'imageData.cropTop' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGain](./get_imagedatagain/)() | 'imageData.gain' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGamma](./get_imagedatagamma/)() | 'imageData.gamma' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGrayscale](./get_imagedatagrayscale/)() | 'imageData.grayscale' 속성을 나타냅니다. |
| **bool** [get_IsCustom](./get_iscustom/)() override | 이 속성이 사양의 미리 정의된 속성 목록에 속하지 않는지 표시합니다: [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptC](./get_pptc/)() | 'ppt_c' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptH](./get_ppth/)() | 'ppt_h' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptR](./get_pptr/)() | 'ppt_r' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptW](./get_pptw/)() | 'ppt_w' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptX](./get_pptx/)() | 'ppt_x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptY](./get_ppty/)() | 'ppt_y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_R](./get_r/)() | 'r' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleX](./get_scalex/)() | 'ScaleX' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleY](./get_scaley/)() | 'ScaleY' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor](./get_shadowcolor/)() | 'shadow.color' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor2](./get_shadowcolor2/)() | 'shadow.color2' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveX](./get_shadowmatrixperspectivex/)() | 'shadow.matrix.perspectiveX' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveY](./get_shadowmatrixperspectivey/)() | 'shadow.matrix.perspectiveY' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoX](./get_shadowmatrixxtox/)() | 'shadow.matrix.xtox' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoY](./get_shadowmatrixxtoy/)() | 'shadow.matrix.xtoy' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoX](./get_shadowmatrixytox/)() | 'shadow.matrix.ytox' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoY](./get_shadowmatrixytoy/)() | 'shadow.matrix.ytoy' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2X](./get_shadowoffset2x/)() | 'shadow.offset2.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2Y](./get_shadowoffset2y/)() | 'shadow.offset2.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetX](./get_shadowoffsetx/)() | 'shadow.offset.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetY](./get_shadowoffsety/)() | 'shadow.offset.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOn](./get_shadowon/)() | 'shadow.on' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOpacity](./get_shadowopacity/)() | 'shadow.opacity' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginX](./get_shadoworiginx/)() | 'shadow.origin.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginY](./get_shadoworiginy/)() | 'shadow.origin.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowType](./get_shadowtype/)() | 'shadow.type' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveX](./get_skewmatrixperspectivex/)() | 'skew.matrix.perspectiveX' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveY](./get_skewmatrixperspectivey/)() | 'skew.matrix.perspectiveY' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoX](./get_skewmatrixxtox/)() | 'skew.matrix.xtox' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoY](./get_skewmatrixxtoy/)() | 'skew.matrix.xtoy' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoX](./get_skewmatrixytox/)() | 'skew.matrix.ytox' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoY](./get_skewmatrixytoy/)() | 'skew.matrix.ytoy' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetX](./get_skewoffsetx/)() | 'skew.offset.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetY](./get_skewoffsety/)() | 'skew.offset.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOn](./get_skewon/)() | 'skew.on' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginX](./get_skeworiginx/)() | 'skew.origin.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginY](./get_skeworiginy/)() | 'skew.origin.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor](./get_strokecolor/)() | 'stroke.color' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor2](./get_strokecolor2/)() | 'stroke.color2' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeDashStyle](./get_strokedashstyle/)() | 'stroke.dashstyle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrow](./get_strokeendarrow/)() | 'stroke.endArrow' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowLength](./get_strokeendarrowlength/)() | 'stroke.endArrowLength' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowWidth](./get_strokeendarrowwidth/)() | 'stroke.endArrowWidth' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeFillType](./get_strokefilltype/)() | 'stroke.filltype' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeX](./get_strokeimagesizex/)() | 'stroke.imagesize.x' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeY](./get_strokeimagesizey/)() | 'stroke.imagesize.y' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeLineStyle](./get_strokelinestyle/)() | 'stroke.linestyle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOn](./get_strokeon/)() | 'stroke.on' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOpacity](./get_strokeopacity/)() | 'stroke.opacity' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeSrc](./get_strokesrc/)() | 'stroke.src' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrow](./get_strokestartarrow/)() | 'stroke.startArrow' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowLength](./get_strokestartarrowlength/)() | 'stroke.startArrowLength' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowWidth](./get_strokestartarrowwidth/)() | 'stroke.startArrowWidth' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeWeight](./get_strokeweight/)() | 'stroke.weight' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleColor](./get_stylecolor/)() | 'style.color' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontFamily](./get_stylefontfamily/)() | 'style.fontFamily' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontSize](./get_stylefontsize/)() | 'style.fontSize' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontStyle](./get_stylefontstyle/)() | 'style.fontStyle' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontWeight](./get_stylefontweight/)() | 'style.fontWeight' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleOpacity](./get_styleopacity/)() | 'style.opacity' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleRotation](./get_stylerotation/)() | 'style.rotation' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleSRotation](./get_stylesrotation/)() | 'style.sRotation' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationLineThrough](./get_styletextdecorationlinethrough/)() | 'style.textDecorationLineThrough' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationUnderline](./get_styletextdecorationunderline/)() | 'style.textDecorationUnderline' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectEmboss](./get_styletexteffectemboss/)() | 'style.textEffectEmboss' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectOutline](./get_styletexteffectoutline/)() | 'style.textEffectOutline' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextShadow](./get_styletextshadow/)() | 'style.textShadow' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextTransform](./get_styletexttransform/)() | 'style.textTransform' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleVisibility](./get_stylevisibility/)() | 'style.visibility' 속성을 나타냅니다. |
| [System::String](../../system/string/) [get_Value](./get_value/)() override | 속성의 값 |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_XShear](./get_xshear/)() | 'xshear' 속성을 나타냅니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_YShear](./get_yshear/)() | 'yshear' 속성을 나타냅니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | [BehaviorProperty::get_Value](./get_value/) 속성을 기반으로 해시 코드를 계산하고 반환합니다. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [GetOrCreateByValue](./getorcreatebyvalue/)([System::String](../../system/string/)) | 값으로 기존 동작 속성을 찾거나 지정된 값으로 새로운 사용자 정의 속성을 생성합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형 복제를 활성화합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로 아무 것도 복사하지 않으며, 새 객체를 초기화하고 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 참조로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 참조 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열과 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인수를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출하면 안 되며, 대신 스마트 포인터와 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [IBehaviorProperty](../ibehaviorproperty/)
* 네임스페이스 [Aspose::Slides::Animation](../)
* 라이브러리 [Aspose.Slides](../../)