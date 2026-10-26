---
title: IOleObjectFrame
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्लाइड पर एक OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
weight: 3095
url: /hi/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame क्लास

एक स्लाइड पर OLE ऑब्जेक्ट का प्रतिनिधित्व करता है।

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई प्लेसहोल्डर नहीं है तो एक नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | दो NaN को समान मानता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है, ऐसी C#-शैली की फ्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | दो NaN को समान मानता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है, ऐसी C#-शैली की फ्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | एक आकृति से जुड़ा वैकल्पिक टेक्स्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | एक आकृति से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | संपत्ति निर्धारित करता है कि आकृति काले-और-सफ़ेद प्रदर्शन मोड में कैसे रेंडर होगी। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | आकृति पर कनेक्शन साइटों की संख्या लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | आकृति के कस्टम डेटा को लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | एक आकृति पर लागू पिक्सल इफ़ेक्ट्स युक्त [EffectFormat](../effectformat/) ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | OLE एम्बेडेड डेटा के बारे में जानकारी प्राप्त करता है। केवल पढ़ने योग्य [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)। |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | एम्बेडेड OLE ऑब्जेक्ट की फ़ाइल नाम लौटाता है |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | एम्बेडेड OLE ऑब्जेक्ट का पथ लौटाता है |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | एक आकृति के फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ युक्त [FillFormat](../fillformat/) ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | आकृति की ऊँचाई, पॉइंट्स में मापी, प्राप्त करता है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि आकृति छुपी है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक। केवल पढ़ने योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ‘Mark as decorative’ विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि आकृति समूहित है या नहीं। केवल पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | निर्धारित करता है कि ऑब्जेक्ट बाहरी फ़ाइल से जुड़ा है या नहीं। केवल पढ़ने योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि आकृति TextHolder है या नहीं। केवल पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | एक आकृति के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ युक्त [LineFormat](../lineformat/) ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | लिंक की गई फ़ाइल का पूर्ण पथ लौटाता है। छोटा फ़ाइल नाम उपयोग किया जाएगा। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | लिंक की गई फ़ाइल का पूर्ण पथ लौटाता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | यदि मौजूद है तो लिंक की गई फ़ाइल का सापेक्ष पथ लौटाता है, अन्यथा खाली स्ट्रिंग लौटाता है। केवल पढ़ने योग्य [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | आकृति का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | ऑब्जेक्ट का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | ऑब्जेक्ट का ProgID लौटाता है। केवल पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | आकृति के जीवनकाल के दौरान स्थिर रहने वाला स्लाइड-स्कोप्ड अद्वितीय पहचानकर्ता लौटाता है, जिससे PowerPoint या इंटरऑप कोड किसी भी स्थान से आकृति को विश्वसनीय रूप से संदर्भित कर सकता है। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि आकृति समूहित है तो पैरेंट [GroupShape](../groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाते हैं। केवल पढ़ने योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | आकृति के लिए प्लेसहोल्डर लौटाता है। केवल पढ़ने योग्य [IPlaceholder](../iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन को लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | कच्चे आकृति फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाव के डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | आकृति के लॉक लौटाता है। केवल पढ़ने योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | OleObject इमेज फ़िल प्रॉपर्टीज़ ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IPictureFillFormat](../ipicturefillformat/)। |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | OleObject आइकन के शीर्षक को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | एक आकृति के लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ युक्त [ThreeDFormat](../threedformat/) ऑब्जेक्ट को लौटाता है। केवल पढ़ने योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एड-इन्स या अन्य कोड द्वारा उपयोग के लिए इंटर्नल, प्रेजेंटेशन-स्कोप्ड पहचानकर्ता लौटाता है। चूँकि यह मान उपयोगकर्ता या प्रोग्रामेटिकली पुनः असाइन किया जा सकता है, इसे स्थायी अद्वितीय कुंजी के रूप में नहीं माना जाना चाहिए। केवल पढ़ने योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | निर्धारित करता है कि लिंक किया गया एम्बेडेड ऑब्जेक्ट प्रेजेंटेशन खुलते या प्रिंट होते समय स्वचालित रूप से अपडेट होता है या नहीं। पढ़ें **bool**। |
| virtual **float** [get_Width](../ishape/get_width/)() | आकृति की चौड़ाई, पॉइंट्स में मापी, प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापी प्राप्त करता है। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापी प्राप्त करता है। पढ़ें **float**। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z-आर्डर में आकृति की स्थिति लौटाता है। Shapes[0] z-आर्डर के पीछे की आकृति लौटाता है, और Shapes[Shapes.Count - 1] सामने की आकृति लौटाता है। केवल पढ़ने योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बेसिक प्लेसहोल्डर आकृति लौटाता है (लेआउट और/या मास्टर स्लाइड से आकृति जो वर्तमान आकृति को विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | आकृति थंबनेल लौटाता है। डिफ़ॉल्ट रूप से [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) आकार थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | आकृति थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समतुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी इंटर्नल डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह आकृति प्लेसहोल्डर नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | आकृति से जुड़ा वैकल्पिक टेक्स्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | आकृति से जुड़ा वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | संपत्ति निर्धारित करती है कि आकृति काले-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगी। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | आकृति की ऊँचाई, पॉइंट्स में मापी, सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि आकृति छुपी है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ‘Mark as decorative’ विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | निर्धारित करता है कि ऑब्जेक्ट आइकन के रूप में दृश्यमान है या नहीं। लिखें **bool**। |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | लिंक की गई फ़ाइल का पूर्ण पथ सेट करता है। लंबा फ़ाइल नाम उपयोग किया जाएगा। लिखें [System::String](../../system/string/)। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | आकृति का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | ऑब्जेक्ट का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | ऑब्जेक्ट का ProgID सेट करता है। केवल पढ़ें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | कच्चे आकृति फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट आकृति के z-अक्ष के चारों ओर घुमाव के डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान प्रतिगामी घुमाव दर्शाता है। लिखें **float**। |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | OleObject आइकन के शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | निर्धारित करता है कि लिंक किया गया एम्बेडेड ऑब्जेक्ट प्रेजेंटेशन खुलते या प्रिंट होते समय स्वचालित रूप से अपडेट होता है या नहीं। लिखें **bool**। |
| virtual void [set_Width](../ishape/set_width/)(**float**) | आकृति की चौड़ाई, पॉइंट्स में मापी, सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | आकृति के ऊपरी-बाएँ कोने के x-निर्देशांक को पॉइंट्स में मापी सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | आकृति के ऊपरी-बाएँ कोने के y-निर्देशांक को पॉइंट्स में मापी सेट करता है। लिखें **float**। |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | OLE एम्बेडेड डेटा के बारे में जानकारी सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मूल्य प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी इंटर्नल डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IGraphicalObject](../igraphicalobject/)
* नेमस्पेस [Aspose::Slides](../)
* Library [Aspose.Slides](../../)