---
title: PictureFrame
second_title: Aspose.Slides for C++ API संदर्भ
description: एक फ्रेम का प्रतिनिधित्व करता है जिसमें अंदर एक चित्र होता है।
type: docs
weight: 4733
url: /hi/aspose.slides/pictureframe/
---
## PictureFrame क्लास

एक फ्रेम को दर्शाता है जिसमें भीतर एक चित्र होता है।

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | आकार के तत्वों की एरे बनाता है और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर आकार के समायोजन मान को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | आकार के समायोजन मानों का संग्रह लौटाता है। केवल-पठन [IAdjustValueCollection](../iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | आकार से जुड़े वैकल्पिक पाठ को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | आकार से जुड़े वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-और-सफेद प्रदर्शन मोड में कैसे प्रस्तुत होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकार के कस्टम डेटा को लौटाता है। केवल-पठन [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकार पर लागू पिक्सेल इफेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ आकारों के लिए जिसमें इफ़ेक्ट प्रॉपर्टी नहीं है, यह null लौट सकता है। केवल-पठन [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकार के लिए भराव स्वरूप प्रॉपर्टी वाले [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ आकारों के लिए जिसमें भराव प्रॉपर्टी नहीं है, यह null लौट सकता है। केवल-पठन [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ को लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Height](../shape/get_height/)() override | आकार की ऊँचाई को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा हुआ है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर को लौटाता है। केवल-पठन [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsCameo](./get_iscameo/)() | निर्धारित करता है कि [PictureFrame](./) एक Cameo ऑब्जेक्ट है या नहीं। केवल-पठन **bool**। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पठन **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पठन **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकार के लिए लाइन स्वरूप प्रॉपर्टी वाले [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ आकारों में लाइन प्रॉपर्टी न होने पर यह null लौट सकता है। केवल-पठन [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकार का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | स्लाइड-स्तरीय अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल में स्थिर रहता है। केवल-पठन **uint32_t**। देखें [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पठन [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | पिक्चर फ्रेम के लिए [PictureFillFormat](../picturefillformat/) ऑब्जेक्ट लौटाता है। केवल-पठन [IPictureFillFormat](../ipicturefillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | आकार की लॉक प्रॉपर्टी लौटाता है। केवल-पठन [IPictureFrameLock](../ipictureframelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पठन [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड के पैरेंट प्रेज़ेंटेशन को लौटाता है। केवल-पठन [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | आकार फ्रेम की कच्ची प्रॉपर्टी लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | पिक्चर फ्रेम की ऊँचाई के स्केल (मूल चित्र आकार के सापेक्ष) को लौटाता है। मान 1.0 का मतलब 100% है। पढ़ें **float**। |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | पिक्चर फ्रेम की चौड़ाई के स्केल (मूल चित्र आकार के सापेक्ष) को लौटाता है। मान 1.0 का मतलब 100% है। पढ़ें **float**। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकार को z-अक्ष के आसपास घूमाने के डिग्री को लौटाता है। सकारात्मक मान घड़ी की दिशा में घूमना दर्शाता है; नकारात्मक मान विपरीत दिशा में। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकार की लॉक प्रॉपर्टी लौटाता है। केवल-पठन [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | आकार के स्टाइल ऑब्जेक्ट को लौटाता है। केवल-पठन [IShapeStyle](../ishapestyle/)। |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकार की पैरेंट स्लाइड को लौटाता है। केवल-पठन [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकार के 3D इफ़ेक्ट प्रॉपर्टी वाले [ThreeDFormat](../threedformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ आकारों में 3D प्रॉपर्टी न होने पर यह null लौट सकता है। केवल-पठन [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | ऐड-इन्स या अन्य कोड द्वारा उपयोग के लिए एक आंतरिक, प्रेज़ेंटेशन-स्तरीय पहचानकर्ता लौटाता है। चूँकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामmatically पुनः निर्धारित किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में प्रयोग नहीं करना चाहिए। केवल-पठन **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../shape/get_width/)() override | आकार की चौड़ाई को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] पीछे के आकार को देता है, और Shapes[Shapes.Count - 1] आगे के आकार को। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट या मास्टर स्लाइड से वह आकार जिससे वर्तमान आकार विरासत में लेता है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ज्यामिति आकार के पथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए कंटेंट से गणना किए गए आकार की दृश्य सीमा प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस को nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक पाठ को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकार से जुड़े वैकल्पिक पाठ के शीर्षक को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि आकार काले-और-सफेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ को सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकार की ऊँचाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | आकार छिपा हुआ है या नहीं निर्धारित करता है। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक को सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यकता होने पर खाली स्ट्रिंग का उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकार फ्रेम की कच्ची प्रॉपर्टीज़ को सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | पिक्चर फ्रेम की ऊँचाई का स्केल (मूल चित्र आकार के सापेक्ष) सेट करता है। मान 1.0 का मतलब 100% है। लिखें **float**। |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | पिक्चर फ्रेम की चौड़ाई का स्केल (मूल चित्र आकार के सापेक्ष) सेट करता है। मान 1.0 का मतलब 100% है। लिखें **float**। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकार को z-अक्ष के आसपास घूमाने के डिग्री सेट करता है। सकारात्मक मान घड़ी की दिशा में घूमना दर्शाता है; नकारात्मक मान विपरीत दिशा में। लिखें **float**। |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | आकार की चौड़ाई को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | आकार ज्यामिति को [IGeometryPath](../igeometrypath/) ऑब्जेक्ट से अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | आकार ज्यामिति को [IGeometryPath](../igeometrypath/) की एरे से अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। आकार के प्रकार ([ShapeType](../shapetype/)) को [ShapeType::Custom](../shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक पॉइंटर काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक पॉइंटर काउंटर को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणी

निम्नलिखित उदाहरण दिखाता है कि कैसे [Audio](../audio/) फ्रेम थंबनेल बदला जाता है।

```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// स्लाइड में निर्दिष्ट स्थिति और आकार के साथ एक ऑडियो फ्रेम जोड़ता है।
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// प्रेज़ेंटेशन रिसोर्सेज़ में एक इमेज जोड़ता है।
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// ऑडियो फ्रेम के लिए इमेज सेट करता है।
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Sसंशोधित प्रेज़ेंटेशन को डिस्क पर सहेजता है
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [GeometryShape](../geometryshape/)
* क्लास [IPictureFrame](../ipictureframe/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)