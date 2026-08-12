---
title: GroupShape
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 1197
url: /hi/aspose.slides/groupshape/
---
## GroupShape वर्ग

एक स्लाइड पर आकृतियों के समूह का प्रतिनिधित्व करता है।

```cpp
class GroupShape : public Aspose::Slides::Shape,
                   public Aspose::Slides::IGroupShape
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई placeholder नहीं है तो एक नया placeholder जोड़ता है और placeholder गुणों को एक निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजन के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक आकृति से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक आकृति से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्धारित करती है कि आकृति काली-श्वेत प्रदर्शन मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकृति का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकृति पर लागू पिक्सेल प्रभावों वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जो प्रभाव गुण नहीं रखतीं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकृति के लिए भराव फ़ॉर्मेटिंग गुणों वाले [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जिनमें भराव गुण नहीं हैं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकृति फ्रेम के गुणों को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() override | आकृति के लॉक को लौटाता है। केवल-पढ़ने योग्य [IGroupShapeLock](../igroupshapelock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकृति की ऊँचाई को पॉइंट में मापता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक प्रबंधक को लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘डेकोरेटिव के रूप में चिह्नित करें’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | आकृति के लिए रेखा फ़ॉर्मेटिंग गुणों वाले [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। नोट: [GroupShape](./) ऑब्जेक्ट्स के लिए null लौटाता है क्योंकि उनके पास रेखा गुण नहीं होते। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकृति का नाम लौटाता है। यह null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान का प्रयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल तक स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकृति को भरोसेमंद तरीके से संदर्भित करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें भी [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकृति समूहित है तो पैरेंट [GroupShape](./) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकृति के लिए placeholder लौटाता है। यदि आकृति में कोई placeholder नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | कच्चे shape फ्रेम के गुणों को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाव के डिग्री संख्या को लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव को दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर समूह के भीतर एक आकृति लौटाता है। केवल-पढ़ने योग्य [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकृति के लॉक को लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | समूह के भीतर आकृतियों के संग्रह को लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../ishapecollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकृति की पैरेंट स्लाइड को लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकृति के 3D प्रभाव गुणों वाले [ThreeDFormat](../threedformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए जिनमें 3D गुण नहीं होते, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | ऐड-इन या अन्य कोड द्वारा उपयोग हेतु एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें भी [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | आकृति की चौड़ाई को पॉइंट में मापता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकृति के ऊपरी-बायें कोने के x-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकृति के ऊपरी-बायें कोने के y-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | आकृति की z-क्रम में स्थिति लौटाता है। Shapes[0] z-क्रम के पीछे वाली आकृति लौटाता है, और Shapes[Shapes.Count - 1] सामने वाली आकृति लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक मूलभूत placeholder आकृति लौटाता है (लेआउट या मास्टर स्लाइड से वह आकृति जिससे वर्तमान आकृति विरासत में मिली है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकृति थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए सामग्री से गणना किए गए आकृति के दृश्य बाउंड्स को प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ मान प्रकार के ऑब्जेक्ट की तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग के केस के लिए विशेषण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकृति placeholder नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | आकृति से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकृति से जुड़े वैकल्पिक पाठ के शीर्षक को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्धारित करती है कि आकृति काली-श्वेत मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकृति फ्रेम के गुणों को सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकृति की ऊँचाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक को सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘डेकोरेटिव के रूप में चिह्नित करें’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकृति का नाम सेट करता है। यह null नहीं होना चाहिए। यदि आवश्यक हो तो खाली स्ट्रिंग मान का उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | कच्चे shape फ्रेम के गुणों को सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाव के डिग्री संख्या को सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव को दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव को दर्शाता है। लिखें **float**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकृति की चौड़ाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकृति के ऊपरी-बायें कोने के x-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकृति के ऊपरी-बायें कोने के y-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वाँ टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें भी

* वर्ग [Shape](../shape/)
* वर्ग [IGroupShape](../igroupshape/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)