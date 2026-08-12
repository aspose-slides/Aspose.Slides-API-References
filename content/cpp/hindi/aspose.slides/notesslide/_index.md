---
title: NotesSlide
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रस्तुतिकरण में नोट्स स्लाइड का प्रतिनिधित्व करता है।
type: docs
weight: 4564
url: /hi/aspose.slides/notesslide/
---
## NotesSlide क्लास


एक प्रस्तुतीकरण में नोट्स स्लाइड का प्रतिनिधित्व करता है।

```cpp
class NotesSlide : public Aspose::Slides::BaseSlide,
                   public Aspose::Slides::INotesSlide
```


## विधियाँ

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | इस स्लाइड के लिए प्रभावी थीम लौटाता है। |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | निर्धारित करता है कि दो [IBaseSlide](../ibaseslide/) इंस्टेंसेज़ समान हैं या नहीं। लौटाया गया मान स्लाइड की संरचना और स्थैतिक सामग्री के आधार पर गणना किया जाता है। दो स्लाइड समान होते हैं यदि सभी आकार, शैलियाँ, पाठ, एनीमेशन और अन्य सेटिंग्स आदि समान हों। तुलना में अद्वितीय पहचानकर्ता मानों को ध्यान में नहीं रखा जाता, जैसे SlideId, तथा गतिशील सामग्री जैसे वर्तमान तिथि मान Date [Placeholder](../placeholder/) में। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantics का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | सिर्फ़ आन्तरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | निर्दिष्ट वैकल्पिक पाठ वाले आकार की पहली उपस्थिति खोजता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | स्लाइड की पृष्ठभूमि लौटाता है। केवल-पढ़ने योग्य [IBackground](../ibackground/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर ActiveX नियंत्रण लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | स्लाइड पर ActiveX नियंत्रणों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IControlCollection](../icontrolcollection/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | स्लाइड का कस्टम डेटा लौटाता है। केवल-पढ़ने योग्य [ICustomData](../icustomdata/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | नोट्स स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | समाहित हाइपरलिंक तक आसान पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IHyperlinkQueries](../ihyperlinkqueries/)। |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | स्लाइड का नाम लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() override | यदि नोट्स का पाठ मौजूद हो तो [TextFrame](../textframe/) लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../itextframe/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() override | पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [ISlide](../islide/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | [IPresentation](../ipresentation/) इंटरफ़ेस लौटाता है। केवल-पढ़ने योग्य [IPresentation](../ipresentation/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | निर्दिष्ट अनुक्रमांक पर आकार लौटाता है। केवल-पढ़ने योग्य [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | स्लाइड के आकारों को लौटाता है। केवल-पढ़ने योग्य [IShapeCollection](../ishapecollection/)। |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाने चाहिए या नहीं। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../ibaseslide/)। |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | स्लाइड का ID लौटाता है। केवल-पढ़ने योग्य **uint32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | ट्रांज़िशन ऑब्जेक्ट लौटाता है जिसमें निर्दिष्ट स्लाइड के स्लाइड शो के दौरान आगे बढ़ने की जानकारी होती है। केवल-पढ़ने योग्य [ISlideShowTransition](../islideshowtransition/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | ओवरराइडिंग थीम प्रबंधक लौटाता है। केवल-पढ़ने योग्य [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | एनीमेशन टाइमलाइन ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IAnimationTimeLine](../ianimationtimeline/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | सभी पैराग्राफ और सभी स्वीकार्य आकारों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | सभी पैराग्राफ और सभी स्वीकार्य आकारों में समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू प्रकार ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट कम करता है। |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | स्लाइड का नाम सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | निर्दिष्ट करता है कि मास्टर स्लाइड पर आकार स्लाइडों पर दिखाने चाहिए या नहीं। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयरड के बजाय) सेट करें। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* वर्ग [BaseSlide](../baseslide/)
* वर्ग [INotesSlide](../inotesslide/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)