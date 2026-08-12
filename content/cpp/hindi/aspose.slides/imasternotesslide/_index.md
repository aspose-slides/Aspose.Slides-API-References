---
title: IMasterNotesSlide
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 2887
url: /hi/aspose.slides/imasternotesslide/
---
## IMasterNotesSlide क्लास


प्रस्तुति नोट्स के लिए मास्टर स्लाइड का प्रतिनिधित्व करता है।

```cpp
class IMasterNotesSlide : public virtual Aspose::Slides::IBaseSlide,
                          public Aspose::Slides::Theme::IMasterThemeable
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | इस थीम योग्य वस्तु के लिए प्रभावी थीम लौटाता है। |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | निर्धारित करता है कि दो [IBaseSlide](../ibaseslide/) उदाहरण समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड्स समान होती हैं यदि सभी आकार, शैलियाँ, टेक्स्ट, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मान, जैसे SlideId, और गतिशील सामग्री, जैसे Date [Placeholder](../placeholder/) में वर्तमान तिथि मान, को ध्यान में नहीं रखा जाता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले आकार की पहली उपस्थिति को खोजता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पठन [IBackground](../ibackground/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | निर्दिष्ट अनुक्रमांक पर ActiveX कंट्रोल लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | स्लाइड पर ActiveX नियंत्रणों के संग्रह को लौटाता है। केवल-पठन [IControlCollection](../icontrolcollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | स्लाइड का कस्टम डेटा लौटाता है। केवल-पठन [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | मास्टर नोट्स स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल-पठन [IDrawingGuidesCollection](../idrawingguidescollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | मास्टर नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पठन [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | निहित हाइपरलिंक्स तक आसान पहुँच प्रदान करता है। केवल-पठन [IHyperlinkQueries](../ihyperlinkqueries/)। |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | स्लाइड का नाम लौटाता है। केवल-पठन [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_NotesStyle](./get_notesstyle/)() | नोट्स टेक्स्ट की शैली लौटाता है। केवल-पठन [ITextStyle](../itextstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पठन [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | निर्दिष्ट अनुक्रमांक पर आकार लौटाता है। केवल-पठन [Aspose::Slides::IShape](../ishape/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | स्लाइड के आकार लौटाता है। केवल-पठन [IShapeCollection](../ishapecollection/)। |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | निर्धारित करता है कि क्या मास्टर स्लाइड पर आकार स्लाइड्स पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह गुण हमेशा **false** लौटाता है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पठन [IBaseSlide](../ibaseslide/)। |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | स्लाइड की आईडी लौटाता है। केवल-पठन **uint32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | TransitionEx ऑब्जेक्ट लौटाता है जो यह जानकारी सम्मिलित करता है कि स्लाइड शो के दौरान निर्दिष्ट स्लाइड कैसे आगे बढ़ती है। केवल-पठन [ISlideShowTransition](../islideshowtransition/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | मास्टर थीम प्रबंधक लौटाता है। केवल-पठन [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पठन [IAnimationTimeLine](../ianimationtimeline/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | सभी स्वीकार्य आकारों में सभी पैराग्राफ़ों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | स्लाइड का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | निर्धारित करता है कि क्या मास्टर स्लाइड पर आकार स्लाइड्स पर दिखाए जाने चाहिए या नहीं। मास्टर स्लाइड के लिए यह गुण हमेशा **false** लौटाता है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-थ टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें भी

* वर्ग [IBaseSlide](../ibaseslide/)
* वर्ग [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)