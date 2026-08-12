---
title: VideoFrame
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 5552
url: /hi/aspose.slides/videoframe/
---
## VideoFrame वर्ग

स्लाइड पर एक वीडियो क्लिप का प्रतिनिधित्व करता है।

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | आकार के तत्वों की एरे बनाता है और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर आकार के समायोजन मान को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | आकार से जुड़े वैकल्पिक टेक्स्ट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | आकार से जुड़े वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | वीडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक्स वाले एक [ICaptionsCollection](../icaptionscollection/) को लौटाता है। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | एम्बेडेड वीडियो ऑब्जेक्ट को लौटाता है। पढ़ें [IVideo](../ivideo/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है जिसमें आकार के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें फ़िल प्रॉपर्टीज़ नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | निर्धारित करता है कि वीडियो पूरी स्क्रीन मोड में दिखाया जाता है या नहीं। पढ़ें **bool**। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें **bool**। |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | निर्धारित करता है कि एक [VideoFrame](./) छिपा हुआ है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर को लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | निर्धारित करता है कि [PictureFrame](../pictureframe/) कैमियो ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें लाइन प्रॉपर्टीज़ नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | वह वीडियो फ़ाइल का नाम लौटाता है जो एक [VideoFrame](./) से लिंक्ड है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | एक आकार का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यकता होने पर ख़ाली स्ट्रिंग मान का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है जो आकार के जीवनकाल में स्थायी रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं भी आकार को विश्वसनीय रूप से रेफ़रेंस करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | एक पिक्चर फ्रेम के लिए [PictureFillFormat](../picturefillformat/) ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../ipictureframelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकार के प्लेसहोल्डर को लौटाता है। यदि आकार का प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | निर्धारित करता है कि वीडियो लूप किया गया है या नहीं। पढ़ें **bool**। |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | वीडियो प्ले मोड लौटाता है। पढ़ें [VideoPlayModePreset](../videoplaymodepreset/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रेज़ेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 100% के बराबर है। पढ़ें **float**। |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 100% के बराबर है। पढ़ें **float**। |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | निर्धारित करता है कि मूवी समाप्त होते ही वीडियो स्वचालित रूप से शुरू में रीवाइंड हो जाता है या नहीं। पढ़ें **bool**। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमाने के डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान उलटी दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | आकार की स्टाइल ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जिसमें आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें 3D प्रॉपर्टीज़ नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | अंत ट्रिम [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | शुरू ट्रिम [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड आइडेंटिफायर लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा बदल सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | ऑडियो वॉल्यूम लौटाता है। पढ़ें [AudioVolumeMode](../audiovolumemode/)। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी बाएँ कोने का x-कोऑर्डिनेट पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी बाएँ कोने का y-कोऑर्डिनेट पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] पीछे वाले आकार को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले आकार को लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ज्यामिति आकार का पाथ कॉपी लौटाता है। कॉर्डिनेट्स आकार के बाएँ ऊपर कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर्ड कंटेंट से गणना किए गए आकार की दृश्य सीमा प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्धारित करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | एम्बेडेड वीडियो ऑब्जेक्ट सेट करता है। लिखें [IVideo](../ivideo/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | निर्धारित करता है कि वीडियो पूरी स्क्रीन मोड में दिखाया जाता है या नहीं। लिखें **bool**। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। लिखें **bool**। |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | निर्धारित करता है कि [VideoFrame](./) छिपा हुआ है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | एक वीडियो फ़ाइल का नाम सेट करता है जो [VideoFrame](./) से लिंक्ड है। लिखें [System::String](../../system/string/)। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | निर्धारित करता है कि वीडियो लूप किया गया है या नहीं। लिखें **bool**। |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | वीडियो प्ले मोड सेट करता है। लिखें [VideoPlayModePreset](../videoplaymodepreset/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 100% के बराबर है। लिखें **float**। |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 100% के बराबर है। लिखें **float**। |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | निर्धारित करता है कि मूवी समाप्त होते ही वीडियो स्वचालित रूप से शुरू में रीवाइंड हो जाता है या नहीं। लिखें **bool**। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार को z-अक्ष के चारों ओर घुमाने के डिग्री सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान उल्टी दिशा में घुमाव दर्शाता है। लिखें **float**। |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | अंत ट्रिम करें [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | शुरू ट्रिम करें [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | ऑडियो वॉल्यूम सेट करता है। लिखें [AudioVolumeMode](../audiovolumemode/)। |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी बाएँ कोने का x-कोऑर्डिनेट पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी बाएँ कोने का y-कोऑर्डिनेट पॉइंट्स में सेट करता है। लिखें **float**। |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से आकार ज्योमेट्री अपडेट करता है। कॉर्डिनेट्स आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) की एरे से आकार ज्योमेट्री अपडेट करता है। कॉर्डिनेट्स आकार के बाएँ ऊपर कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector प्रयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector प्रयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सेव करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर मुक्त करता है। |

## अन्य देखें

* क्लास [PictureFrame](../pictureframe/)
* क्लास [IVideoFrame](../ivideoframe/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)