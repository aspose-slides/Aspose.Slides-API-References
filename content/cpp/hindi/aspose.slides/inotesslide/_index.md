---
title: INotesSlide
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 3017
url: /hi/aspose.slides/inotesslide/
---
## INotesSlide क्लास

एक प्रस्तुति में नोट्स स्लाइड का प्रतिनिधित्व करता है।

```cpp
class INotesSlide : public virtual Aspose::Slides::IBaseSlide,
                    public Aspose::Slides::Theme::IOverrideThemeable
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | इस themeable ऑब्जेक्ट के लिए प्रभावी थीम को वापस करता है। |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | निर्धारित करता है कि दो [IBaseSlide](../ibaseslide/) इंस्टेंसेस बराबर हैं या नहीं। रिटर्न मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड बराबर हैं यदि सभी shapes, styles, texts, animation और अन्य सेटिंग्स आदि बराबर हों। तुलना में विशिष्ट पहचानकर्ता मान जैसे SlideId और गतिशील सामग्री जैसे Date [Placeholder](../placeholder/) में वर्तमान तिथि मान को ध्यान नहीं दिया जाता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | निर्दिष्ट वैकल्पिक टेक्स्ट वाले shape की पहली उपस्थिति को खोजता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | स्लाइड की पृष्ठभूमि को वापस करता है। केवल-पढ़ने योग्य [IBackground](../ibackground/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | निर्दिष्ट इंडेक्स पर ActiveX नियंत्रण को वापस करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | स्लाइड पर ActiveX नियंत्रणों का संग्रह वापस करता है। केवल-पढ़ने योग्य [IControlCollection](../icontrolcollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | स्लाइड के कस्टम डेटा को वापस करता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | नोट्स स्लाइड के HeaderFooter प्रबंधक को वापस करता है। केवल-पढ़ने योग्य [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | संलग्न हाइपरलिंक्स तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../ihyperlinkqueries/)। |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | स्लाइड के नाम को वापस करता है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() | यदि मौजूद हो तो नोट्स के टेक्स्ट के साथ एक [TextFrame](../textframe/) को वापस करता है। केवल-पढ़ने योग्य [ITextFrame](../itextframe/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() | एक ParentSlide को वापस करता है। केवल-पढ़ने योग्य [ISlide](../islide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | प्रस्तुति को वापस करता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | निर्दिष्ट इंडेक्स पर shape को वापस करता है। केवल-पढ़ने योग्य [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | स्लाइड के shapes को वापस करता है। केवल-पढ़ने योग्य [IShapeCollection](../ishapecollection/)। |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | निर्धारित करता है कि master स्लाइड पर shapes को स्लाइड्स पर दिखाना है या नहीं। master स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड को वापस करता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | स्लाइड का ID वापस करता है। केवल-पढ़ने योग्य **uint32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | TransitionEx ऑब्जेक्ट को वापस करता है जो स्लाइड शो के दौरान निर्दिष्ट स्लाइड के आगे बढ़ने के बारे में जानकारी रखता है। केवल-पढ़ने योग्य [ISlideShowTransition](../islideshowtransition/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | ओवरराइड थीम प्रबंधक को वापस करता है। केवल-पढ़ने योग्य [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | एनीमेशन टाइमलाइन ऑब्जेक्ट को वापस करता है। केवल-पढ़ने योग्य [IAnimationTimeLine](../ianimationtimeline/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट के साथ जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | सभी स्वीकार्य shapes में सभी पैराग्राफ़ों के समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। कुछ भी कॉपी नहीं करता, वास्तव में, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कॉन्स्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ भी कॉपी नहीं करता, वास्तव में, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कॉन्स्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-कम्पेयर करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | स्लाइड का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | निर्धारित करता है कि master स्लाइड पर shapes को स्लाइड्स पर दिखाना है या नहीं। master स्लाइड स्वयं के लिए यह प्रॉपर्टी हमेशा **false** लौटाती है। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-थ टेम्पलेट аргумент को एक weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और उसे लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## देखें भी

* Class [IBaseSlide](../ibaseslide/)
* Class [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)