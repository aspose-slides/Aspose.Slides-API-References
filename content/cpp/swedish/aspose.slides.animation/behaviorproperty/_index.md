---
title: BehaviorProperty
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskapstyper för animationsbeteende. Följer listan med egenskaper från  och
type: docs
weight: 53
url: /sv/aspose.slides.animation/behaviorproperty/
---
## BehaviorProperty klass

Representerar egenskapstyper för animationsbeteende. Följer listan med egenskaper från [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) och [https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx)

```cpp
class BehaviorProperty : public Aspose::Slides::Animation::IBehaviorProperty
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Kontrollerar om detta objekt är lika med ett annat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionAutoRotationCenter](./get_extrusionautorotationcenter/)() | Representerar 'extrusion.autorotationcenter' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionBackDepth](./get_extrusionbackdepth/)() | Representerar 'extrusion.backdepth' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColor](./get_extrusioncolor/)() | Representerar 'extrusion.color' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColorMode](./get_extrusioncolormode/)() | Representerar 'extrusion.colormode' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionForeDepth](./get_extrusionforedepth/)() | Representerar 'extrusion.foredepth' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionLockRotationCenter](./get_extrusionlockrotationcenter/)() | Representerar 'extrusion.lockrotationcenter' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOn](./get_extrusionon/)() | Representerar 'extrusion.on' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationAngle](./get_extrusionorientationangle/)() | Representerar 'extrusion.orientationangle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationX](./get_extrusionorientationx/)() | Representerar 'extrusion.orientation.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationY](./get_extrusionorientationy/)() | Representerar 'extrusion.orientation.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationZ](./get_extrusionorientationz/)() | Representerar 'extrusion.orientation.z' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionPlane](./get_extrusionplane/)() | Representerar 'extrusion.plane' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRender](./get_extrusionrender/)() | Representerar 'extrusion.render' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleX](./get_extrusionrotationanglex/)() | Representerar 'extrusion.rotationangle.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleY](./get_extrusionrotationangley/)() | Representerar 'extrusion.rotationangle.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterX](./get_extrusionrotationcenterx/)() | Representerar 'extrusion.rotationcenter.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterY](./get_extrusionrotationcentery/)() | Representerar 'extrusion.rotationcenter.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterZ](./get_extrusionrotationcenterz/)() | Representerar 'extrusion.rotationcenter.z' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAmt](./get_extrusionskewamt/)() | Representerar 'extrusion.skewamt' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAngle](./get_extrusionskewangle/)() | Representerar 'extrusion.skewangle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionType](./get_extrusiontype/)() | Representerar 'extrusion.type' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginX](./get_extrusionviewpointoriginx/)() | Representerar 'extrusion.viewpointorigin.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginY](./get_extrusionviewpointoriginy/)() | Representerar 'extrusion.viewpointorigin.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointX](./get_extrusionviewpointx/)() | Representerar 'extrusion.viewpoint.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointY](./get_extrusionviewpointy/)() | Representerar 'extrusion.viewpoint.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointZ](./get_extrusionviewpointz/)() | Representerar 'extrusion.viewpoint.z' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Fill_Color](./get_fill_color/)() | Representerar 'fill.color' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillAngle](./get_fillangle/)() | Representerar 'fill.angle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor](./get_fillcolor/)() | Representerar 'fillcolor' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor2](./get_fillcolor2/)() | Representerar 'fill.color2' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocus](./get_fillfocus/)() | Representerar 'fill.focus' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionX](./get_fillfocuspositionx/)() | Representerar 'fill.focusposition.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionY](./get_fillfocuspositiony/)() | Representerar 'fill.focusposition.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeX](./get_fillfocussizex/)() | Representerar 'fill.focussize.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeY](./get_fillfocussizey/)() | Representerar 'fill.focussize.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillMethod](./get_fillmethod/)() | Representerar 'fill.method' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOn](./get_fillon/)() | Representerar 'fill.on' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity](./get_fillopacity/)() | Representerar 'fill.opacity' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity2](./get_fillopacity2/)() | Representerar 'fill.opacity2' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillType](./get_filltype/)() | Representerar 'fill.type' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Image](./get_image/)() | Representerar 'image' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataBlacklevel](./get_imagedatablacklevel/)() | Representerar 'imageData.blacklevel' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataChromakey](./get_imagedatachromakey/)() | Representerar 'imageData.chromakey' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropBottom](./get_imagedatacropbottom/)() | Representerar 'imageData.cropBottom' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropLeft](./get_imagedatacropleft/)() | Representerar 'imageData.cropLeft' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropRight](./get_imagedatacropright/)() | Representerar 'imageData.cropRight' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropTop](./get_imagedatacroptop/)() | Representerar 'imageData.cropTop' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGain](./get_imagedatagain/)() | Representerar 'imageData.gain' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGamma](./get_imagedatagamma/)() | Representerar 'imageData.gamma' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGrayscale](./get_imagedatagrayscale/)() | Representerar 'imageData.grayscale' egenskap |
| **bool** [get_IsCustom](./get_iscustom/)() override | Visar om denna egenskap inte tillhör den fördefinierade egenskapslistan i specifikationen: [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptC](./get_pptc/)() | Representerar 'ppt_c' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptH](./get_ppth/)() | Representerar 'ppt_h' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptR](./get_pptr/)() | Representerar 'ppt_r' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptW](./get_pptw/)() | Representerar 'ppt_w' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptX](./get_pptx/)() | Representerar 'ppt_x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptY](./get_ppty/)() | Representerar 'ppt_y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_R](./get_r/)() | Representerar 'r' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleX](./get_scalex/)() | Representerar 'ScaleX' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleY](./get_scaley/)() | Representerar 'ScaleY' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor](./get_shadowcolor/)() | Representerar 'shadow.color' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor2](./get_shadowcolor2/)() | Representerar 'shadow.color2' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveX](./get_shadowmatrixperspectivex/)() | Representerar 'shadow.matrix.perspectiveX' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveY](./get_shadowmatrixperspectivey/)() | Representerar 'shadow.matrix.perspectiveY' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoX](./get_shadowmatrixxtox/)() | Representerar 'shadow.matrix.xtox' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoY](./get_shadowmatrixxtoy/)() | Representerar 'shadow.matrix.xtoy' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoX](./get_shadowmatrixytox/)() | Representerar 'shadow.matrix.ytox' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoY](./get_shadowmatrixytoy/)() | Representerar 'shadow.matrix.ytoy' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2X](./get_shadowoffset2x/)() | Representerar 'shadow.offset2.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2Y](./get_shadowoffset2y/)() | Representerar 'shadow.offset2.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetX](./get_shadowoffsetx/)() | Representerar 'shadow.offset.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetY](./get_shadowoffsety/)() | Representerar 'shadow.offset.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOn](./get_shadowon/)() | Representerar 'shadow.on' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOpacity](./get_shadowopacity/)() | Representerar 'shadow.opacity' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginX](./get_shadoworiginx/)() | Representerar 'shadow.origin.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginY](./get_shadoworiginy/)() | Representerar 'shadow.origin.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowType](./get_shadowtype/)() | Representerar 'shadow.type' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveX](./get_skewmatrixperspectivex/)() | Representerar 'skew.matrix.perspectiveX' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveY](./get_skewmatrixperspectivey/)() | Representerar 'skew.matrix.perspectiveY' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoX](./get_skewmatrixxtox/)() | Representerar 'skew.matrix.xtox' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoY](./get_skewmatrixxtoy/)() | Representerar 'skew.matrix.xtoy' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoX](./get_skewmatrixytox/)() | Representerar 'skew.matrix.ytox' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoY](./get_skewmatrixytoy/)() | Representerar 'skew.matrix.ytoy' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetX](./get_skewoffsetx/)() | Representerar 'skew.offset.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetY](./get_skewoffsety/)() | Representerar 'skew.offset.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOn](./get_skewon/)() | Representerar 'skew.on' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginX](./get_skeworiginx/)() | Representerar 'skew.origin.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginY](./get_skeworiginy/)() | Representerar 'skew.origin.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor](./get_strokecolor/)() | Representerar 'stroke.color' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor2](./get_strokecolor2/)() | Representerar 'stroke.color2' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeDashStyle](./get_strokedashstyle/)() | Representerar 'stroke.dashstyle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrow](./get_strokeendarrow/)() | Representerar 'stroke.endArrow' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowLength](./get_strokeendarrowlength/)() | Representerar 'stroke.endArrowLength' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowWidth](./get_strokeendarrowwidth/)() | Representerar 'stroke.endArrowWidth' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeFillType](./get_strokefilltype/)() | Representerar 'stroke.filltype' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeX](./get_strokeimagesizex/)() | Representerar 'stroke.imagesize.x' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeY](./get_strokeimagesizey/)() | Representerar 'stroke.imagesize.y' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeLineStyle](./get_strokelinestyle/)() | Representerar 'stroke.linestyle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOn](./get_strokeon/)() | Representerar 'stroke.on' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOpacity](./get_strokeopacity/)() | Representerar 'stroke.opacity' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeSrc](./get_strokesrc/)() | Representerar 'stroke.src' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrow](./get_strokestartarrow/)() | Representerar 'stroke.startArrow' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowLength](./get_strokestartarrowlength/)() | Representerar 'stroke.startArrowLength' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowWidth](./get_strokestartarrowwidth/)() | Representerar 'stroke.startArrowWidth' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeWeight](./get_strokeweight/)() | Representerar 'stroke.weight' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleColor](./get_stylecolor/)() | Representerar 'style.color' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontFamily](./get_stylefontfamily/)() | Representerar 'style.fontFamily' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontSize](./get_stylefontsize/)() | Representerar 'style.fontSize' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontStyle](./get_stylefontstyle/)() | Representerar 'style.fontStyle' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontWeight](./get_stylefontweight/)() | Representerar 'style.fontWeight' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleOpacity](./get_styleopacity/)() | Representerar 'style.opacity' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleRotation](./get_stylerotation/)() | Representerar 'style.rotation' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleSRotation](./get_stylesrotation/)() | Representerar 'style.sRotation' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationLineThrough](./get_styletextdecorationlinethrough/)() | Representerar 'style.textDecorationLineThrough' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationUnderline](./get_styletextdecorationunderline/)() | Representerar 'style.textDecorationUnderline' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectEmboss](./get_styletexteffectemboss/)() | Representerar 'style.textEffectEmboss' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectOutline](./get_styletexteffectoutline/)() | Representerar 'style.textEffectOutline' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextShadow](./get_styletextshadow/)() | Representerar 'style.textShadow' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextTransform](./get_styletexttransform/)() | Representerar 'style.textTransform' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleVisibility](./get_stylevisibility/)() | Representerar 'style.visibility' egenskap |
| [System::String](../../system/string/) [get_Value](./get_value/)() override | Värde för egenskapen |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_XShear](./get_xshear/)() | Representerar 'xshear' egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_YShear](./get_yshear/)() | Representerar 'yshear' egenskap |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Beräknar och returnerar hash-kod baserat på [BehaviorProperty::get_Value](./get_value/) egenskap |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [GetOrCreateByValue](./getorcreatebyvalue/)([System::String](../../system/string/)) | Söker efter befintlig beteende-egenskap efter värde eller skapar en ny anpassad med det angivna värdet |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen beskrivna av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satset för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'th mallparameter till en svag pekare (i stället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satset för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Class [IBehaviorProperty](../ibehaviorproperty/)
* Namespace [Aspose::Slides::Animation](../)
* Library [Aspose.Slides](../../)