---
title: IPictureFrame
second_title: Aspose.Slides for C++ API संदर्भ
description: एक फ्रेम का प्रतिनिधित्व करता है जिसमें चित्र अंतर्निहित है।
type: docs
weight: 3251
url: /hi/aspose.slides/ipictureframe/
---
## IPictureFrame क्लास

एक फ्रेम को दर्शाता है जिसमें चित्र अंतर्निहित है।

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | आकार के तत्वों का ऐरे बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) कार्यपद्धति से करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | मान प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | निर्दिष्ट अनुक्रमणिका पर आकार के समायोजन मान को लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../iadjustvaluecollection/)। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | आकार से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | आकार से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | प्रॉपर्टी यह निर्धारित करती है कि आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | आकार के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | आकार पर लागू पिक्सल इफेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | आकार के फ़िल फ़ॉर्मेटिंग गुणों वाले [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | आकार की ऊँचाई को पॉइंट में मापता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक केवल-पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘डेकोरेटिव के रूप में चिह्नित करें’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि आकार TextHolder है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | आकार के लाइन फ़ॉर्मेटिंग गुणों वाले [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | आकार का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | स्लाइड-संकुचित एक अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल भर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें also [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | चित्र फ्रेम के लिए [PictureFillFormat](../picturefillformat/) ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | [PictureFrame](../pictureframe/) की लॉक स्थिति लौटाता है। केवल-पढ़ने योग्य [IPictureFrameLock](../ipictureframelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | आकार के लिए प्लेसहोल्डर लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 = 100 %। पढ़ें **float**। |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल लौटाता है। मान 1.0 = 100 %। पढ़ें **float**। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट आकार के z-अक्ष के आसपास घुमाव के डिग्री संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | आकार की लॉक स्थिति लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | आकार की शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../ishapestyle/)। |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | जियोमेट्री प्रीसैट प्रकार लौटाता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों में रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../shapetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | आकार के लाइन फ़ॉर्मेटिंग गुणों वाले [ThreeDFormat](../threedformat/) ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | आंतरिक, प्रस्तुति-संकुचित पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी न मानें। केवल-पढ़ने योग्य **uint32_t**। देखें also [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual **float** [get_Width](../ishape/get_width/)() | आकार की चौड़ाई को पॉइंट में मापता है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | आकार की z-क्रम में स्थिति लौटाता है। Shapes[0] पीछे की स्थिति वाला आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की स्थिति वाला आकार। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | मूल प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ा रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | जियोमेट्री आकार के पाथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ-ऊपर कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | आकार थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स प्रकार डिफ़ॉल्ट रूप से प्रयोग होता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वास्तविक ऑब्जेक्ट प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित इंस्टेंस का प्रतिनिधित्व करता है या नहीं। C# ‘is’ ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक रूप से कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सब-क्लास की कॉपी-कंस्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारम्भ करता है और सब-क्लास की कॉपी-कंस्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार के ऑब्जेक्ट की nullptr से रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | आकार से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | प्रॉपर्टी यह निर्धारित करती है कि आकार काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | आकार की ऊँचाई को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘डेकोरेटिव के रूप में चिह्नित करें’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | आकार का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | कच्ची आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | चित्र फ्रेम की ऊँचाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 = 100 %। लिखें **float**। |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | चित्र फ्रेम की चौड़ाई (मूल चित्र आकार के सापेक्ष) का स्केल सेट करता है। मान 1.0 = 100 %। लिखें **float**। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट आकार के z-अक्ष के आसपास घुमाव के डिग्री संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | जियोमेट्री प्रीसैट प्रकार सेट करता है। नोट: मान बदलने पर सभी समायोजन मान उनके डिफ़ॉल्ट मानों में रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../shapetype/)। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | आकार की चौड़ाई को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | आकार के ऊपर-बाएँ कोने के x-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | आकार के ऊपर-बाएँ कोने के y-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से आकार जियोमेट्री को अपडेट करता है। निर्देशांक बाएँ-ऊपर कोने के सापेक्ष होने चाहिए। आकार का प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) के ऐरे से आकार जियोमेट्री को अपडेट करता है। निर्देशांक बाएँ-ऊपर कोने के सापेक्ष होते हैं। आकार का प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्गुमेंट को वीक पॉइंटर सेट करता है (शेर्ड के बजाय)। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अन-लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [IGeometryShape](../igeometryshape/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)