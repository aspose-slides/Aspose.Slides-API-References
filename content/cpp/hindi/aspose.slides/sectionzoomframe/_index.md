---
title: SectionZoomFrame
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड में एक सेक्शन ज़ूम ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 5045
url: /hi/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame क्लास

एक स्लाइड में [Section](../section/) Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

```cpp
class SectionZoomFrame : public Aspose::Slides::ZoomObject,
                         public virtual Aspose::Slides::ISectionZoomFrame
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक आकार से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | यह प्रॉपर्टी निर्दिष्ट करती है कि एक आकार काले-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) ऑब्जेक्ट लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है जिसमें आकार की फ़िल फ़ॉर्मेटिंग प्रॉपर्टी होती है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें फ़िल प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | ज़ूम ऑब्जेक्ट की इमेज टाइप प्राप्त करता है। पढ़ें [ZoomImageType](../zoomimagetype/)। डिफ़ॉल्ट मान: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है जिसमें आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टी होती है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें लाइन प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | एक आकार का नाम लौटाता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है जो आकार के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से रेफ़रेंस करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पेरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पेरेंट प्रेज़ेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें **bool**। डिफ़ॉल्ट मान: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार ज़-अक्ष के आसपास कितनी डिग्री घुमा हुआ है, वह संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी के विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | यह मान प्राप्त करता है जो दर्शाता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें **bool**। डिफ़ॉल्ट मान: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | एक आकार की पेरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() override | [Section](../section/) ज़ूम ऑब्जेक्ट जिस सेक्शन ऑब्जेक्ट से लिंक करता है, उसे प्राप्त करता है। पढ़ें [ISection](../isection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जिसमें आकार की 3D इफ़ेक्ट प्रॉपर्टी होते हैं। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनमें 3D प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | ज़ूम और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। पढ़ें **float**। डिफ़ॉल्ट मान: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः सौंपा जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है। पढ़ें [IPPImage](../ippimage/)। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | ज़-ऑर्डर में एक आकार की पोजीशन लौटाता है। Shapes[0] ज़-ऑर्डर के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] ज़-ऑर्डर के अग्र भाग का आकार लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक मूल प्लेसहोल्डर आकार लौटाता है (लेआउट या मास्टर स्लाइड से आया वह आकार जिससे वर्तमान आकार विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए कंटेंट से गणना किए गए आकार की विज़ुअल बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामलों के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग मामलों के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकार से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकार से जुड़ा वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि एक आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छुपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | ज़ूम ऑब्जेक्ट की इमेज टाइप सेट करता है। लिखें [ZoomImageType](../zoomimagetype/)। डिफ़ॉल्ट मान: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | एक आकार का नाम सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | स्लाइडशो में नेविगेशन व्यवहार सेट करता है। लिखें **bool**। डिफ़ॉल्ट मान: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार ज़-अक्ष के आसपास कितनी डिग्री घुमा हुआ है, वह संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी के विपरीत दिशा में घूर्णन दर्शाता है। लिखें **float**। |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | यह मान सेट करता है जो दर्शाता है कि ज़ूम गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। लिखें **bool**। डिफ़ॉल्ट मान: true |
| void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | [Section](../section/) ज़ूम ऑब्जेक्ट जो सेक्शन ऑब्जेक्ट से लिंक करता है, उसे सेट करता है। लिखें [ISection](../isection/)। |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | ज़ूम और स्लाइड के बीच संक्रमण की अवधि सेट करता है। लिखें **float**। डिफ़ॉल्ट मान: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | ज़ूम ऑब्जेक्ट के लिए इमेज सेट करता है। लिखें [IPPImage](../ippimage/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-थे टेम्प्लेट आर्ग्युमेंट को साझा पॉइंटर के बजाय वीक पॉइंटर सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [ZoomObject](../zoomobject/)
* क्लास [ISectionZoomFrame](../isectionzoomframe/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)