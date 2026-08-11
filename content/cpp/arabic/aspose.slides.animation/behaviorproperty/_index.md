---
title: BehaviorProperty
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل أنواع الخصائص لسلوك الرسوم المتحركة. يتبع قائمة الخصائص من  و
type: docs
weight: 53
url: /ar/aspose.slides.animation/behaviorproperty/
---
## BehaviorProperty فئة

يمثل أنواع الخصائص لسلوك الرسوم المتحركة. يتبع قائمة الخصائص من [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) و [https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx)

```cpp
class BehaviorProperty : public Aspose::Slides::Animation::IBehaviorProperty
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | يتحقق مما إذا كان هذا الكائن مساويًا لآخر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام سلوكيات C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بنمط C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN-انان متساويتين بالرغم من أن IEC 60559:1989 يُعرّف أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بنمط C# حيث تُعتبر NaN-انان متساويتين بالرغم من أن IEC 60559:1989 يُعرّف أن NaN غير مساوي لأي قيمة، بما فيها NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionAutoRotationCenter](./get_extrusionautorotationcenter/)() | يمثل خاصية 'extrusion.autorotationcenter'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionBackDepth](./get_extrusionbackdepth/)() | يمثل خاصية 'extrusion.backdepth'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColor](./get_extrusioncolor/)() | يمثل خاصية 'extrusion.color'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColorMode](./get_extrusioncolormode/)() | يمثل خاصية 'extrusion.colormode'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionForeDepth](./get_extrusionforedepth/)() | يمثل خاصية 'extrusion.foredepth'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionLockRotationCenter](./get_extrusionlockrotationcenter/)() | يمثل خاصية 'extrusion.lockrotationcenter'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOn](./get_extrusionon/)() | يمثل خاصية 'extrusion.on'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationAngle](./get_extrusionorientationangle/)() | يمثل خاصية 'extrusion.orientationangle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationX](./get_extrusionorientationx/)() | يمثل خاصية 'extrusion.orientation.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationY](./get_extrusionorientationy/)() | يمثل خاصية 'extrusion.orientation.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationZ](./get_extrusionorientationz/)() | يمثل خاصية 'extrusion.orientation.z'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionPlane](./get_extrusionplane/)() | يمثل خاصية 'extrusion.plane'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRender](./get_extrusionrender/)() | يمثل خاصية 'extrusion.render'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleX](./get_extrusionrotationanglex/)() | يمثل خاصية 'extrusion.rotationangle.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleY](./get_extrusionrotationangley/)() | يمثل خاصية 'extrusion.rotationangle.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterX](./get_extrusionrotationcenterx/)() | يمثل خاصية 'extrusion.rotationcenter.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterY](./get_extrusionrotationcentery/)() | يمثل خاصية 'extrusion.rotationcenter.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterZ](./get_extrusionrotationcenterz/)() | يمثل خاصية 'extrusion.rotationcenter.z'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAmt](./get_extrusionskewamt/)() | يمثل خاصية 'extrusion.skewamt'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAngle](./get_extrusionskewangle/)() | يمثل خاصية 'extrusion.skewangle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionType](./get_extrusiontype/)() | يمثل خاصية 'extrusion.type'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginX](./get_extrusionviewpointoriginx/)() | يمثل خاصية 'extrusion.viewpointorigin.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginY](./get_extrusionviewpointoriginy/)() | يمثل خاصية 'extrusion.viewpointorigin.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointX](./get_extrusionviewpointx/)() | يمثل خاصية 'extrusion.viewpoint.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointY](./get_extrusionviewpointy/)() | يمثل خاصية 'extrusion.viewpoint.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointZ](./get_extrusionviewpointz/)() | يمثل خاصية 'extrusion.viewpoint.z'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Fill_Color](./get_fill_color/)() | يمثل خاصية 'fill.color'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillAngle](./get_fillangle/)() | يمثل خاصية 'fill.angle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor](./get_fillcolor/)() | يمثل خاصية 'fillcolor'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor2](./get_fillcolor2/)() | يمثل خاصية 'fill.color2'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocus](./get_fillfocus/)() | يمثل خاصية 'fill.focus'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionX](./get_fillfocuspositionx/)() | يمثل خاصية 'fill.focusposition.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionY](./get_fillfocuspositiony/)() | يمثل خاصية 'fill.focusposition.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeX](./get_fillfocussizex/)() | يمثل خاصية 'fill.focussize.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeY](./get_fillfocussizey/)() | يمثل خاصية 'fill.focussize.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillMethod](./get_fillmethod/)() | يمثل خاصية 'fill.method'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOn](./get_fillon/)() | يمثل خاصية 'fill.on'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity](./get_fillopacity/)() | يمثل خاصية 'fill.opacity'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity2](./get_fillopacity2/)() | يمثل خاصية 'fill.opacity2'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillType](./get_filltype/)() | يمثل خاصية 'fill.type'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Image](./get_image/)() | يمثل خاصية 'image'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataBlacklevel](./get_imagedatablacklevel/)() | يمثل خاصية 'imageData.blacklevel'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataChromakey](./get_imagedatachromakey/)() | يمثل خاصية 'imageData.chromakey'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropBottom](./get_imagedatacropbottom/)() | يمثل خاصية 'imageData.cropBottom'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropLeft](./get_imagedatacropleft/)() | يمثل خاصية 'imageData.cropLeft'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropRight](./get_imagedatacropright/)() | يمثل خاصية 'imageData.cropRight'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropTop](./get_imagedatacroptop/)() | يمثل خاصية 'imageData.cropTop'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGain](./get_imagedatagain/)() | يمثل خاصية 'imageData.gain'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGamma](./get_imagedatagamma/)() | يمثل خاصية 'imageData.gamma'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGrayscale](./get_imagedatagrayscale/)() | يمثل خاصية 'imageData.grayscale'. |
| **bool** [get_IsCustom](./get_iscustom/)() override | يُظهر ما إذا كانت هذه الخاصية لا تنتمي إلى قائمة الخصائص المحددة في المواصفة: [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptC](./get_pptc/)() | يمثل خاصية 'ppt_c'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptH](./get_ppth/)() | يمثل خاصية 'ppt_h'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptR](./get_pptr/)() | يمثل خاصية 'ppt_r'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptW](./get_pptw/)() | يمثل خاصية 'ppt_w'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptX](./get_pptx/)() | يمثل خاصية 'ppt_x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptY](./get_ppty/)() | يمثل خاصية 'ppt_y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_R](./get_r/)() | يمثل خاصية 'r'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleX](./get_scalex/)() | يمثل خاصية 'ScaleX'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleY](./get_scaley/)() | يمثل خاصية 'ScaleY'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor](./get_shadowcolor/)() | يمثل خاصية 'shadow.color'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor2](./get_shadowcolor2/)() | يمثل خاصية 'shadow.color2'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveX](./get_shadowmatrixperspectivex/)() | يمثل خاصية 'shadow.matrix.perspectiveX'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveY](./get_shadowmatrixperspectivey/)() | يمثل خاصية 'shadow.matrix.perspectiveY'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoX](./get_shadowmatrixxtox/)() | يمثل خاصية 'shadow.matrix.xtox'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoY](./get_shadowmatrixxtoy/)() | يمثل خاصية 'shadow.matrix.xtoy'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoX](./get_shadowmatrixytox/)() | يمثل خاصية 'shadow.matrix.ytox'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoY](./get_shadowmatrixytoy/)() | يمثل خاصية 'shadow.matrix.ytoy'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2X](./get_shadowoffset2x/)() | يمثل خاصية 'shadow.offset2.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2Y](./get_shadowoffset2y/)() | يمثل خاصية 'shadow.offset2.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetX](./get_shadowoffsetx/)() | يمثل خاصية 'shadow.offset.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetY](./get_shadowoffsety/)() | يمثل خاصية 'shadow.offset.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOn](./get_shadowon/)() | يمثل خاصية 'shadow.on'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOpacity](./get_shadowopacity/)() | يمثل خاصية 'shadow.opacity'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginX](./get_shadoworiginx/)() | يمثل خاصية 'shadow.origin.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginY](./get_shadoworiginy/)() | يمثل خاصية 'shadow.origin.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowType](./get_shadowtype/)() | يمثل خاصية 'shadow.type'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveX](./get_skewmatrixperspectivex/)() | يمثل خاصية 'skew.matrix.perspectiveX'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveY](./get_skewmatrixperspectivey/)() | يمثل خاصية 'skew.matrix.perspectiveY'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoX](./get_skewmatrixxtox/)() | يمثل خاصية 'skew.matrix.xtox'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoY](./get_skewmatrixxtoy/)() | يمثل خاصية 'skew.matrix.xtoy'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoX](./get_skewmatrixytox/)() | يمثل خاصية 'skew.matrix.ytox'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoY](./get_skewmatrixytoy/)() | يمثل خاصية 'skew.matrix.ytoy'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetX](./get_skewoffsetx/)() | يمثل خاصية 'skew.offset.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetY](./get_skewoffsety/)() | يمثل خاصية 'skew.offset.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOn](./get_skewon/)() | يمثل خاصية 'skew.on'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginX](./get_skeworiginx/)() | يمثل خاصية 'skew.origin.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginY](./get_skeworiginy/)() | يمثل خاصية 'skew.origin.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor](./get_strokecolor/)() | يمثل خاصية 'stroke.color'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor2](./get_strokecolor2/)() | يمثل خاصية 'stroke.color2'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeDashStyle](./get_strokedashstyle/)() | يمثل خاصية 'stroke.dashstyle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrow](./get_strokeendarrow/)() | يمثل خاصية 'stroke.endArrow'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowLength](./get_strokeendarrowlength/)() | يمثل خاصية 'stroke.endArrowLength'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowWidth](./get_strokeendarrowwidth/)() | يمثل خاصية 'stroke.endArrowWidth'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeFillType](./get_strokefilltype/)() | يمثل خاصية 'stroke.filltype'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeX](./get_strokeimagesizex/)() | يمثل خاصية 'stroke.imagesize.x'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeY](./get_strokeimagesizey/)() | يمثل خاصية 'stroke.imagesize.y'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeLineStyle](./get_strokelinestyle/)() | يمثل خاصية 'stroke.linestyle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOn](./get_strokeon/)() | يمثل خاصية 'stroke.on'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOpacity](./get_strokeopacity/)() | يمثل خاصية 'stroke.opacity'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeSrc](./get_strokesrc/)() | يمثل خاصية 'stroke.src'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrow](./get_strokestartarrow/)() | يمثل خاصية 'stroke.startArrow'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowLength](./get_strokestartarrowlength/)() | يمثل خاصية 'stroke.startArrowLength'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowWidth](./get_strokestartarrowwidth/)() | يمثل خاصية 'stroke.startArrowWidth'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeWeight](./get_strokeweight/)() | يمثل خاصية 'stroke.weight'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleColor](./get_stylecolor/)() | يمثل خاصية 'style.color'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontFamily](./get_stylefontfamily/)() | يمثل خاصية 'style.fontFamily'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontSize](./get_stylefontsize/)() | يمثل خاصية 'style.fontSize'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontStyle](./get_stylefontstyle/)() | يمثل خاصية 'style.fontStyle'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontWeight](./get_stylefontweight/)() | يمثل خاصية 'style.fontWeight'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleOpacity](./get_styleopacity/)() | يمثل خاصية 'style.opacity'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleRotation](./get_stylerotation/)() | يمثل خاصية 'style.rotation'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleSRotation](./get_stylesrotation/)() | يمثل خاصية 'style.sRotation'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationLineThrough](./get_styletextdecorationlinethrough/)() | يمثل خاصية 'style.textDecorationLineThrough'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationUnderline](./get_styletextdecorationunderline/)() | يمثل خاصية 'style.textDecorationUnderline'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectEmboss](./get_styletexteffectemboss/)() | يمثل خاصية 'style.textEffectEmboss'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectOutline](./get_styletexteffectoutline/)() | يمثل خاصية 'style.textEffectOutline'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextShadow](./get_styletextshadow/)() | يمثل خاصية 'style.textShadow'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextTransform](./get_styletexttransform/)() | يمثل خاصية 'style.textTransform'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleVisibility](./get_stylevisibility/)() | يمثل خاصية 'style.visibility'. |
| [System::String](../../system/string/) [get_Value](./get_value/)() override | قيمة الخاصية |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_XShear](./get_xshear/)() | يمثل خاصية 'xshear'. |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_YShear](./get_yshear/)() | يمثل خاصية 'yshear'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على بنية عداد المرجع المرتبط بالكائن. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | يحسب ويعيد رمز التجزئة بناءً على خاصية [BehaviorProperty::get_Value](./get_value/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [GetOrCreateByValue](./getorcreatebyvalue/)([System::String](../../system/string/)) | يبحث عن خاصية سلوك موجودة بالقيمة أو ينشئ واحدة مخصصة جديدة بالقيمة المحددة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. مشابه لاستدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بواسطة targetType. مشابه لمشغل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق بيان القفل C# lock(). استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه لطريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ الكائن. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | مُنشيء النسخ. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح نسخ الفئات الموروثة. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ شيئًا فعليًا، بل يهيئ كائنًا جديدًا ويتيح نسخ الفئات الموروثة. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن نوع القيمة بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة وnullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص خاص لـ [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يحدد القالب رقم n كإشارة ضعيفة (بدلاً من مشاركة). يسمح بتحويل المؤشرات في الحاويات إلى وضع ضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه لطريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بناء C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق بيان القفل C# lock() لإلغاء القفل. استدعِه مباشرة أو استخدم كائن الحارس [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. لا يجب استدعاؤه مباشرة؛ استخدم المؤشرات الذكية أو ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرّر جميع هياكل البيانات الداخلية. |
## انظر أيضًا

* فئة [IBehaviorProperty](../ibehaviorproperty/)
* مساحة الاسم [Aspose::Slides::Animation](../)
* مكتبة [Aspose.Slides](../../)