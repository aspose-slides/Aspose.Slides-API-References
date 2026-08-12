---
title: LegacyDiagram
second_title: C++ API संदर्भ के लिए Aspose.Slides
description: एक लेगेसी डायग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 4330
url: /hi/aspose.slides/legacydiagram/
---
## LegacyDiagram वर्ग

एक लेगेसी डायग्राम ऑब्जेक्ट का प्रतिनिधित्व करता है।

```cpp
class LegacyDiagram : public Aspose::Slides::GraphicalObject,
                      public Aspose::Slides::ILegacyDiagram
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर न हो तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [ConvertToGroupShape](./converttogroupshape/)() override | लेगेसी डायग्राम को संपादनीय समूह आकृति में बदलता है। बनाया गया [GroupShape](../groupshape/) ऑब्जेक्ट उसी स्थिति में पैरेंट समूह आकृति में जोड़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[SmartArt::ISmartArt](../../aspose.slides.smartart/ismartart/)\> [ConvertToSmartArt](./converttosmartart/)() override | लेगेसी डायग्राम को संपादनीय [SmartArt](../../aspose.slides.smartart/) ऑब्जेक्ट में बदलता है। बनाया गया [SmartArt](../../aspose.slides.smartart/) ऑब्जेक्ट उसी स्थिति में पैरेंट समूह आकृति में जोड़ता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक आकृति से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक आकृति से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी यह निर्दिष्ट करती है कि एक आकृति काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकृति का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकृति पर लागू पिक्सेल इफ़ेक्ट्स युक्त [EffectFormat](../effectformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ आकृति प्रकारों के लिए जो इफ़ेक्ट प्रॉपर्टीज़ नहीं रखते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकृति के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ युक्त [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ आकृति प्रकारों के लिए जिनमें फ़िल प्रॉपर्टीज़ नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | आकृति के लॉक लौटाता है। केवल-पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकृति की ऊँचाई (पॉइंट में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकृति छुपी है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘डेकोरेटिव के रूप में मार्क करें’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकृति समूहबद्ध है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकृति के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ युक्त [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ आकृति प्रकारों के लिए जिनमें लाइन प्रॉपर्टी नहीं है, null लौटाया जा सकता है। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकृति का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनभर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकृति को भरोसेमंद तरीके से रेफ़रेंस करने देता है। केवल-पढ़ने योग्य **uint32_t**। और देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकृति समूहबद्ध है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | एक आकृति के लिए प्लेसहोल्डर लौटाता है। यदि आकृति के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | रॉ आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घूर्णित डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घूर्णन दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकृति के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | एक आकृति की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकृति के 3D इफ़ेक्ट प्रॉपर्टीज़ युक्त [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ आकृति प्रकारों के लिए जिनमें 3D प्रॉपर्टीज़ नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाना है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्रामेटिक रूप से पुनः सौंपा जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। और देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | आकृति की चौड़ाई (पॉइंट में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकृति के ऊपरी-बाएँ कोने का x-निर्देशांक (पॉइंट में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकृति के ऊपरी-बाएँ कोने का y-निर्देशांक (पॉइंट में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | आकृति की z-ऑर्डर में स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] आगे की आकृति लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से निकाली गई आकृति जिससे वर्तमान आकृति विरासत में मिली है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समरूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकृति थंबनेल बाउंड्स टाइप का उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समरूप। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर की गई सामग्री से गणना किए गए आकृति के विजुअल बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समरूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू प्रकार ऑब्जेक्ट के साथ nullptr की। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | निर्धारित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकृति से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकृति से जुड़े वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी यह निर्धारित करती है कि एक आकृति काली-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकृति की ऊँचाई (पॉइंट में मापी गई) सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकृति छुपी है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘डेकोरेटिव के रूप में मार्क करें’ विकल्प सेट करता है। लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकृति का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | रॉ आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घूर्णित डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान घड़ी की विपरीत दिशा में घूर्णन दर्शाता है। लिखें **float**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकृति की चौड़ाई (पॉइंट में मापी गई) सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकृति के ऊपरी-बाएँ कोने का x-निर्देशांक (पॉइंट में मापी गई) सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकृति के ऊपरी-बाएँ कोने का y-निर्देशांक (पॉइंट में मापी गई) सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्युमेंट को शैर्ड की बजाय वीक पॉइंटर सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सैंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फाइल के रूप में सेव करता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फाइल के रूप में सेव करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## संबंधित देखें

* क्लास [GraphicalObject](../graphicalobject/)
* क्लास [ILegacyDiagram](../ilegacydiagram/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)