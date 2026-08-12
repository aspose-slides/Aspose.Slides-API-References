---
title: ISmartArtShape
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: SmartArt आरेख के अंदर एक shape का प्रतिनिधित्व करता है
type: docs
weight: 40
url: /hi/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape क्लास

एक [SmartArt](../smartart/) आरेख के अंदर shape का प्रतिनिधित्व करता है

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | यदि कोई नया placeholder नहीं है तो एक नया placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | shape के तत्वों की array बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिन्टैक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में reference प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में value प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | निर्दिष्ट इंडेक्स पर shape की adjustment मान लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | shape के adjustment मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | shape से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | shape से जुड़ा वैकल्पिक पाठ शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | संपत्ति निर्धारित करती है कि shape काली-सफेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | shape के कस्टम डेटा को लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) ऑब्जेक्ट लौटाता है जिसमें shape पर लागू पिक्सेल प्रभाव होते हैं। केवल-पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) ऑब्जेक्ट लौटाता है जिसमें shape के लिए fill फ़ॉर्मेटिंग गुण होते हैं। केवल-पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | shape फ्रेम की संपत्तियां लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | shape की ऊँचाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | निर्धारित करता है कि shape छिपा है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित hyperlink लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks मैनेजर केवल-पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित hyperlink लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | निर्धारित करता है कि shape TextHolder है या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। केवल-पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | shape का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | shape के जीवनकाल के दौरान स्थिर रहने वाला और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है, ऐसा slide-स्तरीय अद्वितीय पहचानकर्ता लौटाता है। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | यदि shape समूहित है तो पैरेंट [GroupShape](../../aspose.slides/groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | shape के लिए placeholder लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेज़ेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | raw shape फ्रेम की संपत्तियां लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री संख्या लौटाता है। सकारात्मक मान क्रमवार घूर्णन दर्शाता है; नकारात्मक मान विपरित घूर्णन दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | shape के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | shape की शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../../aspose.slides/ishapestyle/)। |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | geometry प्रीसेट प्रकार लौटाता है। नोट: मान बदलने पर सभी adjustment मान अपने डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../../aspose.slides/shapetype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | [SmartArt](../smartart/) shape का टेक्स्ट लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) ऑब्जेक्ट लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग गुण होते हैं। केवल-पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/)। |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | add-ins या अन्य कोड द्वारा उपयोग के लिए अभिप्रेत एक आंतरिक, प्रेज़ेंटेशन-स्तरीय पहचानकर्ता लौटाता है। क्योंकि यह मान उपयोगकर्ता द्वारा या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)। |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | shape की चौड़ाई पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | shape के ऊपर-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | shape के ऊपर-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में प्राप्त करता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | z-ऑर्डर में shape की स्थिति लौटाता है। Shapes[0] z-ऑर्डर के पीछे का shape लौटाता है, और Shapes[Shapes.Count - 1] आगे का shape लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | एक बेसिक placeholder shape लौटाता है (layout और/या master स्लाइड से shape जो वर्तमान shape को विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी reference काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | geometry shape के पथ की कॉपी लौटाता है। कॉऑर्डिनेट्स shape के ऊँचे बाएँ कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) shape थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | shape थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने को सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है value-टाइप ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत रूप स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकृत रूप स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | shape से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | shape से जुड़ा वैकल्पिक पाठ शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | संपत्ति निर्धारित करती है कि shape काली-सफेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | shape फ्रेम की संपत्तियां सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | shape की ऊँचाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | निर्धारित करता है कि shape छिपा है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित hyperlink सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | माउस ओवर के लिए परिभाषित hyperlink सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | shape का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | raw shape फ्रेम की संपत्तियां सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | निर्दिष्ट shape को z-अक्ष के चारों ओर घुमाने के डिग्री संख्या सेट करता है। सकारात्मक मान क्रमवार घूर्णन दर्शाता है; नकारात्मक मान विपरित घूर्णन दर्शाता है। लिखें **float**। |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | geometry प्रीसेट प्रकार सेट करता है। नोट: मान बदलने पर सभी adjustment मान अपने डिफ़ॉल्ट मानों पर रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../../aspose.slides/shapetype/)। |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | shape की चौड़ाई पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | shape के ऊपर-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | shape के ऊपर-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट्स में सेट करता है। लिखें **float**। |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | [IGeometryPath](../../aspose.slides/igeometrypath/) ऑब्जेक्ट से shape geometry को अपडेट करता है। कॉऑर्डिनेट्स shape के बाएँ-ऊपर कोने के सापेक्ष होना चाहिए। shape के प्रकार ([ShapeType](../../aspose.slides/shapetype/)) को [ShapeType::Custom](../../aspose.slides/shapetype/) में बदलता है। |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | [IGeometryPath](../../aspose.slides/igeometrypath/) की array से shape geometry को अपडेट करता है। कॉऑर्डिनेट्स shape के बाएँ-ऊपर कोने के सापेक्ष होना चाहिए। shape के प्रकार ([ShapeType](../../aspose.slides/shapetype/)) को [ShapeType::Custom](../../aspose.slides/shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IGeometryShape](../../aspose.slides/igeometryshape/)
* नामस्थान [Aspose::Slides::SmartArt](../)
* लाइब्रेरी [Aspose.Slides](../../)