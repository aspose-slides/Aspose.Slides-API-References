---
title: BehaviorProperty
second_title: Referência da API Aspose.Slides para C++
description: Representa tipos de propriedade para comportamento de animação. Segue a lista de propriedades de  e
type: docs
weight: 53
url: /pt/aspose.slides.animation/behaviorproperty/
---
## BehaviorProperty classe

Representa tipos de propriedade para comportamento de animação. Segue a lista de propriedades de [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) e [https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx)

```cpp
class BehaviorProperty : public Aspose::Slides::Animation::IBehaviorProperty
```

## Métodos

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Verifica se este objeto é igual a outro. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionAutoRotationCenter](./get_extrusionautorotationcenter/)() | Representa a propriedade 'extrusion.autorotationcenter' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionBackDepth](./get_extrusionbackdepth/)() | Representa a propriedade 'extrusion.backdepth' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColor](./get_extrusioncolor/)() | Representa a propriedade 'extrusion.color' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColorMode](./get_extrusioncolormode/)() | Representa a propriedade 'extrusion.colormode' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionForeDepth](./get_extrusionforedepth/)() | Representa a propriedade 'extrusion.foredepth' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionLockRotationCenter](./get_extrusionlockrotationcenter/)() | Representa a propriedade 'extrusion.lockrotationcenter' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOn](./get_extrusionon/)() | Representa a propriedade 'extrusion.on' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationAngle](./get_extrusionorientationangle/)() | Representa a propriedade 'extrusion.orientationangle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationX](./get_extrusionorientationx/)() | Representa a propriedade 'extrusion.orientation.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationY](./get_extrusionorientationy/)() | Representa a propriedade 'extrusion.orientation.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationZ](./get_extrusionorientationz/)() | Representa a propriedade 'extrusion.orientation.z' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionPlane](./get_extrusionplane/)() | Representa a propriedade 'extrusion.plane' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRender](./get_extrusionrender/)() | Representa a propriedade 'extrusion.render' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleX](./get_extrusionrotationanglex/)() | Representa a propriedade 'extrusion.rotationangle.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleY](./get_extrusionrotationangley/)() | Representa a propriedade 'extrusion.rotationangle.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterX](./get_extrusionrotationcenterx/)() | Representa a propriedade 'extrusion.rotationcenter.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterY](./get_extrusionrotationcentery/)() | Representa a propriedade 'extrusion.rotationcenter.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterZ](./get_extrusionrotationcenterz/)() | Representa a propriedade 'extrusion.rotationcenter.z' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAmt](./get_extrusionskewamt/)() | Representa a propriedade 'extrusion.skewamt' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAngle](./get_extrusionskewangle/)() | Representa a propriedade 'extrusion.skewangle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionType](./get_extrusiontype/)() | Representa a propriedade 'extrusion.type' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginX](./get_extrusionviewpointoriginx/)() | Representa a propriedade 'extrusion.viewpointorigin.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginY](./get_extrusionviewpointoriginy/)() | Representa a propriedade 'extrusion.viewpointorigin.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointX](./get_extrusionviewpointx/)() | Representa a propriedade 'extrusion.viewpoint.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointY](./get_extrusionviewpointy/)() | Representa a propriedade 'extrusion.viewpoint.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointZ](./get_extrusionviewpointz/)() | Representa a propriedade 'extrusion.viewpoint.z' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Fill_Color](./get_fill_color/)() | Representa a propriedade 'fill.color' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillAngle](./get_fillangle/)() | Representa a propriedade 'fill.angle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor](./get_fillcolor/)() | Representa a propriedade 'fillcolor' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor2](./get_fillcolor2/)() | Representa a propriedade 'fill.color2' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocus](./get_fillfocus/)() | Representa a propriedade 'fill.focus' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionX](./get_fillfocuspositionx/)() | Representa a propriedade 'fill.focusposition.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionY](./get_fillfocuspositiony/)() | Representa a propriedade 'fill.focusposition.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeX](./get_fillfocussizex/)() | Representa a propriedade 'fill.focussize.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeY](./get_fillfocussizey/)() | Representa a propriedade 'fill.focussize.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillMethod](./get_fillmethod/)() | Representa a propriedade 'fill.method' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOn](./get_fillon/)() | Representa a propriedade 'fill.on' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity](./get_fillopacity/)() | Representa a propriedade 'fill.opacity' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity2](./get_fillopacity2/)() | Representa a propriedade 'fill.opacity2' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillType](./get_filltype/)() | Representa a propriedade 'fill.type' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Image](./get_image/)() | Representa a propriedade 'image' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataBlacklevel](./get_imagedatablacklevel/)() | Representa a propriedade 'imageData.blacklevel' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataChromakey](./get_imagedatachromakey/)() | Representa a propriedade 'imageData.chromakey' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropBottom](./get_imagedatacropbottom/)() | Representa a propriedade 'imageData.cropBottom' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropLeft](./get_imagedatacropleft/)() | Representa a propriedade 'imageData.cropLeft' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropRight](./get_imagedatacropright/)() | Representa a propriedade 'imageData.cropRight' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropTop](./get_imagedatacroptop/)() | Representa a propriedade 'imageData.cropTop' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGain](./get_imagedatagain/)() | Representa a propriedade 'imageData.gain' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGamma](./get_imagedatagamma/)() | Representa a propriedade 'imageData.gamma' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGrayscale](./get_imagedatagrayscale/)() | Representa a propriedade 'imageData.grayscale' |
| **bool** [get_IsCustom](./get_iscustom/)() override | Mostra se esta propriedade não pertence à lista de propriedades pré-definidas na especificação: [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptC](./get_pptc/)() | Representa a propriedade 'ppt_c' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptH](./get_ppth/)() | Representa a propriedade 'ppt_h' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptR](./get_pptr/)() | Representa a propriedade 'ppt_r' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptW](./get_pptw/)() | Representa a propriedade 'ppt_w' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptX](./get_pptx/)() | Representa a propriedade 'ppt_x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptY](./get_ppty/)() | Representa a propriedade 'ppt_y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_R](./get_r/)() | Representa a propriedade 'r' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleX](./get_scalex/)() | Representa a propriedade 'ScaleX' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleY](./get_scaley/)() | Representa a propriedade 'ScaleY' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor](./get_shadowcolor/)() | Representa a propriedade 'shadow.color' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor2](./get_shadowcolor2/)() | Representa a propriedade 'shadow.color2' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveX](./get_shadowmatrixperspectivex/)() | Representa a propriedade 'shadow.matrix.perspectiveX' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveY](./get_shadowmatrixperspectivey/)() | Representa a propriedade 'shadow.matrix.perspectiveY' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoX](./get_shadowmatrixxtox/)() | Representa a propriedade 'shadow.matrix.xtox' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoY](./get_shadowmatrixxtoy/)() | Representa a propriedade 'shadow.matrix.xtoy' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoX](./get_shadowmatrixytox/)() | Representa a propriedade 'shadow.matrix.ytox' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoY](./get_shadowmatrixytoy/)() | Representa a propriedade 'shadow.matrix.ytoy' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2X](./get_shadowoffset2x/)() | Representa a propriedade 'shadow.offset2.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2Y](./get_shadowoffset2y/)() | Representa a propriedade 'shadow.offset2.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetX](./get_shadowoffsetx/)() | Representa a propriedade 'shadow.offset.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetY](./get_shadowoffsety/)() | Representa a propriedade 'shadow.offset.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOn](./get_shadowon/)() | Representa a propriedade 'shadow.on' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOpacity](./get_shadowopacity/)() | Representa a propriedade 'shadow.opacity' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginX](./get_shadoworiginx/)() | Representa a propriedade 'shadow.origin.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginY](./get_shadoworiginy/)() | Representa a propriedade 'shadow.origin.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowType](./get_shadowtype/)() | Representa a propriedade 'shadow.type' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveX](./get_skewmatrixperspectivex/)() | Representa a propriedade 'skew.matrix.perspectiveX' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveY](./get_skewmatrixperspectivey/)() | Representa a propriedade 'skew.matrix.perspectiveY' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoX](./get_skewmatrixxtox/)() | Representa a propriedade 'skew.matrix.xtox' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoY](./get_skewmatrixxtoy/)() | Representa a propriedade 'skew.matrix.xtoy' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoX](./get_skewmatrixytox/)() | Representa a propriedade 'skew.matrix.ytox' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoY](./get_skewmatrixytoy/)() | Representa a propriedade 'skew.matrix.ytoy' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetX](./get_skewoffsetx/)() | Representa a propriedade 'skew.offset.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetY](./get_skewoffsety/)() | Representa a propriedade 'skew.offset.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOn](./get_skewon/)() | Representa a propriedade 'skew.on' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginX](./get_skeworiginx/)() | Representa a propriedade 'skew.origin.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginY](./get_skeworiginy/)() | Representa a propriedade 'skew.origin.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor](./get_strokecolor/)() | Representa a propriedade 'stroke.color' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor2](./get_strokecolor2/)() | Representa a propriedade 'stroke.color2' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeDashStyle](./get_strokedashstyle/)() | Representa a propriedade 'stroke.dashstyle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrow](./get_strokeendarrow/)() | Representa a propriedade 'stroke.endArrow' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowLength](./get_strokeendarrowlength/)() | Representa a propriedade 'stroke.endArrowLength' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowWidth](./get_strokeendarrowwidth/)() | Representa a propriedade 'stroke.endArrowWidth' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeFillType](./get_strokefilltype/)() | Representa a propriedade 'stroke.filltype' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeX](./get_strokeimagesizex/)() | Representa a propriedade 'stroke.imagesize.x' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeY](./get_strokeimagesizey/)() | Representa a propriedade 'stroke.imagesize.y' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeLineStyle](./get_strokelinestyle/)() | Representa a propriedade 'stroke.linestyle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOn](./get_strokeon/)() | Representa a propriedade 'stroke.on' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOpacity](./get_strokeopacity/)() | Representa a propriedade 'stroke.opacity' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeSrc](./get_strokesrc/)() | Representa a propriedade 'stroke.src' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrow](./get_strokestartarrow/)() | Representa a propriedade 'stroke.startArrow' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowLength](./get_strokestartarrowlength/)() | Representa a propriedade 'stroke.startArrowLength' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowWidth](./get_strokestartarrowwidth/)() | Representa a propriedade 'stroke.startArrowWidth' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeWeight](./get_strokeweight/)() | Representa a propriedade 'stroke.weight' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleColor](./get_stylecolor/)() | Representa a propriedade 'style.color' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontFamily](./get_stylefontfamily/)() | Representa a propriedade 'style.fontFamily' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontSize](./get_stylefontsize/)() | Representa a propriedade 'style.fontSize' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontStyle](./get_stylefontstyle/)() | Representa a propriedade 'style.fontStyle' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontWeight](./get_stylefontweight/)() | Representa a propriedade 'style.fontWeight' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleOpacity](./get_styleopacity/)() | Representa a propriedade 'style.opacity' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleRotation](./get_stylerotation/)() | Representa a propriedade 'style.rotation' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleSRotation](./get_stylesrotation/)() | Representa a propriedade 'style.sRotation' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationLineThrough](./get_styletextdecorationlinethrough/)() | Representa a propriedade 'style.textDecorationLineThrough' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationUnderline](./get_styletextdecorationunderline/)() | Representa a propriedade 'style.textDecorationUnderline' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectEmboss](./get_styletexteffectemboss/)() | Representa a propriedade 'style.textEffectEmboss' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectOutline](./get_styletexteffectoutline/)() | Representa a propriedade 'style.textEffectOutline' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextShadow](./get_styletextshadow/)() | Representa a propriedade 'style.textShadow' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextTransform](./get_styletexttransform/)() | Representa a propriedade 'style.textTransform' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleVisibility](./get_stylevisibility/)() | Representa a propriedade 'style.visibility' |
| [System::String](../../system/string/) [get_Value](./get_value/)() override | Valor da propriedade |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_XShear](./get_xshear/)() | Representa a propriedade 'xshear' |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_YShear](./get_yshear/)() | Representa a propriedade 'yshear' |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Calcula e retorna o código hash baseado na propriedade [BehaviorProperty::get_Value](./get_value/) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [GetOrCreateByValue](./getorcreatebyvalue/)([System::String](../../system/string/)) | Procura por uma propriedade de comportamento existente pelo valor ou cria uma nova personalizada com o valor especificado |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja também

* Classe [IBehaviorProperty](../ibehaviorproperty/)
* Espaço de nomes [Aspose::Slides::Animation](../)
* Biblioteca [Aspose.Slides](../../)