---
title: IGroupShape
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्लाइड पर आकारों के एक समूह का प्रतिनिधित्व करता है।
type: docs
weight: 2484
url: /hi/aspose.slides/igroupshape/
---
## IGroupShape क्लास


Represents a group of shapes on a slide.

```cpp
class IGroupShape : public virtual Aspose::Slides::IShape
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट एक पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | एक आकार से जुड़ा वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | एक आकार से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | प्रोपर्टी निर्धारित करती है कि आकार काला-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-रीड **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | आकार का कस्टम डेटा लौटाता है। केवल-रीड [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | एक [EffectFormat](../effectformat/) वस्तु लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। केवल-रीड [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | एक [FillFormat](../fillformat/) वस्तु लौटाता है जिसमें आकार के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-रीड [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() | आकार के लॉक लौटाता है। केवल-रीड [IGroupShapeLock](../igroupshapelock/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | आकार की ऊँचाई बिंदुओं में प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि आकार छुपा है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल-रीड [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-रीड **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि आकार TextHolder है या नहीं। केवल-रीड **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | एक [LineFormat](../lineformat/) वस्तु लौटाता है जिसमें आकार के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-रीड [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | एक आकार का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफ़ायर लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरेक्ट कोड को दस्तावेज़ के कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने की अनुमति देता है। केवल-रीड **uint32_t**। देखें भी [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](./)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) वस्तु लौटाता है। अन्यथा null लौटाता है। केवल-रीड [IGroupShape](./)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | आकार के लिए प्लेसहोल्डर लौटाता है। केवल-रीड [IPlaceholder](../iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रस्तुति लौटाता है। केवल-रीड [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट आकार z-धुरी के चारों ओर घुमाए जाने वाले डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | निर्दिष्ट इंडेक्स पर समूह में आकार लौटाता है। केवल-रीड [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | आकार के लॉक लौटाता है। केवल-रीड [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | समूह के भीतर आकारों का संग्रह लौटाता है। केवल-रीड [IShapeCollection](../ishapecollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-रीड [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | एक [ThreeDFormat](../threedformat/) वस्तु लौटाता है जिसमें आकार के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-रीड [IThreeDFormat](../ithreedformat/)। |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एक इंटर्नल, प्रस्तुति-स्कोप्ड आइडेंटिफ़ायर लौटाता है जिसे ऐड-इन्स या अन्य कोड द्वारा उपयोग किया जाना है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-रीड **uint32_t**। देखें भी [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual **float** [get_Width](../ishape/get_width/)() | आकार की चौड़ाई बिंदुओं में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | आकार के ऊपरी-बाएँ कोने का x-निर्देशांक बिंदुओं में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | आकार के ऊपरी-बाएँ कोने का y-निर्देशांक बिंदुओं में प्राप्त करता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे का आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे का आकार। केवल-रीड **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जो वर्तमान आकार से विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | आकार थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप डिफ़ॉल्ट रूप से उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि वस्तु targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# ‘is’ ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी इंटर्नल डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सब-क्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइजेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | आकार से जुड़ा वैकल्पिक टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | आकार से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | प्रोपर्टी निर्धारित करती है कि आकार काला-श्वेत डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | आकार की ऊँचाई बिंदुओं में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि आकार छुपा है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | आकार का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | कच्चे आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट आकार को z-धुरी के चारों ओर घुमाए जाने वाले डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | आकार की चौड़ाई बिंदुओं में सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | आकार के ऊपरी-बाएँ कोने का x-निर्देशांक बिंदुओं में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | आकार के ऊपरी-बाएँ कोने का y-निर्देशांक बिंदुओं में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर (शेयरड नहीं) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंट का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी इंटर्नल डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [IShape](../ishape/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)