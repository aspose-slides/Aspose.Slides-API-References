---
title: Ink
second_title: Aspose.Slides for C++ API संदर्भ
description: एक स्लाइड पर इंक वस्तु का प्रतिनिधित्व करता है।
type: docs
weight: 53
url: /hi/aspose.slides.ink/ink/
---
## Ink क्लास

Represents an ink object on a slide.

```cpp
class Ink : public Aspose::Slides::GraphicalObject,
            public Aspose::Slides::Ink::IInk
```

## विधियाँ

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | एक आकार से संबद्ध वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | एक आकार से संबद्ध वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | [EffectFormat](../../aspose.slides/effectformat/) ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार के आकार जिनके पास इफ़ेक्ट प्रॉपर्टी नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) ऑब्जेक्ट लौटाता है जिसमें आकार की फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनके पास फ़िल प्रॉपर्टी नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | आकार की लॉकिंग स्थितियों को लौटाता है। केवल-पढ़ने योग्य [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)। |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | आकार की ऊँचाई प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[InkEffectType](../inkeffecttype/), [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\>\>\> [get_InkEffectImages](./get_inkeffectimages/)() | इंक ब्रश के विज़ुअल इफ़ेक्ट्स को सिम्युलेट करने के लिए उपयोग की जाने कस्टम इमेजेज़ का संग्रह प्राप्त करता है। ये इमेजेज़ विशिष्ट [InkEffectType](../inkeffecttype/) मानों जैसे Galaxy, Rainbow आदि के साथ इंक रेंडर करते समय उपयोग की जाती हैं। अपनी स्वयं की इमेजेज़ प्रदान करके आप प्रत्येक इंक इफ़ेक्ट के दिखने को नियंत्रित कर सकते हैं। |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) ऑब्जेक्ट लौटाता है जिसमें आकार की लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: कुछ प्रकार के आकार जिनके पास लाइन प्रॉपर्टीज़ नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | एक आकार का नाम लौटाता है। यह null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को भरोसेमंद रूप से संदर्भित करने की अनुमति देता है। केवल-पढ़ने योग्य **uint32_t**। तथा देखें [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../../aspose.slides/groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | आकार फ्रेम की कच्ची प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | निर्दिष्ट आकार के z-अक्ष के आसपास घूमें हुए डिग्री का मान लौटाता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान उल्टे दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | आकार की लॉकिंग स्थितियों को लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | एक आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) ऑब्जेक्ट लौटाता है जिसमें आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनके पास 3D प्रॉपर्टीज़ नहीं होती, उनके लिए null लौटाया जा सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/)। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() override | [IInk](../iink/) तत्व [IInkTrace](../iinktrace/) में सम्मिलित सभी ट्रेसेज़ प्राप्त करता है। केवल-पढ़ने योग्य। |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत है। चूँकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। तथा देखें [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | आकार की चौड़ाई प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने की x-निर्देशांक प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने की y-निर्देशांक प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | z-ऑर्डर में एक आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] z-ऑर्डर के आगे का आकार लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से प्राप्त आकार जिससे वर्तमान आकार विरासत में लेता है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | आकार के रेंडर किए गये कंटेंट से गणना किए गए विज़ुअल बाउंड्स को प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकार से संबद्ध वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकार से संबद्ध वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि आकार काली-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | आकार की ऊँचाई सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है पढ़ें/लिखें **bool**। |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | एक आकार का नाम सेट करता है। यह null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग का उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | आकार फ्रेम की कच्ची प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | निर्दिष्ट आकार के z-अक्ष के चारों ओर घुमा किये गये डिग्री की संख्या सेट करता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान उल्टी दिशा में घुमाव दर्शाता है। लिखें **float**। |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | आकार की चौड़ाई सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने की x-निर्देशांक सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने की y-निर्देशांक सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्युमेंट को weak पोइंटर (shared के बजाय) सेट करता है। कंटेनरों में पोइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पोइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पोइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पोइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पोइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject/)
* क्लास [IInk](../iink/)
* नेमस्पेस [Aspose::Slides::Ink](../)
* लाइब्रेरी [Aspose.Slides](../../)