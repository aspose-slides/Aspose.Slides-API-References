---
title: Connector
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक कनेक्टर का प्रतिनिधित्व करता है।
type: docs
weight: 482
url: /hi/aspose.slides/connector/
---
## Connector वर्ग

Represents a connector.

```cpp
class Connector : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IConnector
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले पर सेट करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | शेप के तत्वों का ऐरे बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर शेप के समायोजन मान को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | शेप के समायोजन मानों का संग्रह लौटाता है। केवल पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक शेप से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक शेप से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि शेप काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | शेप पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() override | कनेक्टर के लॉक लौटाता है। केवल पढ़ने योग्य [IConnectorLock](../iconnectorlock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | शेप के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | शेप पर लागू पिक्सेल इफ़ेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ शेप प्रकारों के लिए जहाँ इफ़ेक्ट प्रॉपर्टी नहीं होती, यह null वापस कर सकता है। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() override | कनेक्टर के अंत को संलग्न करने के लिए शेप को लौटाता है। पढ़ें [IShape](../ishape/)। |
| **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() override | अंत शेप के लिए कनेक्शन साइट का इंडेक्स लौटाता है। पढ़ें **uint32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | एक शेप के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टी वाले [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ शेप प्रकारों में जहाँ भराव प्रॉपर्टी नहीं होती, यह null वापस कर सकता है। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | शेप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Height](../shape/get_height/)() override | शेप की ऊँचाई (पॉइंट में) प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि शेप छिपा हुआ है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक प्रबंधक लौटाता है। केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि शेप समूहित (grouped) है या नहीं। केवल पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि शेप TextHolder_PPT है या नहीं। केवल पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है जिसमें शेप के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होती हैं। नोट: कुछ शेप प्रकारों में जहाँ लाइन प्रॉपर्टी नहीं होती, यह null लौट सकता है। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | शेप का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग प्रयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफायर लौटाता है जो शेप के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी शेप को विश्वसनीय रूप से संदर्भित करने देता है। केवल पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि शेप समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | एक शेप के लिए प्लेसहोल्डर लौटाता है। यदि शेप में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | एक स्लाइड के पैरेंट प्रस्तुति को लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे शेप फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट शेप को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान उलटा घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | शेप के लॉक लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | शेप की स्टाइल ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | [AutoShape](../autoshape/) प्रकार लौटाता है। पढ़ें [Slides::ShapeType](../shapetype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | एक शेप के पैरेंट स्लाइड को लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() override | कनेक्टर की शुरुआत को संलग्न करने वाले शेप को लौटाता है। पढ़ें [IShape](../ishape/)। |
| **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() override | स्टार्ट शेप के लिए कनेक्शन साइट का इंडेक्स लौटाता है। पढ़ें **uint32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है जिसमें शेप के 3D इफ़ेक्ट प्रॉपर्टीज़ होती हैं। नोट: कुछ शेप प्रकारों में जहाँ 3D प्रॉपर्टी नहीं होती, यह null लौट सकता है। केवल पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः निर्धारित किया जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | शेप की चौड़ाई (पॉइंट में) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | शेप के ऊपरी-बाएँ कोने का x-निर्देशांक (पॉइंट में) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | शेप के ऊपरी-बाएँ कोने का y-निर्देशांक (पॉइंट में) प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में शेप की स्थिति लौटाता है। Shapes[0] पीछे की ओर शेप लौटाता है, और Shapes[Shapes.Count - 1] आगे की ओर शेप लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बुनियादी प्लेसहोल्डर शेप लौटाता है (लेआउट और/या मास्टर स्लाइड से शेप जिसे वर्तमान शेप विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | जियोमेट्री शेप के पाथ की कॉपी लौटाता है। निर्देशांक शेप के बायें उपर कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | शेप थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) शेप थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | शेप थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | शेप के रेंडर किए गए कंटेंट से गणना किए गए विज़ुअल बाउंड्स को प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | निर्धारित करता है कि यह शेप प्लेसहोल्डर नहीं है। |
| void [Reroute](./reroute/)() override | कनेक्टर को पुन:रूट करता है ताकि वह जुड़े शेप्स के बीच सबसे छोटा पथ ले। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | एक शेप से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक शेप से जुड़े वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्धारित करती है कि शेप काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | कनेक्टर के अंत को संलग्न करने वाले शेप को सेट करता है। लिखें [IShape](../ishape/)। |
| void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) override | अंत शेप के लिए कनेक्शन साइट का इंडेक्स सेट करता है। लिखें **uint32_t**। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | शेप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | शेप की ऊँचाई (पॉइंट में) सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि शेप छिपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | शेप का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग प्रयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे शेप फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट शेप को z-अक्ष के चारों ओर घुमाए गए डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान उलटा घुमाव दर्शाता है। लिखें **float**। |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | [AutoShape](../autoshape/) प्रकार सेट करता है। लिखें [Slides::ShapeType](../shapetype/)। |
| void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | कनेक्टर की शुरुआत को संलग्न करने वाले शेप को सेट करता है। लिखें [IShape](../ishape/)। |
| void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) override | स्टार्ट शेप के लिए कनेक्शन साइट का इंडेक्स सेट करता है। लिखें **uint32_t**। |
| void [set_Width](../shape/set_width/)(**float**) override | शेप की चौड़ाई (पॉइंट में) सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | शेप के ऊपरी-बाएँ कोने का x-निर्देशांक (पॉइंट में) सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | शेप के ऊपरी-बाएँ कोने का y-निर्देशांक (पॉइंट में) सेट करता है। लिखें **float**। |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से शेप जियोमेट्री को अपडेट करता है। निर्देशांक शेप के बायें उपर कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) की एरे से शेप जियोमेट्री को अपडेट करता है। निर्देशांक शेप के बायें उपर कोने के सापेक्ष होने चाहिए। शेप के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने की अनुमति देता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर मुक्त करता है। |

## संबंधित देखें

* क्लास [GeometryShape](../geometryshape/)
* क्लास [IConnector](../iconnector/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)