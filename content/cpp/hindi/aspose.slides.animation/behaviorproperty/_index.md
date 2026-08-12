---
title: BehaviorProperty
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एनिमेशन व्यवहार के लिए प्रॉपर्टी प्रकारों का प्रतिनिधित्व करता है। प्रॉपर्टीज़ की सूची का अनुसरण करता है  और।
type: docs
weight: 53
url: /hi/aspose.slides.animation/behaviorproperty/
---
## BehaviorProperty क्लास


Represent property types for animation behavior. [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) और [https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/documentformat.openxml.presentation.attributename(v=office.15).aspx) से गुणों की सूची का अनुसरण करता है।

```cpp
class BehaviorProperty : public Aspose::Slides::Animation::IBehaviorProperty
```

## विधियाँ

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | जाँचता है कि यह ऑब्जेक्ट किसी अन्य के बराबर है या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionAutoRotationCenter](./get_extrusionautorotationcenter/)() | 'extrusion.autorotationcenter' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionBackDepth](./get_extrusionbackdepth/)() | 'extrusion.backdepth' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColor](./get_extrusioncolor/)() | 'extrusion.color' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionColorMode](./get_extrusioncolormode/)() | 'extrusion.colormode' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionForeDepth](./get_extrusionforedepth/)() | 'extrusion.foredepth' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionLockRotationCenter](./get_extrusionlockrotationcenter/)() | 'extrusion.lockrotationcenter' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOn](./get_extrusionon/)() | 'extrusion.on' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationAngle](./get_extrusionorientationangle/)() | 'extrusion.orientationangle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationX](./get_extrusionorientationx/)() | 'extrusion.orientation.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationY](./get_extrusionorientationy/)() | 'extrusion.orientation.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionOrientationZ](./get_extrusionorientationz/)() | 'extrusion.orientation.z' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionPlane](./get_extrusionplane/)() | 'extrusion.plane' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRender](./get_extrusionrender/)() | 'extrusion.render' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleX](./get_extrusionrotationanglex/)() | 'extrusion.rotationangle.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationAngleY](./get_extrusionrotationangley/)() | 'extrusion.rotationangle.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterX](./get_extrusionrotationcenterx/)() | 'extrusion.rotationcenter.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterY](./get_extrusionrotationcentery/)() | 'extrusion.rotationcenter.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionRotationCenterZ](./get_extrusionrotationcenterz/)() | 'extrusion.rotationcenter.z' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAmt](./get_extrusionskewamt/)() | 'extrusion.skewamt' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionSkewAngle](./get_extrusionskewangle/)() | 'extrusion.skewangle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionType](./get_extrusiontype/)() | 'extrusion.type' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginX](./get_extrusionviewpointoriginx/)() | 'extrusion.viewpointorigin.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointOriginY](./get_extrusionviewpointoriginy/)() | 'extrusion.viewpointorigin.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointX](./get_extrusionviewpointx/)() | 'extrusion.viewpoint.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointY](./get_extrusionviewpointy/)() | 'extrusion.viewpoint.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ExtrusionViewPointZ](./get_extrusionviewpointz/)() | 'extrusion.viewpoint.z' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Fill_Color](./get_fill_color/)() | 'fill.color' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillAngle](./get_fillangle/)() | 'fill.angle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor](./get_fillcolor/)() | 'fillcolor' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillColor2](./get_fillcolor2/)() | 'fill.color2' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocus](./get_fillfocus/)() | 'fill.focus' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionX](./get_fillfocuspositionx/)() | 'fill.focusposition.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusPositionY](./get_fillfocuspositiony/)() | 'fill.focusposition.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeX](./get_fillfocussizex/)() | 'fill.focussize.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillFocusSizeY](./get_fillfocussizey/)() | 'fill.focussize.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillMethod](./get_fillmethod/)() | 'fill.method' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOn](./get_fillon/)() | 'fill.on' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity](./get_fillopacity/)() | 'fill.opacity' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillOpacity2](./get_fillopacity2/)() | 'fill.opacity2' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_FillType](./get_filltype/)() | 'fill.type' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_Image](./get_image/)() | 'image' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataBlacklevel](./get_imagedatablacklevel/)() | 'imageData.blacklevel' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataChromakey](./get_imagedatachromakey/)() | 'imageData.chromakey' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropBottom](./get_imagedatacropbottom/)() | 'imageData.cropBottom' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropLeft](./get_imagedatacropleft/)() | 'imageData.cropLeft' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropRight](./get_imagedatacropright/)() | 'imageData.cropRight' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataCropTop](./get_imagedatacroptop/)() | 'imageData.cropTop' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGain](./get_imagedatagain/)() | 'imageData.gain' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGamma](./get_imagedatagamma/)() | 'imageData.gamma' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ImageDataGrayscale](./get_imagedatagrayscale/)() | 'imageData.grayscale' प्रॉपर्टी को दर्शाता है |
| **bool** [get_IsCustom](./get_iscustom/)() override | बताता है कि यह प्रॉपर्टी विनिर्देश में निर्धारित प्रॉपर्टी सूची में नहीं आती है: [https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx](https://msdn.microsoft.com/en-us/library/dd949052(v=office.15).aspx) |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptC](./get_pptc/)() | 'ppt_c' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptH](./get_ppth/)() | 'ppt_h' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptR](./get_pptr/)() | 'ppt_r' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptW](./get_pptw/)() | 'ppt_w' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptX](./get_pptx/)() | 'ppt_x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_PptY](./get_ppty/)() | 'ppt_y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_R](./get_r/)() | 'r' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleX](./get_scalex/)() | 'ScaleX' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ScaleY](./get_scaley/)() | 'ScaleY' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor](./get_shadowcolor/)() | 'shadow.color' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowColor2](./get_shadowcolor2/)() | 'shadow.color2' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveX](./get_shadowmatrixperspectivex/)() | 'shadow.matrix.perspectiveX' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixPerspectiveY](./get_shadowmatrixperspectivey/)() | 'shadow.matrix.perspectiveY' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoX](./get_shadowmatrixxtox/)() | 'shadow.matrix.xtox' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixXtoY](./get_shadowmatrixxtoy/)() | 'shadow.matrix.xtoy' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoX](./get_shadowmatrixytox/)() | 'shadow.matrix.ytox' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowMatrixYtoY](./get_shadowmatrixytoy/)() | 'shadow.matrix.ytoy' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2X](./get_shadowoffset2x/)() | 'shadow.offset2.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffset2Y](./get_shadowoffset2y/)() | 'shadow.offset2.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetX](./get_shadowoffsetx/)() | 'shadow.offset.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOffsetY](./get_shadowoffsety/)() | 'shadow.offset.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOn](./get_shadowon/)() | 'shadow.on' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOpacity](./get_shadowopacity/)() | 'shadow.opacity' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginX](./get_shadoworiginx/)() | 'shadow.origin.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowOriginY](./get_shadoworiginy/)() | 'shadow.origin.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_ShadowType](./get_shadowtype/)() | 'shadow.type' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveX](./get_skewmatrixperspectivex/)() | 'skew.matrix.perspectiveX' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixPerspectiveY](./get_skewmatrixperspectivey/)() | 'skew.matrix.perspectiveY' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoX](./get_skewmatrixxtox/)() | 'skew.matrix.xtox' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixXtoY](./get_skewmatrixxtoy/)() | 'skew.matrix.xtoy' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoX](./get_skewmatrixytox/)() | 'skew.matrix.ytox' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewMatrixYtoY](./get_skewmatrixytoy/)() | 'skew.matrix.ytoy' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetX](./get_skewoffsetx/)() | 'skew.offset.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOffsetY](./get_skewoffsety/)() | 'skew.offset.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOn](./get_skewon/)() | 'skew.on' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginX](./get_skeworiginx/)() | 'skew.origin.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_SkewOriginY](./get_skeworiginy/)() | 'skew.origin.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor](./get_strokecolor/)() | 'stroke.color' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeColor2](./get_strokecolor2/)() | 'stroke.color2' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeDashStyle](./get_strokedashstyle/)() | 'stroke.dashstyle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrow](./get_strokeendarrow/)() | 'stroke.endArrow' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowLength](./get_strokeendarrowlength/)() | 'stroke.endArrowLength' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeEndArrowWidth](./get_strokeendarrowwidth/)() | 'stroke.endArrowWidth' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeFillType](./get_strokefilltype/)() | 'stroke.filltype' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeX](./get_strokeimagesizex/)() | 'stroke.imagesize.x' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeImageSizeY](./get_strokeimagesizey/)() | 'stroke.imagesize.y' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeLineStyle](./get_strokelinestyle/)() | 'stroke.linestyle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOn](./get_strokeon/)() | 'stroke.on' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeOpacity](./get_strokeopacity/)() | 'stroke.opacity' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeSrc](./get_strokesrc/)() | 'stroke.src' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrow](./get_strokestartarrow/)() | 'stroke.startArrow' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowLength](./get_strokestartarrowlength/)() | 'stroke.startArrowLength' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeStartArrowWidth](./get_strokestartarrowwidth/)() | 'stroke.startArrowWidth' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StrokeWeight](./get_strokeweight/)() | 'stroke.weight' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleColor](./get_stylecolor/)() | 'style.color' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontFamily](./get_stylefontfamily/)() | 'style.fontFamily' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontSize](./get_stylefontsize/)() | 'style.fontSize' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontStyle](./get_stylefontstyle/)() | 'style.fontStyle' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleFontWeight](./get_stylefontweight/)() | 'style.fontWeight' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleOpacity](./get_styleopacity/)() | 'style.opacity' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleRotation](./get_stylerotation/)() | 'style.rotation' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleSRotation](./get_stylesrotation/)() | 'style.sRotation' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationLineThrough](./get_styletextdecorationlinethrough/)() | 'style.textDecorationLineThrough' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextDecorationUnderline](./get_styletextdecorationunderline/)() | 'style.textDecorationUnderline' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectEmboss](./get_styletexteffectemboss/)() | 'style.textEffectEmboss' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextEffectOutline](./get_styletexteffectoutline/)() | 'style.textEffectOutline' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextShadow](./get_styletextshadow/)() | 'style.textShadow' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleTextTransform](./get_styletexttransform/)() | 'style.textTransform' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_StyleVisibility](./get_stylevisibility/)() | 'style.visibility' प्रॉपर्टी को दर्शाता है |
| [System::String](../../system/string/) [get_Value](./get_value/)() override | प्रॉपर्टी का मान |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_XShear](./get_xshear/)() | 'xshear' प्रॉपर्टी को दर्शाता है |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [get_YShear](./get_yshear/)() | 'yshear' प्रॉपर्टी को दर्शाता है |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | [BehaviorProperty::get_Value](./get_value/) प्रॉपर्टी के आधार पर हैश कोड की गणना करता है और लौटाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[BehaviorProperty](./)\> [GetOrCreateByValue](./getorcreatebyvalue/)([System::String](../../system/string/)) | मान द्वारा मौजूदा व्यवहार प्रॉपर्टी खोजता है या निर्दिष्ट मान के साथ नई कस्टम प्रॉपर्टी बनाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस को nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संदर्भ देखें

* क्लास [IBehaviorProperty](../ibehaviorproperty/)
* नामस्थान [Aspose::Slides::Animation](../)
* लाइब्रेरी [Aspose.Slides](../../)