---
title: IAudioFrame
second_title: C++ के लिए Aspose.Slides एपीआई संदर्भ
description: एक स्लाइड पर ऑडियो क्लिप का प्रतिनिधित्व करता है।
type: docs
weight: 1353
url: /hi/aspose.slides/iaudioframe/
---
## IAudioFrame क्लास

Represents an audio clip on a slide.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट प्लेसहोल्डर पर सेट करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | शेप के तत्वों का सरणी बनाता है और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | निश्चित इंडेक्स पर शैप के समायोजन मान को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | शैप के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | शैप से जुड़ा वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | शैप से जुड़े वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | अंतिम ट्रैक इंडेक्स लौटाता है। पढ़ें **int32_t**। |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | अंतिम ट्रैक समय लौटाता है। पढ़ें **int32_t**। |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | प्रारंभ ट्रैक इंडेक्स लौटाता है। पढ़ें **int32_t**। |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | प्रारंभ ट्रैक समय लौटाता है। पढ़ें **int32_t**। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | गुणधर्म निर्धारित करता है कि शैप काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | ऑडियो फ्रेम से जुड़े क्लोज़्ड कैप्शन संग्रह को प्राप्त करता है। यह गुणधर्म केवल-पढ़ने योग्य है और एक [ICaptionsCollection](../icaptionscollection/) लौटाता है जिसमें सभी कैप्शन ट्रैक्स होते हैं। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | शैप पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | शैप का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | एक [EffectFormat](../effectformat/) वस्तु लौटाता है जिसमें शैप पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual **bool** [get_Embedded](./get_embedded/)() | निर्धारित करता है कि क्या एक साउंड प्रस्तुति में एम्बेडेड है। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | एम्बेडेड ऑडियो ऑब्जेक्ट लौटाता है। पढ़ें [IAudio](../iaudio/)। |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | मीडिया के प्रारंभिक फेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | मीडिया के अंतिम फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | एक [FillFormat](../fillformat/) वस्तु लौटाता है जिसमें शैप के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | शैप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | शैप की ऊँचाई, पॉइंट्स में मापी, प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि शैप छिपा हुआ है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | निर्धारित करता है कि एक [AudioFrame](../audioframe/) छिपा हुआ है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि शैप ग्रुप्ड है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि शैप TextHolder है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | एक [LineFormat](../lineformat/) वस्तु लौटाता है जिसमें शैप के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | एक ऑडियो फ़ाइल का नाम लौटाता है जो एक [AudioFrame](../audioframe/) से जुड़ा है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | शैप का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो शैप के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शैप को भरोसेमंद रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि शैप ग्रुप्ड है तो पैरेंट [GroupShape](../groupshape/) वस्तु लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | एक पिक्चर फ्रेम के लिए [PictureFillFormat](../picturefillformat/) वस्तु लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | [PictureFrame](../pictureframe/) के लॉक लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../ipictureframelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | शैप के लिए प्लेसहोल्डर लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | निर्धारित करता है कि ऑडियो लूप में है या नहीं। पढ़ें **bool**। |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | ऑडियो प्ले मोड लौटाता है। पढ़ें [AudioPlayModePreset](../audioplaymodepreset/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | रॉ शैप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 100% के बराबर है। पढ़ें **float**। |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 100% के बराबर है। पढ़ें **float**। |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड हो जाता है या नहीं। पढ़ें **bool**। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्धारित शैप के z-axis के चारों ओर घुमाव के डिग्री की संख्या लौटाता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | शैप के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | शैप के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | ज्योमेट्री प्रीसेट प्रकार लौटाता है। नोट: मान बदलने पर सभी समायोजन मान अपनी डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../shapetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | एक [ThreeDFormat](../threedformat/) वस्तु लौटाता है जिसमें शैप के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | प्लेबैक के दौरान मीडिया के अंत से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | प्लेबैक के दौरान मीडिया के प्रारंभ से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। पढ़ें **float**। |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एक आंतरिक, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जा सकता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | ऑडियो वॉल्यूम लौटाता है। पढ़ें [AudioVolumeMode](../audiovolumemode/)। |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | ऑडियो वॉल्यूम प्रतिशत में लौटाता है। पढ़ें **float**। |
| virtual **float** [get_Width](../ishape/get_width/)() | शैप की चौड़ाई, पॉइंट्स में मापी, प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | शैप के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में मापता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | शैप के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में मापता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-order में शैप की स्थिति लौटाता है। Shapes[0] बैक में शैप लौटाता है, और Shapes[Shapes.Count - 1] फ्रंट में शैप लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बुनियादी प्लेसहोल्डर शैप लौटाता है (लेआउट और/या मास्टर स्लाइड से शैप जो वर्तमान शैप से विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | ज्योमेट्री शैप के पाथ की प्रतिलिपि लौटाता है। कॉर्डिनेट्स शैप के बाएँ-ऊपर कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | शैप थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) शैप थंबनेल बाउंड्स टाइप डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | शैप थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# ‘is’ ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने का कार्य करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर शुरू करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-कम्पेयर वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | निर्धारित करता है कि यह शैप प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | शैप से जुड़ा वैकल्पिक टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | शैप से जुड़े वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | अंतिम ट्रैक इंडेक्स सेट करता है। लिखें **int32_t**। |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | अंतिम ट्रैक समय सेट करता है। लिखें **int32_t**। |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | प्रारंभ ट्रैक इंडेक्स सेट करता है। लिखें **int32_t**। |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | प्रारंभ ट्रैक समय सेट करता है। लिखें **int32_t**। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | गुणधर्म निर्धारित करता है कि शैप काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | एम्बेडेड ऑडियो ऑब्जेक्ट सेट करता है। लिखें [IAudio](../iaudio/)। |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | मीडिया के प्रारंभिक फेड-इन की अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | मीडिया के अंतिम फेड-आउट की अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | शैप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | शैप की ऊँचाई, पॉइंट्स में मापी, सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि शैप छिपा हुआ है या नहीं। लिखें **bool**। |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | निर्धारित करता है कि एक [AudioFrame](../audioframe/) छिपा हुआ है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | एक ऑडियो फ़ाइल का नाम सेट करता है जो एक [AudioFrame](../audioframe/) से जुड़ी है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | शैप का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | निर्धारित करता है कि ऑडियो स्लाइड्स के बीच चल रहा है या नहीं। लिखें **bool**। |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | निर्धारित करता है कि ऑडियो लूप में है या नहीं। लिखें **bool**। |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | ऑडियो प्ले मोड सेट करता है। लिखें [AudioPlayModePreset](../audioplaymodepreset/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | रॉ शैप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | पिक्चर फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 100% के बराबर है। लिखें **float**। |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | पिक्चर फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 100% के बराबर है। लिखें **float**। |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | निर्धारित करता है कि प्ले होने के बाद ऑडियो स्वचालित रूप से शुरू में रिवाइंड हो जाता है या नहीं। लिखें **bool**। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | शैप को z-axis के चारों ओर घुमाव के डिग्री सेट करता है। धनात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; ऋणात्मक मान प्रतिक्लॉकवाइज़ घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ज्योमेट्री प्रीसेट प्रकार सेट करता है। नोट: मान बदलने पर सभी समायोजन मान अपनी डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../shapetype/)। |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | प्लेबैक के दौरान मीडिया के अंत से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | प्लेबैक के दौरान मीडिया के प्रारंभ से हटाने के समय अवधि को मिलीसेकंड में निर्दिष्ट करता है। लिखें **float**। |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | ऑडियो वॉल्यूम सेट करता है। लिखें [AudioVolumeMode](../audiovolumemode/)। |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | ऑडियो वॉल्यूम प्रतिशत में सेट करता है। लिखें **float**। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | शैप की चौड़ाई, पॉइंट्स में मापी, सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | शैप के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | शैप के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | शैप ज्योमेट्री को [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से अपडेट करता है। कॉर्डिनेट्स शैप के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। शैप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | शैप ज्योमेट्री को [IGeometryPath](../igeometrypath/) की एरे से अपडेट करता है। कॉर्डिनेट्स शैप के बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। शैप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्गुमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। क़ंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर फ्री करता है। |
## देखें

* क्लास [IPictureFrame](../ipictureframe/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)