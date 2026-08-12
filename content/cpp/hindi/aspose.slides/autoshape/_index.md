---
title: AutoShape
second_title: Aspose.Slides for C++ API संदर्भ
description: एक AutoShape का प्रतिनिधित्व करता है।
type: docs
weight: 66
url: /hi/aspose.slides/autoshape/
---
## AutoShape वर्ग

एक [AutoShape](./) का प्रतिनिधित्व करता है।

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई-placeholder नहीं है तो नया-placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट वाले में सेट करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | एक आकार में नया [TextFrame](../textframe/) जोड़ता है। यदि आकार में पहले से [TextFrame](../textframe/) है तो केवल उसका पाठ बदलता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | आकार के तत्वों की एरे बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर आकार के समायोजन मान को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | आकार से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | आकार से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | ऑटोशेप के लॉक को लौटाता है। केवल-पढ़ने योग्य [IAutoShapeLock](../iautoshapelock/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्धारित करती है कि आकार काले-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइट्स की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकार पर लागू पिक्सेल इफ़ेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनके पास इफ़ेक्ट प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकार के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टी वाला [FillFormat](../fillformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनके पास फ़िल प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextBox](./get_istextbox/)() override | निर्धारित करता है कि आकार टेक्स्ट बॉक्स है या नहीं। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टी वाला [LineFormat](../lineformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनके पास लाइन प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकार का नाम लौटाता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड अनूठा पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरोप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य **uint32_t**। अन्य देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकार के लिए placeholder लौटाता है। यदि आकार के पास placeholder नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चा shape frame की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार को z-अक्ष के आसपास घुमाने के डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | आकार की स्टाइल ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | ज्यामिति प्रीसेट प्रकार लौटाता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफॉल्ट मानों में रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../shapetype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | [AutoShape](./) के लिए [TextFrame](../textframe/) ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../itextframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकार के लिए 3D इफ़ेक्ट प्रॉपर्टी वाला [ThreeDFormat](../threedformat/) ऑब्जेक्ट लौटाता है। नोट: उन कुछ प्रकार के आकारों के लिए null लौटाया जा सकता है जिनके पास 3D प्रॉपर्टी नहीं होती। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जो ऐड-इन या अन्य कोड द्वारा उपयोग के लिए है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अनोखा कुंजी नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। अन्य देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | निर्धारित करता है कि यह ऑटोशेप स्लाइड की बैकग्राउंड फ़िल से भरना चाहिए या स्टाइल/फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट। पढ़ें **bool**। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे वाले आकार को लौटाता है, और Shapes[Shapes.Count - 1] आगे वाले आकार को लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बेसिक placeholder आकार (लेआउट और/या मास्टर स्लाइड से आया आकार) लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ज्यामिति आकार के पाथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफॉल्ट रूप में [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेण्डर किए गए कंटेंट से गणना किए गए आकार की विज़ुअल बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार ऑब्जेक्ट की रेफ़रेंस तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार placeholder नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्धारित करती है कि आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे shape frame की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार को z-अक्ष के आसपास घुमाने के डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। लिखें **float**। |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | ज्यामिति प्रीसेट टाइप सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफॉल्ट मानों में रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../shapetype/)। |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | निर्धारित करता है कि यह ऑटोशेप स्लाइड की बैकग्राउंड फ़िल से भरना चाहिए या स्टाइल/फ़िल फ़ॉर्मेट द्वारा निर्दिष्ट। लिखें **bool**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को सेट करता है, पॉइंट में मापी गई। लिखें **float**। |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से आकार ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) की एरे से आकार ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak प्वाइंटर (shared के बजाय) सेट करता है। कंटेनरों में प्वाइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट प्वाइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## और देखें

* क्लास [GeometryShape](../geometryshape/)
* क्लास [IAutoShape](../iautoshape/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)