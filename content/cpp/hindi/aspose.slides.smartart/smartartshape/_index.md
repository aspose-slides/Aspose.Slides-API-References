---
title: SmartArtShape
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: SmartArt आकार का प्रतिनिधित्व करता है
type: docs
weight: 105
url: /hi/aspose.slides.smartart/smartartshape/
---
## SmartArtShape वर्ग


प्रतिनिधित्व करता है [SmartArt](../smartart/) आकृति

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | आकृति के तत्वों की सरणी बनाता और लौटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | निर्दिष्ट अनुक्रमणिका पर आकृति का समायोजन मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | आकृति के समायोजन मानों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | आकृति से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | आकृति से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्दिष्ट करती है कि आकृति ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे प्रदर्शित होगी। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | आकृति का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | आकृति पर लागू पिक्सेल प्रभावों वाले [EffectFormat](../../aspose.slides/effectformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार की आकृतियों के लिए जो प्रभाव गुण नहीं रखतीं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | आकृति के लिए भराव फ़ॉर्मेटिंग गुणों वाले [FillFormat](../../aspose.slides/fillformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार की आकृतियों के लिए जो भराव गुण नहीं रखतीं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | आकार फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | आकृति की ऊँचाई, बिंदुओं में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | निर्धारित करता है कि आकृति छुपी है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | आकृति के लिए लाइन फ़ॉर्मेटिंग गुणों वाले [LineFormat](../../aspose.slides/lineformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार की आकृतियों के लिए जो लाइन गुण नहीं रखतीं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | आकार का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का प्रयोग करें। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकार के जीवनकाल के लिए स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकार को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../../aspose.slides/groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | स्लाइड के पैरेंट प्रस्तुति को लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | कच्चे आकार फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | निर्दिष्ट आकार के Z-अक्ष के चारों ओर घुमा दिया गया डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान वामावर्त घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | आकार के लॉक लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | आकार की शैली ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IShapeStyle](../../aspose.slides/ishapestyle/)। |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | ज्यामिति प्रीसेट प्रकार लौटाता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट पर रीसेट हो जाएंगे। पढ़ें [Slides::ShapeType](../../aspose.slides/shapetype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | [SmartArt](../smartart/) आकार का पाठ लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../aspose.slides/itextframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | आकार के 3D प्रभाव गुणों वाले [ThreeDFormat](../../aspose.slides/threedformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार की आकृतियों के लिए जो 3D गुण नहीं रखतीं, null लौटाया जा सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/)। |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाना है। चूँकि इस मान को उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | आकार की चौड़ाई, बिंदुओं में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | आकार के ऊपरी-बाएँ कोने का X-निर्देशांक, बिंदुओं में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | आकार के ऊपरी-बाएँ कोने का Y-निर्देशांक, बिंदुओं में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | आकार की Z-क्रम में स्थिति लौटाता है। Shapes[0] पीछे की ज़-क्रम में आकार लौटाता है, और Shapes[Shapes.Count - 1] आगे की ज़-क्रम में आकार लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | एक बुनियादी प्लेसहोल्डर आकार लौटाता है (लेआउट और/या मास्टर स्लाइड से आकार जिसका वर्तमान आकार उनसे विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ा रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | ज्यामिति आकार के पाथ की कॉपी लौटाता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानान्तर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | रेंडर किए गए कंटेंट से गणना किए गए आकार के दृश्य बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य-टाइप द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# ‘is’ ऑपरेटर का समानान्तर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानान्तर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाएँ इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | दर्शाता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | आकृति से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | आकृति से जुड़ा वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | प्रॉपर्टी निर्दिष्ट करती है कि आकृति ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे प्रदर्शित होगी। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | आकार फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | आकार की ऊँचाई, बिंदुओं में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छुपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | आकार का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग मान का प्रयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | कच्चे आकार फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | निर्दिष्ट आकार को Z-अक्ष के चारों ओर घुमा देने वाले डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान वामावर्त घुमाव दर्शाता है। लिखें **float**। |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | ज्यामिति प्रीसेट प्रकार सेट करता है। नोट: मान बदलने पर सभी समायोजन मान डिफ़ॉल्ट पर रीसेट हो जाएंगे। लिखें [Slides::ShapeType](../../aspose.slides/shapetype/)। |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | आकार की चौड़ाई, बिंदुओं में मापी गई, सेट करता है। लिखें **float**। |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | आकार के ऊपरी-बाएँ कोने का X-निर्देशांक, बिंदुओं में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | आकार के ऊपरी-बाएँ कोने का Y-निर्देशांक, बिंदुओं में मापी गई, सेट करता है। लिखें **float**। |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) ऑब्जेक्ट से आकार ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होने चाहिए। आकार ([ShapeType](../../aspose.slides/shapetype/)) का प्रकार [ShapeType::Custom](../../aspose.slides/shapetype/) में बदलता है। |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) की array से आकार ज्यामिति को अपडेट करता है। निर्देशांक आकार के बाएँ-ऊपरी कोने के सापेक्ष होते हैं। आकार ([ShapeType](../../aspose.slides/shapetype/)) का प्रकार [ShapeType::Custom](../../aspose.slides/shapetype/) में बदलता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* वर्ग [GeometryShape](../../aspose.slides/geometryshape/)
* वर्ग [ISmartArtShape](../ismartartshape/)
* नामस्थान [Aspose::Slides::SmartArt](../)
* लाइब्रेरी [Aspose.Slides](../../)