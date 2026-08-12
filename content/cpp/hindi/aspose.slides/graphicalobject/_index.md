---
title: GraphicalObject
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 1171
url: /hi/aspose.slides/graphicalobject/
---
## GraphicalObject क्लास


अमूर्त ग्राफ़िकल ऑब्जेक्ट का प्रतिनिधित्व करता है।

```cpp
class GraphicalObject : public Aspose::Slides::Shape,
                        public virtual Aspose::Slides::IGraphicalObject
```

## विधियां

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | सिर्फ आंतरिक उपयोग के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | आकार से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | आकार से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकार पर लागू पिक्सेल इफ़ेक्ट्स वाला [EffectFormat](../effectformat/) ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट गुण नहीं होते, के लिए null लौट सकता है। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकार के लिए फाल फ़ॉर्मेटिंग गुणों वाला [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के आकार जिनमें फाइल गुण नहीं होते, के लिए null लौट सकता है। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() override | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकार के लिए लाइन फ़ॉर्मेटिंग गुणों वाला [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के आकार जिनमें लाइन गुण नहीं होते, के लिए null लौट सकता है। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकार का नाम लौटाता है। इसे null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के लिए स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार का भरोसेमंद संदर्भ देता है। केवल पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे आकार फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार का z-अक्ष के चारों ओर घुमा हुआ डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार के लॉक लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकार की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकार के 3D इफ़ेक्ट गुणों वाला [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है। नोट: कुछ प्रकार के आकार जिनमें 3D गुण नहीं होते, के लिए null लौट सकता है। केवल पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | इंटरनल, प्रेज़ेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग किया जा सकता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] सामने वाला आकार लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जो वर्तमान आकार से विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए कंटेंट से गणना किए गए आकार की विज़ुअल बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबकलासेस की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबकलासेस की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr से करती है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | आकार से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकार से जुड़ा वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। इसे null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग मान उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे आकार फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार का z-अक्ष के चारों ओर घुमा हुआ डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। लिखें **float**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्यूमेंट को विंड पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को विंड मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाकर लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | विंड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | विंड रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [Shape](../shape/)
* क्लास [IGraphicalObject](../igraphicalobject/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)