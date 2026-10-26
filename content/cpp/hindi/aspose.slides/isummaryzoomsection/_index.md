---
title: ISummaryZoomSection
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: Summary Zoom फ्रेम में Summary Zoom Section वस्तु का प्रतिनिधित्व करता है।
type: docs
weight: 3927
url: /hi/aspose.slides/isummaryzoomsection/
---
## ISummaryZoomSection क्लास


एक Summary Zoom [Section](../section/) वस्तु को Summary Zoom फ्रेम में दर्शाता है।

```cpp
class ISummaryZoomSection : public virtual Aspose::Slides::ISectionZoomFrame
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | यदि कोई placeholder नहीं है तो नया placeholder जोड़ता है और placeholder गुणों को निर्दिष्ट वाले पर सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | एक shape से जुड़ा वैकल्पिक पाठ लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | एक shape से जुड़ा वैकल्पिक पाठ का शीर्षक लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | यह प्रॉपर्टी निर्धारित करती है कि shape काली-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। पढ़ें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | shape पर कनेक्शन साइटों की संख्या लौटाता है। केवल-पढ़ने-योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | shape का कस्टम डेटा लौटाता है। केवल-पढ़ने-योग्य [ICustomData](../icustomdata/)। |
| virtual [System::String](../../system/string/) [get_Description](./get_description/)() | Summary Zoom [Section](../section/) वस्तु का पाठ विवरण लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) वस्तु लौटाता है जिसमें shape पर लागू पिक्सल इफ़ेक्ट्स होते हैं। केवल-पढ़ने-योग्य [IEffectFormat](../ieffectformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) वस्तु लौटाता है जिसमें shape के लिए फ़िल फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने-योग्य [IFillFormat](../ifillformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | shape फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | shape के लॉक लौटाता है। केवल-पढ़ने-योग्य [IGraphicalObjectLock](../igraphicalobjectlock/)। |
| virtual **float** [get_Height](../ishape/get_height/)() | shape की ऊँचाई प्राप्त करता है, जो पॉइंट में मापी गई है। पढ़ें **float**। |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | निर्धारित करता है कि shape छिपा हुआ है या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | माउस क्लिक के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | हाइपरलिंक प्रबंधक। केवल-पढ़ने-योग्य [IHyperlinkManager](../ihyperlinkmanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | माउस ओवर के लिए परिभाषित हाइपरलिंक लौटाता है। पढ़ें [IHyperlink](../ihyperlink/)। |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | zoom वस्तु की इमेज टाइप प्राप्त करता है। पढ़ें [ZoomImageType](../zoomimagetype/)। डिफ़ॉल्ट मान: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' विकल्प प्राप्त करता है। पढ़ें/लिखें **bool**। |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | निर्धारित करता है कि shape समूहित है या नहीं। केवल-पढ़ने-योग्य **bool**। |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | निर्धारित करता है कि shape TextHolder है या नहीं। केवल-पढ़ने-योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) वस्तु लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने-योग्य [ILineFormat](../ilineformat/)। |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | shape का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | एक slide-स्कोप्ड यूनिक पहचानकर्ता लौटाता है जो shape के जीवनकाल में स्थिर रहता है और PowerPoint या इंटरऑप कोड को दस्तावेज़ में कहीं से भी shape को विश्वसनीय रूप से संदर्भित करने देता है। केवल-पढ़ने-योग्य **uint32_t**। देखें [IShape::get_UniqueId](../ishape/get_uniqueid/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | यदि shape समूहित है तो पैरेंट [GroupShape](../groupshape/) वस्तु लौटाता है। अन्यथा null लौटाता है। केवल-पढ़ने-योग्य [IGroupShape](../igroupshape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | shape के लिए placeholder लौटाता है। केवल-पढ़ने-योग्य [IPlaceholder](../iplaceholder/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | presentation लौटाता है। केवल-पढ़ने-योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | raw shape फ्रेम की प्रॉपर्टीज़ लौटाता है। पढ़ें [IShapeFrame](../ishapeframe/)। |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | slideshow में नेविगेशन व्यवहार प्राप्त करता है। पढ़ें **bool**। डिफ़ॉल्ट मान: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | निर्दिष्ट shape के z-axis के चारों ओर घूर्णन डिग्री की संख्या लौटाता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगामी घूर्णन दर्शाता है। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | shape के लॉक लौटाता है। केवल-पढ़ने-योग्य [IBaseShapeLock](../ibaseshapelock/)। |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Zoom द्वारा लक्ष्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा या नहीं, इसे दर्शाने वाला मान प्राप्त करता है। पढ़ें **bool**। डिफ़ॉल्ट मान: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने-योग्य [IBaseSlide](../ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../isectionzoomframe/get_targetsection/)() | [Section](../section/) Zoom वस्तु जिस सेक्शन ऑब्जेक्ट से जुड़ी है, उसे प्राप्त करता है। पढ़ें [ISection](../isection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) वस्तु लौटाता है जिसमें shape के लिए लाइन फ़ॉर्मेटिंग प्रॉपर्टीज़ होते हैं। केवल-पढ़ने-योग्य [IThreeDFormat](../ithreedformat/)। |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Summary Zoom [Section](../section/) वस्तु का टेक्स्ट शीर्षक लौटाता है। |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Zoom और स्लाइड के बीच संक्रमण की अवधि प्राप्त करता है। पढ़ें **float**। डिफ़ॉल्ट मान: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | एक आंतरिक, presentation-स्कोप्ड पहचानकर्ता लौटाता है जिसका उपयोग ऐड-इन या अन्य कोड द्वारा किया जाता है। क्योंकि यह मान उपयोगकर्ता या प्रोग्राम द्वारा पुनः सौंपा जा सकता है, इसे स्थायी यूनिक कुंजी के रूप में नहीं माना जाना चाहिए। केवल-पढ़ने-योग्य **uint32_t**। देखें [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)। |
| virtual **float** [get_Width](../ishape/get_width/)() | shape की चौड़ाई प्राप्त करता है, जो पॉइंट में मापी जाती है। पढ़ें **float**। |
| virtual **float** [get_X](../ishape/get_x/)() | shape के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| virtual **float** [get_Y](../ishape/get_y/)() | shape के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को प्राप्त करता है, पॉइंट में मापी गई। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | zoom वस्तु के लिए इमेज प्राप्त करता है। पढ़ें [IPPImage](../ippimage/)। |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | shape की z-order में स्थिति लौटाता है। Shapes[0] z-order के पीछे का shape लौटाता है, और Shapes[Shapes.Count - 1] z-order के सामने का shape लौटाता है। केवल-पढ़ने-योग्य **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | एक बेसिक placeholder shape लौटाता है (layout और/या master slide से shape जो वर्तमान shape से विरासत में मिला है)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | shape थंबनेल लौटाता है। डिफ़ॉल्ट रूप में [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape थंबनेल बाउंड्स टाइप उपयोग किया जाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | shape थंबनेल लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि वस्तु targetType द्वारा वर्णित प्रकार की instance है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने को सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | परिभाषित करता है कि यह shape placeholder नहीं है। |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | shape से जुड़ा वैकल्पिक पाठ सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | shape से जुड़ा वैकल्पिक पाठ का शीर्षक सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | प्रॉपर्टी निर्धारित करती है कि shape काली-और-सफ़ेद डिस्प्ले मोड में कैसे रेंडर होगा। लिखें [Slides::BlackWhiteMode](../blackwhitemode/)। |
| virtual void [set_Description](./set_description/)([System::String](../../system/string/)) | Summary Zoom [Section](../section/) वस्तु का पाठ विवरण लौटाता है। |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | shape फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_Height](../ishape/set_height/)(**float**) | shape की ऊँचाई पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | निर्धारित करता है कि shape छिपा हुआ है या नहीं। लिखें **bool**। |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस क्लिक के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | माउस ओवर के लिए परिभाषित हाइपरलिंक सेट करता है। लिखें [IHyperlink](../ihyperlink/)। |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | zoom वस्तु की इमेज टाइप सेट करता है। लिखें [ZoomImageType](../zoomimagetype/)। डिफ़ॉल्ट मान: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' विकल्प सेट करता है। पढ़ें/लिखें **bool**। |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | shape का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | raw shape फ्रेम की प्रॉपर्टीज़ सेट करता है। लिखें [IShapeFrame](../ishapeframe/)। |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | slideshow में नेविगेशन व्यवहार सेट करता है। लिखें **bool**। डिफ़ॉल्ट मान: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | निर्दिष्ट shape को z-axis के चारों ओर घुमाए जाने वाले डिग्री की संख्या सेट करता है। सकारात्मक मान घड़ी की दिशा में घूर्णन दर्शाता है; नकारात्मक मान प्रतिगामी घूर्णन दर्शाता है। लिखें **float**। |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Zoom द्वारा लक्ष्य स्लाइड की पृष्ठभूमि का उपयोग किया जाएगा या नहीं, यह दर्शाने वाला मान सेट करता है। लिखें **bool**। डिफ़ॉल्ट मान: true |
| virtual void [set_TargetSection](../isectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | [Section](../section/) Zoom वस्तु जिस सेक्शन ऑब्जेक्ट से जुड़ी है, उसे सेट करता है। लिखें [ISection](../isection/)। |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Summary Zoom [Section](../section/) वस्तु का टेक्स्ट शीर्षक लौटाता है। |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Zoom और स्लाइड के बीच संक्रमण की अवधि सेट करता है। लिखें **float**। डिफ़ॉल्ट मान: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | shape की चौड़ाई पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_X](../ishape/set_x/)(**float**) | shape के ऊपरी-बाएँ कोने के x-कोऑर्डिनेट को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_Y](../ishape/set_y/)(**float**) | shape के ऊपरी-बाएँ कोने के y-कोऑर्डिनेट को पॉइंट में सेट करता है। लिखें **float**। |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | zoom वस्तु के लिए इमेज सेट करता है। लिखें [IPPImage](../ippimage/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट तर्क को weak पॉइंटर सेट करता है (shared नहीं)। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) की सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें भी

* क्लास [ISectionZoomFrame](../isectionzoomframe/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)