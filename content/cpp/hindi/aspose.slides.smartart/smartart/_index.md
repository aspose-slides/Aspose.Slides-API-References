---
title: SmartArt
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक SmartArt आरेख का प्रतिनिधित्व करता है
type: docs
weight: 66
url: /hi/aspose.slides.smartart/smartart/
---
## SmartArt क्लास

एक [SmartArt](./) आरेख का प्रतिनिधित्व करता है

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | यदि कोई नहीं है तो नया प्लेसहोल्डर जोड़ता है और प्लेसहोल्डर गुणों को निर्दिष्ट वाले में सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, बावजूद इसके कि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, बावजूद इसके कि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | [SmartArt](./) ऑब्जेक्ट में सभी नोड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../ismartartnodecollection/)। |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | एक आकार से जुड़े वैकल्पिक टेक्स्ट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | एक आकार से जुड़े वैकल्पिक टेक्स्ट का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | प्रॉपर्टी निर्धारित करती है कि एक आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | [SmartArt](./) ऑब्जेक्ट की रंग शैली को लौटाता है। पढ़ें [SmartArtColorType](../smartartcolortype/)। |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | आकार पर कनेक्शन साइटों की संख्या को लौटाता है। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | आकार का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../../aspose.slides/icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | [EffectFormat](../../aspose.slides/effectformat/) ऑब्जेक्ट को लौटाता है जिसमें आकार पर लागू पिक्सेल इफ़ेक्ट्स होते हैं। नोट: कुछ प्रकार के आकार जिनमें इफ़ेक्ट प्रॉपर्टी नहीं होती, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IEffectFormat](../../aspose.slides/ieffectformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) ऑब्जेक्ट को लौटाता है जिसमें आकार के लिए भराव फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। नोट: कुछ प्रकार के आकार जिनमें भराव प्रॉपर्टी नहीं होती, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IFillFormat](../../aspose.slides/ifillformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | आकार के लॉक को लौटाता है। केवल-पढ़ने योग्य [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)। |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | आकार की ऊँचाई (पॉइंट्स में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | निर्धारित करता है कि आकार छिपा है या नहीं। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | माउस क्लिक के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | हाइपरलिंक मैनेजर को लौटाता है। केवल-पढ़ने योग्य [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | माउस ओवर के लिए परिभाषित हाइपरलिंक को लौटाता है। पढ़ें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | निर्धारित करता है कि आकार समूहित है या नहीं। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_IsReversed](./get_isreversed/)() override | [SmartArt](./) डायग्राम की स्थिति को (बाएँ से दाएँ) LTR या (दाएँ से बाएँ) RTL के संबंध में लौटाता या सेट करता है, यदि डायग्राम उलटने का समर्थन करता है। पढ़ें **bool**। |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | निर्धारित करता है कि आकार TextHolder_PPT है या नहीं। केवल-पढ़ने योग्य **bool**। |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | [SmartArt](./) ऑब्जेक्ट का लेआउट लौटाता है। पढ़ें [SmartArtLayoutType](../smartartlayouttype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | एक आकार के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ वाले [LineFormat](../../aspose.slides/lineformat/) ऑब्जेक्ट को लौटाता है। नोट: कुछ प्रकार के आकार जिनमें लाइन प्रॉपर्टी नहीं होती, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [ILineFormat](../../aspose.slides/ilineformat/)। |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | एक आकार का नाम लौटाता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर [SmartArt](./) ऑब्जेक्ट में मूल नोड्स के संग्रह से एक नोड लौटाता है। केवल-पढ़ने योग्य [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर [SmartArt](./) ऑब्जेक्ट में सभी नोड्स के संग्रह से एक नोड लौटाता है। केवल-पढ़ने योग्य [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | [SmartArt](./) ऑब्जेक्ट में मूल नोड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../ismartartnodecollection/)। |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | एक स्लाइड-स्कोप्ड यूनिक आइडेंटिफ़ायर लौटाता है जो आकार के जीवनकाल के दौरान स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी आकार का विश्वसनीय संदर्भ देता है। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | यदि आकार समूहित है तो पैरेंट [GroupShape](../../aspose.slides/groupshape/) ऑब्जेक्ट लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने योग्य [IGroupShape](../../aspose.slides/igroupshape/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | एक आकार के लिए प्लेसहोल्डर लौटाता है। यदि आकार में कोई प्लेसहोल्डर नहीं है तो null लौटाता है। केवल-पढ़ने योग्य [IPlaceholder](../../aspose.slides/iplaceholder/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | [SmartArt](./) ऑब्जेक्ट की क्विक स्टाइल लौटाता है। पढ़ें [SmartArtQuickStyleType](../smartartquickstyletype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | निर्दिष्ट आकार के z-एक्सिस के चारों ओर घुमाव के डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घुमाव दर्शाता है; नकारात्मक मान विपरीत दिशा में घुमाव दर्शाता है। पढ़ें **float**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | आकार के लॉक को लौटाता है। केवल-पढ़ने योग्य [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | एक आकार की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | एक आकार के 3D इफ़ेक्ट प्रॉपर्टीज़ वाला [ThreeDFormat](../../aspose.slides/threedformat/) ऑब्जेक्ट लौटाता है। नोट: कुछ आकार जिनमें 3D प्रॉपर्टी नहीं होती, उनके लिए null लौट सकता है। केवल-पढ़ने योग्य [IThreeDFormat](../../aspose.slides/ithreedformat/)। |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | एक आंतरिक, प्रस्तुति-स्कोप्ड आइडेंटिफ़ायर लौटाता है जिसका उपयोग एड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुन: असाइन किया जा सकता है, इसे स्थायी यूनिक कुंजी नहीं माना जाना चाहिए। केवल-पढ़ने योग्य **uint32_t**। देखें [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)। |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | आकार की चौड़ाई (पॉइंट्स में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | आकार के ऊपर-बाएँ कोने का x-निर्देशांक (पॉइंट्स में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | आकार के ऊपर-बाएँ कोने का y-निर्देशांक (पॉइंट्स में मापी गई) प्राप्त करता है। पढ़ें **float**। |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | z-ऑर्डर में आकार की स्थिति लौटाता है। Shapes[0] पीछे के आकार को लौटाता है, और Shapes[Shapes.Count - 1] आगे के आकार को। केवल-पढ़ने योग्य **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | एक बेसिक प्लेसहोल्डर आकार लौटाता है (लेआउट या मास्टर स्लाइड से आने वाला आकार जिसे वर्तमान आकार ने विरासत में प्राप्त किया है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान है। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | आकार थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) आकार थंबनेल बाउंड्स प्रकार उपयोग किया जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | आकार थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान है। |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | रेंडर की गई सामग्री से गणना किए गए आकार की दृश्य सीमाओं को प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग के मामले के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | परिभाषित करता है कि यह आकार प्लेसहोल्डर नहीं है। |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | एक आकार से जुड़े वैकल्पिक टेक्स्ट को सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | एक आकार से जुड़े वैकल्पिक टेक्स्ट का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | प्रॉपर्टी निर्धारित करती है कि आकार ब्लैक-एंड-व्हाइट डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)। |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | [SmartArt](./) ऑब्जेक्ट की रंग शैली सेट करता है। लिखें [SmartArtColorType](../smartartcolortype/)। |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | आकार की ऊँचाई (पॉइंट्स में) सेट करता है। लिखें **float**। |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | निर्धारित करता है कि आकार छिपा है या नहीं। लिखें **bool**। |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../../aspose.slides/ihyperlink/)। |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | [SmartArt](./) डायग्राम की स्थिति को (LTR/RTL) लौटाता या सेट करता है, यदि डायग्राम उलटने का समर्थन करता है। लिखें **bool**। |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | [SmartArt](./) ऑब्जेक्ट का लेआउट सेट करता है। लिखें [SmartArtLayoutType](../smartartlayouttype/)। |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | एक आकार का नाम सेट करता है। यह null नहीं होना चाहिए। आवश्यक होने पर खाली स्ट्रिंग का उपयोग करें। लिखें [System::String](../../system/string/)। |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | [SmartArt](./) ऑब्जेक्ट की क्विक स्टाइल सेट करता है। लिखें [SmartArtQuickStyleType](../smartartquickstyletype/)। |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | कच्चे आकार फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../../aspose.slides/ishapeframe/)। |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | निर्दिष्ट आकार के z-एक्सिस के चारों ओर घुमाव के डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में, नकारात्मक मान विपरीत दिशा में। लिखें **float**। |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | आकार की चौड़ाई (पॉइंट्स में) सेट करता है। लिखें **float**। |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | आकार के ऊपर-बाएँ कोने का x-निर्देशांक (पॉइंट्स में) सेट करता है। लिखें **float**। |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | आकार के ऊपर-बाएँ कोने का y-निर्देशांक (पॉइंट्स में) सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को शेयर्ड के बजाय वीके पॉइंटर सेट करता है। कंटेनर्स में पॉइंटर्स को वीके मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीके रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीके रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [GraphicalObject](../../aspose.slides/graphicalobject/)
* क्लास [ISmartArt](../ismartart/)
* नेमस्पेस [Aspose::Slides::SmartArt](../)
* लाइब्रेरी [Aspose.Slides](../../)