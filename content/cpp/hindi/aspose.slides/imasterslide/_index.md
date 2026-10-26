---
title: IMasterSlide
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन में एक मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 2926
url: /hi/aspose.slides/imasterslide/
---
## IMasterSlide वर्ग

प्रेजेंटेशन में एक मास्टर स्लाइड का प्रतिनिधित्व करता है।

```cpp
class IMasterSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IMasterThemeable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](./)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) | वर्तमान स्लाइड पर आधारित एक नई मास्टर स्लाइड बनाता है, उस पर एक बाहरी थीम लागू करता है और बनाई गई मास्टर स्लाइड को सभी निर्भर स्लाइड्स पर लागू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | इस थीम योग्य वस्तु के लिए प्रभावी थीम लौटाता है। |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | निर्धारित करता है कि दो [IBaseSlide](../ibaseslide/) इंस्टेंस समान हैं या नहीं। लौटाई गई मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना की जाती है। दो स्लाइड समान होती हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मूल्यों, जैसे SlideId, तथा गतिशील सामग्री, जैसे वर्तमान तिथि मान Date [Placeholder](../placeholder/) को ध्यान में नहीं रखा जाता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली घटना ढूँढता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | स्लाइड की पृष्ठभूमि लौटाता है। केवल पढ़ने योग्य [IBackground](../ibackground/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() | बॉडी टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [ITextStyle](../itextstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | निर्दिष्ट सूचकांक पर ActiveX कंट्रोल लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | स्लाइड पर ActiveX कंट्रोल्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IControlCollection](../icontrolcollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | स्लाइड का कस्टम डेटा लौटाता है। केवल पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | मास्टर स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | यदि इस मास्टर स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। केवल पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | मास्टर स्लाइड के HeaderFooter प्रबंधक को लौटाता है। केवल पढ़ने योग्य [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | समाहित हाइपरलिंक्स तक आसान पहुँच प्रदान करता है। केवल पढ़ने योग्य [IHyperlinkQueries](../ihyperlinkqueries/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | निर्दिष्ट सूचकांक पर इस मास्टर स्लाइड के लिए चाइल्ड लेआउट स्लाइड लौटाता है। केवल पढ़ने योग्य [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | इस मास्टर स्लाइड के चाइल्ड लेआउट स्लाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)। |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | स्लाइड का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() | अन्य टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [ITextStyle](../itextstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual **bool** [get_Preserve](./get_preserve/)() | निर्धारित करता है कि सभी स्लाइड्स जो उस मास्टर के बाद आती हैं, हटाए जाने पर संबंधित मास्टर हटाया जाता है या नहीं। नोट: [Aspose.Slides](../) स्वयं कोई भी अनउपयोगित मास्टर नहीं हटाएगा, वास्तव में अनउपयोगित मास्टर को हटाने के लिए [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) कॉल करें पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | निर्दिष्ट सूचकांक पर आकार लौटाता है। केवल पढ़ने योग्य [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | स्लाइड के आकार लौटाता है। केवल पढ़ने योग्य [IShapeCollection](../ishapecollection/)। |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकारों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। स्वयं मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | स्लाइड का आईडी लौटाता है। केवल पढ़ने योग्य **uint32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | TransitionEx ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड के स्लाइड शो के दौरान कैसे आगे बढ़ता है, इसकी जानकारी होती है। केवल पढ़ने योग्य [ISlideShowTransition](../islideshowtransition/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | मास्टर थीम प्रबंधक लौटाता है। केवल पढ़ने योग्य [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य [IAnimationTimeLine](../ianimationtimeline/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() | टाइटल टेक्स्ट की शैली लौटाता है। केवल पढ़ने योग्य [ITextStyle](../itextstyle/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | एक एरे लौटाता है जिसमें सभी स्लाइड्स होते हैं, जो इस मास्टर स्लाइड पर निर्भर हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ों में समान फॉर्मेटिंग वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करना सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | स्लाइड का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_Preserve](./set_preserve/)(**bool**) | निर्धारित करता है कि सभी स्लाइड्स जो उस मास्टर के बाद आती हैं, हटाए जाने पर संबंधित मास्टर हटाया जाता है या नहीं। नोट: [Aspose.Slides](../) स्वयं कोई भी अनउपयोगित मास्टर नहीं हटाएगा, वास्तव में अनउपयोगित मास्टर को हटाने के लिए [IMasterSlideCollection::RemoveUnused](../imasterslidecollection/removeunused/) कॉल करें लिखें **bool**। |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकारों को स्लाइड्स पर दिखाया जाना चाहिए या नहीं। स्वयं मास्टर स्लाइड के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके अलावा, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [IBaseSlide](../ibaseslide/)
* क्लास [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)