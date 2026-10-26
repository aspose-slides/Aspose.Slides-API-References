---
title: AudioFrame
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्लाइड पर एक ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 53
url: /hi/aspose.slides/audioframe/
---
## AudioFrame वर्ग

एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और निर्दिष्ट प्लेसहोल्डर की गुणधर्म सेट करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | शेप के तत्वों की एरे बनाता है और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर शेप के एडजस्टमेंट मान को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | शेप के एडजस्टमेंट मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक शेप से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक शेप से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | अंतिम ट्रैक इंडेक्स लौटाता है। पढ़ें **int32_t**। |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | अंतिम ट्रैक समय लौटाता है। पढ़ें **int32_t**। |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | प्रारम्भिक ट्रैक इंडेक्स लौटाता है। पढ़ें **int32_t**। |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | प्रारम्भिक ट्रैक समय लौटाता है। पढ़ें **int32_t**। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | ऑडियो फ्रेम से जुड़े क्लोज्ड कैप्शन का संग्रह प्राप्त करता है। यह प्रॉपर्टी केवल-पढ़ने योग्य है और सभी कैप्शन ट्रैक्स वाला [ICaptionsCollection](../icaptionscollection/) लौटाता है। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | शेप का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) ऑब्जेक्ट लौटाता है जो शेप पर लागू पिक्सेल इफ़ेक्ट्स रखता है। नोट: कुछ शेप्स जिनके पास इफ़ेक्ट प्रॉपर्टी नहीं है, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| **bool** [get_Embedded](./get_embedded/)() override | निर्धारित करता है कि क्या ध्वनि प्रस्तुति में एम्बेड की गई है। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | एम्बेडेड ऑडियो ऑब्जेक्ट लौटाता है। पढ़ें [IAudio](../iaudio/)। |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | मीडिया के प्रारम्भिक फ़ेड-इन की अवधि मिलिसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | मीडिया के समाप्ति फ़ेड-आउट की अवधि मिलिसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है जिसमें शेप के फ़िल फ़ॉर्मेटिंग प्रॉपर्टी होते हैं। नोट: कुछ शेप्स जिनके पास फ़िल प्रॉपर्टी नहीं है, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | शेप फ्रेम की प्रॉपर्टी लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Height](../shape/get_height/)() override | शेप की ऊँचाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि शेप छुपा हुआ है या नहीं। पढ़ें **bool**। |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | निर्धारित करता है कि [AudioFrame](./) छुपा हुआ है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | निर्धारित करता है कि [PictureFrame](../pictureframe/) Cameo ऑब्जेक्ट है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। रीड/राइट **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि शेप समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है जिसमें शेप के लाइन फ़ॉर्मेटिंग प्रॉपर्टी होते हैं। नोट: कुछ शेप्स जिनके पास लाइन प्रॉपर्टी नहीं है, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | एक ऑडियो फ़ाइल का नाम लौटाता है जो [AudioFrame](./) से लिंक्ड है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | शेप का नाम लौटाता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो शेप के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरॉप कोड को दस्तावेज़ में कहीं से भी शेप को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य **uint32_t**। देखें भी [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि शेप समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | पिक्चर फ्रेम के लिए [PictureFillFormat](../picturefillformat/) ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | शेप की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../ipictureframelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | शेप का प्लेसहोल्डर लौटाता है। यदि शेप के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच बज रहा है या नहीं। पढ़ें **bool**। |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | निर्धारित करता है कि ऑडियो लूपेड है या नहीं। पढ़ें **bool**। |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | ऑडियो प्ले मोड लौटाता है। पढ़ें [AudioPlayModePreset](../audioplaymodepreset/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे शेप फ्रेम की प्रॉपर्टी लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 का अर्थ 100% है। पढ़ें **float**। |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 का अर्थ 100% है। पढ़ें **float**। |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | निर्धारित करता है कि ऑडियो प्ले होने के बाद स्वचालित रूप से प्रारम्भ पर रीवाइंड हो जाए। पढ़ें **bool**। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट शेप का Z-अक्ष के चारों ओर घुमाव (डिग्री) लौटाता है। सकारात्मक मान संकेत देता है घड़ी की दिशा में घुमाव; नकारात्मक मान संकेत देता है विरोधी दिशा में घुमाव। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | शेप की लॉकिंग जानकारी लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | शेप के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | शेप के पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | एक शेप के 3D इफ़ेक्ट प्रॉपर्टीज़ वाला [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है। ध्यान दें: कुछ शेप्स जिनके पास 3D प्रॉपर्टीज़ नहीं है, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | प्लेबैक के दौरान मीडिया के अंत से हटाए जाने वाले समय को मिलिसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | प्लेबैक के दौरान मीडिया की शुरुआत से हटाए जाने वाले समय को मिलिसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें भी [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | ऑडियो वॉल्यूम लौटाता है। पढ़ें [AudioVolumeMode](../audiovolumemode/)। |
| **float** [get_VolumeValue](./get_volumevalue/)() override | ऑडियो वॉल्यूम प्रतिशत में लौटाता है। पढ़ें **float**। |
| **float** [get_Width](../shape/get_width/)() override | शेप की चौड़ाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | शेप के ऊपरी-बाएँ शीर्ष बिंदु का X-कोऑर्डिनेट, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | शेप के ऊपरी-बाएँ शीर्ष बिंदु का Y-कोऑर्डिनेट, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Z-ऑर्डर में शेप की स्थिति लौटाता है। Shapes[0] Z-ऑर्डर के पीछे वाला शेप लौटाता है, और Shapes[Shapes.Count - 1] Z-ऑर्डर के आगे वाला शेप लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से शेप जिससे वर्तमान शेप विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ज्योमेट्री शेप के पथ की कॉपी लौटाता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | शेप थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) डिफ़ॉल्ट रूप से शेप थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | शेप थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | शेप की दृश्य सीमाएँ प्राप्त करता है जो उसके रेंडर किए गये कंटेंट से गणना की गई हैं। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य-टाइप द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत संस्करण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत संस्करण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | निर्धारित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | शेप से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | शेप से जुड़े वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | अंतिम ट्रैक इंडेक्स सेट करता है। लिखें **int32_t**। |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | अंतिम ट्रैक समय सेट करता है। लिखें **int32_t**। |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | प्रारम्भिक ट्रैक इंडेक्स सेट करता है। लिखें **int32_t**। |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | प्रारम्भिक ट्रैक समय सेट करता है। लिखें **int32_t**। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | एम्बेडेड ऑडियो ऑब्जेक्ट सेट करता है। लिखें [IAudio](../iaudio/)। |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | मीडिया के प्रारम्भिक फ़ेड-इन की अवधि मिलिसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | मीडिया के समाप्ति फ़ेड-आउट की अवधि मिलिसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | शेप फ्रेम की प्रॉपर्टी सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | शेप की ऊँचाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि शेप छुपा हुआ है या नहीं। लिखें **bool**। |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | निर्धारित करता है कि [AudioFrame](./) छुपा हुआ है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। रीड/राइट **bool**। |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | एक ऑडियो फ़ाइल का नाम सेट करता है जो [AudioFrame](./) से लिंक्ड है। लिखें [System::String](../../system/string/)। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | शेप का नाम सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच बज रहा है या नहीं। लिखें **bool**। |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | निर्धारित करता है कि ऑडियो लूपेड है या नहीं। लिखें **bool**। |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | ऑडियो प्ले मोड सेट करता है। लिखें [AudioPlayModePreset](../audioplaymodepreset/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे शेप फ्रेम की प्रॉपर्टी सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 का अर्थ 100% है। लिखें **float**। |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 का अर्थ 100% है। लिखें **float**। |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | निर्धारित करता है कि ऑडियो प्ले होने के बाद स्वचालित रूप से प्रारम्भ पर रीवाइंड हो जाए। लिखें **bool**। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट शेप का Z-अक्ष के चारों ओर घुमाव (डिग्री) सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरोधी दिशा में घुमाव दर्शाता है। लिखें **float**। |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | प्लेबैक के दौरान मीडिया के अंत से हटाने वाले समय को मिलिसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | प्लेबैक के दौरान मीडिया की शुरुआत से हटाने वाले समय को मिलिसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | ऑडियो वॉल्यूम सेट करता है। लिखें [AudioVolumeMode](../audiovolumemode/)। |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | ऑडियो वॉल्यूम प्रतिशत में सेट करता है। लिखें **float**। |
| void [set_Width](../shape/set_width/)(**float**) override | शेप की चौड़ाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | शेप के ऊपरी-बाएँ शीर्ष बिंदु का X-कोऑर्डिनेट, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | शेप के ऊपरी-बाएँ शीर्ष बिंदु का Y-कोऑर्डिनेट, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | शेप जियोमेट्री को [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से अपडेट करता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | शेप जियोमेट्री को [IGeometryPath](../igeometrypath/) की एरे से अपडेट करता है। निर्देशांक शेप के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

निम्नलिखित उदाहरण दिखाते हैं कि कैसे [Audio](../audio/) प्ले विकल्प बदलें।

```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## देखें

* वर्ग [PictureFrame](../pictureframe/)
* वर्ग [IAudioFrame](../iaudioframe/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)