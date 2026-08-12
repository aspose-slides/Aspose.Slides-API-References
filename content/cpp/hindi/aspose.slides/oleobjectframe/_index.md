---
title: OleObjectFrame
second_title: Aspose.Slides for C++ API संदर्भ
description: स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 4603
url: /hi/aspose.slides/oleobjectframe/
---
## OleObjectFrame वर्ग

आकृति पर एक OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | यदि कोई प्लेसहोल्डर नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट प्लेसहोल्डर में सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली वाले फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | एक आकृति से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | एक आकृति से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | यह संपत्ति निर्धारित करती है कि आकृति काले-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | आकृति का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | आकृति पर लागू पिक्सेल इफ़ेक्ट्स वाले [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें इफ़ेक्ट गुण नहीं होते। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | OLE एंबेडेड डेटा के बारे में जानकारी प्राप्त करता है। पढ़ें [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)। |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | एंबेडेड OLE ऑब्जेक्ट का फ़ाइल नाम लौटाता है। |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | एंबेडेड OLE ऑब्जेक्ट का पथ लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | आकृति के लिए फिल फ़ॉर्मेटिंग गुणों को सम्मिलित करने वाले [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें फिल गुण नहीं होते। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | आकृति फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| **float** [get_Height](../shape/get_height/)() override | आकृति की ऊँचाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../shape/get_hidden/)() override | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | हाइपरलिंक प्रबंधक लौटाता है। केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल पढ़ने योग्य **bool**। |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखाई देता है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से जुड़ा है या नहीं। केवल पढ़ने योग्य **bool**। |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | निर्धारित करता है कि आकृति TextHolder_PPT है या नहीं। केवल पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | आकृति के लिए लाइन फ़ॉर्मेटिंग गुणों को सम्मिलित करने वाले [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें लाइन गुण नहीं होते। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | लिंक की गई फ़ाइल का पूर्ण पथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | लिंक की गई फ़ाइल का पूर्ण पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | यदि मौजूद हो तो लिंक की गई फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | आकृति का नाम लौटाता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | ऑब्जेक्ट का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | ऑब्जेक्ट का ProgID लौटाता है। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है जो आकृति के जीवनकाल भर स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ के किसी भी स्थान से आकृति का विश्वसनीय संदर्भ देता है। केवल पढ़ने योग्य **uint32_t**। देखें also [Shape::get_UniqueId](../shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | यदि आकृति समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | आकृति के प्लेसहोल्डर को लौटाता है। यदि आकृति के पास प्लेसहोल्डर नहीं है तो null लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | स्लाइड की पैरेंट प्रस्तुति को लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | रॉ शेप फ्रेम के गुण लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| **float** [get_Rotation](../shape/get_rotation/)() override | निर्दिष्ट आकृति के z-अक्ष पर घुमाव के डिग्री की संख्या लौटाता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान प्रतिवर्त घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | आकृति की पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | OleObject इमेज भराव गुणों वाला ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | OleObject आइकन के लिए शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | आकृति के 3D इफ़ेक्ट गुणों को सम्मिलित करने वाले [ThreeDFormat](../threedformat/) ऑब्जेक्ट को लौटाता है। नोट: उन कुछ प्रकार की आकृतियों के लिए null लौटाया जा सकता है जिनमें 3D गुण नहीं होते। केवल पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड पहचानकर्ता लौटाता है जिसे ऐड-इन या अन्य कोड द्वारा उपयोग किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें also [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)। |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति के खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। पढ़ें **bool**। |
| **float** [get_Width](../shape/get_width/)() override | आकृति की चौड़ाई, पॉइंट में मापी गई, प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../shape/get_x/)() override | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| **float** [get_Y](../shape/get_y/)() override | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में मापता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z-ऑर्डर में आकृति की स्थिति लौटाता है। Shapes[0] पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] आगे की आकृति लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | लेआउट और/या मास्टर स्लाइड से विरासत में मिली मूल प्लेसहोल्डर आकृति लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | आकृति थंबनेल लौटाता है। [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकृति थंबनेल बॉण्ड्स प्रकार डिफॉल्ट रूप से उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट की वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | रेंडर किए गए सामग्री से गणना किए गए आकृति के दृश्य बाउंड्स प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य-टाइप द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नई ऑब्जेक्ट को प्रारंभ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नई ऑब्जेक्ट को प्रारंभ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकृति से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकृति से जुड़ा वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | यह संपत्ति निर्धारित करती है कि आकृति काले-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | आकृति फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Height](../shape/set_height/)(**float**) override | आकृति की ऊँचाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकृति छिपी हुई है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दिखाई देता है या नहीं। लिखें **bool**। |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | पूर्ण पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। लिखें [System::String](../../system/string/)। |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | आकृति का नाम सेट करता है। null नहीं होना चाहिए। आवश्यकता पड़ने पर खाली स्ट्रिंग मान उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | ऑब्जेक्ट का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | ऑब्जेक्ट का ProgID सेट करता है। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | रॉ शेप फ्रेम के गुण सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | निर्दिष्ट आकृति के z-अक्ष पर घुमाव के डिग्री की संख्या सेट करता है। एक सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; एक नकारात्मक मान प्रतिवर्त घुमाव दर्शाता है। लिखें **float**। |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | OleObject आइकन के लिए शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | निर्धारित करता है कि लिंक्ड एंबेडेड ऑब्जेक्ट प्रस्तुति खुले या प्रिंट होने पर स्वचालित रूप से अपडेट होता है या नहीं। लिखें **bool**। |
| void [set_Width](../shape/set_width/)(**float**) override | आकृति की चौड़ाई, पॉइंट में मापी गई, सेट करता है। लिखें **float**। |
| void [set_X](../shape/set_x/)(**float**) override | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| void [set_Y](../shape/set_y/)(**float**) override | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट में सेट करता है। लिखें **float**। |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | OLE एंबेडेड डेटा के बारे में जानकारी सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

निम्न उदाहरण दिखाता है कि OLE ऑब्जेक्ट फ्रेम्स तक कैसे पहुँचें।

```cpp
// PPTX को एक प्रेजेंटेशन ऑब्जेक्ट में लोड करता है
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// पहली स्लाइड तक पहुँचता है
auto slide = pres->get_Slides()->idx_get(0);
// शेप को OleObjectFrame में कास्ट करता है
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// OLE ऑब्जेक्ट को पढ़ता है और उसे डिस्क पर लिखता है
if (oleObjectFrame != nullptr)
{
    // एंबेडेड फ़ाइल डेटा प्राप्त करता है
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // एंबेडेड फ़ाइल एक्सटेंशन प्राप्त करता है
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // निकाली गई फ़ाइल को सहेजने के लिए पाथ बनाता है
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // निकाले गए डेटा को सहेजता है
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## देखें

* वर्ग [GraphicalObject](../graphicalobject/)
* वर्ग [IOleObjectFrame](../ioleobjectframe/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)