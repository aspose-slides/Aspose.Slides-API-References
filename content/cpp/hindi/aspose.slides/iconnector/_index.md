---
title: IConnector
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
weight: 1847
url: /hi/aspose.slides/iconnector/
---
## IConnector क्लास

एक कनेक्टर का प्रतिनिधित्व करता है।

```cpp
class IConnector : public virtual Aspose::Slides::IGeometryShape
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | शेप के तत्वों की array बनाता है और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | निर्दिष्ट इंडेक्स पर एक शेप के एडजस्टमेंट मान को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | शेप के एडजस्टमेंट मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | शेप से जुड़ा वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | शेप से जुड़ी वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | प्रॉपर्टी निर्धारित करती है कि एक शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() | [Connector](../connector/) के लॉक लौटाता है। केवल-पढ़ने योग्य [IConnectorLock](../iconnectorlock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | शेप के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) ऑब्जेक्ट लौटाता है जिसमें शेप पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() | कनेक्टर के अंत को जुड़ने के लिए शेप लौटाता है। पढ़ें [IShape](../ishape/)। |
| virtual **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() | अंत शेप के कनेक्शन साइट का इंडेक्स लौटाता है। पढ़ें **uint32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है जिसमें एक शेप के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | शेप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | शेप की ऊँचाई प्राप्त करता है, पॉइंट्स में मापी गई। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' विकल्प प्राप्त करता है पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि शेप ग्रुपेड है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि शेप TextHolder है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है जिसमें एक शेप के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | एक शेप का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | एक स्लाइड-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो शेप के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शेप को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि शेप ग्रुपेड है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | एक शेप के लिए प्लेसहोल्डर लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | रॉ शेप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट शेप के z-अक्ष के चारों ओर घुमाव के डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | शेप के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | शेप के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | ज्यॉमेट्री प्रीसेट टाइप लौटाता है। ध्यान दें: मान बदलने पर सभी एडजस्टमेंट मान उनके डिफ़ॉल्ट मान पर रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../shapetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() | कनेक्टर की शुरुआत को जुड़ने के लिए शेप लौटाता है। पढ़ें [IShape](../ishape/)। |
| virtual **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() | स्टार्ट शेप के कनेक्शन साइट का इंडेक्स लौटाता है। पढ़ें **uint32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जिसमें एक शेप के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एक_internal, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन्स या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्रामmatically पुनः असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual **float** [get_Width](../ishape/get_width/)() | शेप की चौड़ाई प्राप्त करता है, पॉइंट्स में मापी गई। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | शेप के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट प्राप्त करता है, पॉइंट्स में मापी गई। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | शेप के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट प्राप्त करता है, पॉइंट्स में मापी गई। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | शेप की ज़ी-ऑर्डर में स्थिति लौटाता है। Shapes[0] ज़ी-ऑर्डर के पीछे की शेप लौटाता है, और Shapes[Shapes.Count - 1] ज़ी-ऑर्डर के सामने की शेप लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बेसिक प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से वह शेप जिससे वर्तमान शेप विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | ज्यॉमेट्री शेप के पाथ की कॉपी लौटाता है। कोऑर्डिनेट्स शेप के बाएँ शीर्ष कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) शेप थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | शेप थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयरड रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| virtual void [Reroute](./reroute/)() | कनेक्टर को पुनः मार्गित करता है ताकि वह जुड़े हुए शेप्स के बीच सबसे छोटा पाथ ले। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | शेप से जुड़े वैकल्पिक टेक्स्ट को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | शेप से जुड़े वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | प्रॉपर्टी निर्धारित करती है कि एक शेप ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | कनेक्टर के अंत को जुड़ने के लिए शेप सेट करता है। लिखें [IShape](../ishape/)। |
| virtual void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) | अंत शेप के कनेक्शन साइट का इंडेक्स सेट करता है। लिखें **uint32_t**। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | शेप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | शेप की ऊँचाई सेट करता है, पॉइंट्स में मापी गई। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' विकल्प सेट करता है पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | शेप का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | रॉ शेप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट शेप को z-अक्ष के चारों ओर घुमाने के डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विरुद्ध दिशा में घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ज्यॉमेट्री प्रीसेट टाइप सेट करता है। ध्यान दें: मान बदलने पर सभी एडजस्टमेंट मान डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../shapetype/)। |
| virtual void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | कनेक्टर की शुरुआत को जुड़ने के लिए शेप सेट करता है। लिखें [IShape](../ishape/)। |
| virtual void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) | स्टार्ट शेप के कनेक्शन साइट का इंडेक्स सेट करता है। लिखें **uint32_t**। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | शेप की चौड़ाई सेट करता है, पॉइंट्स में मापी गई। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | शेप के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | शेप के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से शेप ज्यॉमेट्री को अपडेट करता है। कोऑर्डिनेट्स शेप के बाएँ शीर्ष कोने के सापेक्ष होना चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) की array से शेप ज्यॉमेट्री को अपडेट करता है। कोऑर्डिनेट्स शेप के बाएँ शीर्ष कोने के सापेक्ष होना चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की सुविधा देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## देखें

* क्लास [IGeometryShape](../igeometryshape/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)