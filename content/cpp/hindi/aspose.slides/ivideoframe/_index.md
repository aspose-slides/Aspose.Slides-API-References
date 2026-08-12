---
title: IVideoFrame
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्लाइड पर वीडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 4226
url: /hi/aspose.slides/ivideoframe/
---
## IVideoFrame क्लास

स्लाइड पर एक वीडियो क्लिप को दर्शाता है।

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट एक में सेट करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | आकृति के तत्वों की एरे बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | निर्दिष्ट इंडेक्स पर आकृति के समायोजन मान को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | आकृति के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | आकृति से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | आकृति से जुड़े वैकल्पिक पाठ के शीर्षक को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | यह प्रॉपर्टी निर्धारित करती है कि आकृति काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | ऑडियो फ्रेम से जुड़े बंद कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल पढ़ने योग्य है और सभी कैप्शन ट्रैक्स को शामिल करने वाला एक [ICaptionsCollection](../icaptionscollection/) लौटाती है। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | आकृति पर कनेक्शन साइट्स की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | आकृति के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है जिसमें आकृति पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | एम्बेडेड वीडियो ऑब्जेक्ट लौटाता है। पढ़ें [IVideo](../ivideo/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है जिसमें आकृति के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया जाता है। पढ़ें **bool**। |
| virtual **float** [get_Height](../ishape/get_height/)() | आकृति की ऊँचाई को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि क्या आकृति छिपी है। पढ़ें **bool**। |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | निर्धारित करता है कि क्या [VideoFrame](../videoframe/) छिपा है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक मैनेजर केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' विकल्प को पढ़ें/लिखें के रूप में प्राप्त करता है **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि क्या आकृति समूहित है। केवल पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि क्या आकृति TextHolder है। केवल पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | एक वीडियो फ़ाइल का नाम लौटाता है जो एक [VideoFrame](../videoframe/) से लिंक है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | आकृति का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | आकृति के जीवनकाल के दौरान स्थिर रहने वाला एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जिससे PowerPoint या इंटरऑप कोड दस्तावेज़ में कहीं से भी आकृति को विश्वसनीय रूप से संदर्भित कर सके। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि आकृति समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | पिक्चर फ्रेम के लिए [PictureFillFormat](../picturefillformat/) ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | [PictureFrame](../pictureframe/) के लॉक को लौटाता है। केवल पढ़ने योग्य [IPictureFrameLock](../ipictureframelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | आकृति के लिए प्लेसहोल्डर लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | निर्धारित करता है कि क्या वीडियो लूप में चल रहा है। पढ़ें **bool**। |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | वीडियो प्ले मोड लौटाता है। पढ़ें [VideoPlayModePreset](../videoplaymodepreset/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | रॉ shape फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 का मतलब 100% है। पढ़ें **float**। |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 का मतलब 100% है। पढ़ें **float**। |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | निर्धारित करता है कि क्या वीडियो प्ले समाप्त होते ही स्वचालित रूप से शुरू में रीवाइंड हो जाता है। पढ़ें **bool**। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घूर्णन के डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | आकृति के लॉक को लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | आकृति की शैली ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | जियोमेट्री प्रीसेट प्रकार लौटाता है। नोट: मान बदलने पर सभी समायोजन मान अपने डिफ़ॉल्ट मूल्यों पर रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../shapetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड वापस देता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जिसमें आकृति के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | ट्रिम अंत [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | ट्रिम शुरू [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। चूंकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | ऑडियो वॉल्यूम लौटाता है। पढ़ें [AudioVolumeMode](../audiovolumemode/)। |
| virtual **float** [get_Width](../ishape/get_width/)() | आकृति की चौड़ाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | आकृति के ऊपर-बाएं कोने के x-निर्देशांक को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | आकृति के ऊपर-बाएं कोने के y-निर्देशांक को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-ऑर्डर में आकृति की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के सामने की आकृति लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बेसिक प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से मिलने वाली आकृति जिससे वर्तमान आकृति विरासत में मिली है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | जियोमेट्री आकृति के पाथ की कॉपी लौटाता है। निर्देशांक आकृति के बाएं ऊपर कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकृति थंबनेल बॉउंड्स प्रकार उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनींग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | आकृति से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | आकृति से जुड़े वैकल्पिक पाठ के शीर्षक को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | प्रॉपर्टी निर्धारित करती है कि आकृति काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | एम्बेडेड वीडियो ऑब्जेक्ट सेट करता है। लिखें [IVideo](../ivideo/)। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | निर्धारित करता है कि क्या वीडियो फुल-स्क्रीन मोड में दिखाया जाता है। लिखें **bool**। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | आकृति की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि क्या आकृति छिपी है। लिखें **bool**। |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | निर्धारित करता है कि क्या [VideoFrame](../videoframe/) छिपा है। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' विकल्प सेट करता है पढ़ें/लिखें **bool**। |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | एक वीडियो फ़ाइल का नाम सेट करता है जो एक [VideoFrame](../videoframe/) से लिंक है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | आकृति का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | निर्धारित करता है कि क्या वीडियो लूप में है। लिखें **bool**। |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | वीडियो प्ले मोड सेट करता है। लिखें [VideoPlayModePreset](../videoplaymodepreset/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | रॉ shape फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 का मतलब 100% है। लिखें **float**। |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 का मतलब 100% है। लिखें **float**। |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | निर्धारित करता है कि क्या वीडियो प्ले समाप्त होते ही स्वचालित रूप से शुरू में रीवाइंड हो जाता है। लिखें **bool**। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घूर्णन के डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | जियोमेट्री प्रीसेट प्रकार सेट करता है। नोट: मान बदलने पर सभी समायोजन मान अपने डिफ़ॉल्ट मूल्यों पर रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../shapetype/)। |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | ट्रिम अंत [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | ट्रिम शुरू [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | ऑडियो वॉल्यूम सेट करता है। लिखें [AudioVolumeMode](../audiovolumemode/)। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | आकृति की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | आकृति के ऊपर-बाएं कोने के x-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | आकृति के ऊपर-बाएं कोने के y-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से आकृति जियोमेट्री अपडेट करता है। निर्देशांक आकृति के बाएं ऊपर कोने के सापेक्ष होने चाहिए। आकृति के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) की एरे से आकृति जियोमेट्री अपडेट करता है। निर्देशांक आकृति के बाएं ऊपर कोने के सापेक्ष होने चाहिए। आकृति के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को एकWeak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए गए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए गए रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए गए रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IPictureFrame](../ipictureframe/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)