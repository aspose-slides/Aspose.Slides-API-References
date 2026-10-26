---
title: NormalViewProperties
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: "सामान्य दृश्य गुणों का प्रतिनिधित्व करता है। सामान्य दृश्य में तीन सामग्री क्षेत्रों का समुच्चय होता है: स्वयं स्लाइड, एक साइड सामग्री क्षेत्र, और एक नीचे का सामग्री क्षेत्र।"
type: docs
weight: 4525
url: /hi/aspose.slides/normalviewproperties/
---
## NormalViewProperties क्लास

सामान्य दृश्य गुण दर्शाता है। सामान्य दृश्य में तीन सामग्री क्षेत्र होते हैं: स्लाइड स्वयं, एक साइड सामग्री क्षेत्र, और एक नीचे का सामग्री क्षेत्र।

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaNs को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaNs को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | बताता है कि क्षैतिज स्प्लिटर बार किस स्थिति में दिखाया जाना चाहिए। एक क्षैतिज स्प्लिटर बार स्लाइड को स्लाइड के नीचे के सामग्री क्षेत्र से अलग करता है। |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | निर्दिष्ट करता है कि उपयोगकर्ता मानक सामान्य दृश्य में तीन सामग्री क्षेत्रों के बजाय पूर्ण-खिड़की एकल- सामग्री क्षेत्र देखना पसंद करता है या नहीं। यदि सक्षम किया गया, तो एप्लिकेशन पूरे विंडो में किसी एक सामग्री क्षेत्र को प्रदर्शित करना चुन सकता है। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | यह तत्व सामान्य दृश्य के साइड सामग्री क्षेत्र का आकार निर्दिष्ट करता है, जब क्षेत्र का आकार परिवर्ती पुनर्स्थापित आकार (न तो न्यूनतम और न ही अधिकतम) हो। पढ़ें केवल [INormalViewRestoredProperties](../inormalviewrestoredproperties/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | यह तत्व सामान्य दृश्य के शीर्ष स्लाइड क्षेत्र का आकार निर्दिष्ट करता है, जब क्षेत्र का आकार परिवर्ती पुनर्स्थापित आकार (न तो न्यूनतम और न ही अधिकतम) हो। पढ़ें केवल [INormalViewRestoredProperties](../inormalviewrestoredproperties/)। |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | निर्दिष्ट करता है कि सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करने पर एप्लिकेशन को आइकन दिखाने चाहिए या नहीं। पढ़ें **bool**। |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | निर्दिष्ट करता है कि साइड क्षेत्र पर्याप्त छोटा होने पर वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। पढ़ें **bool**। |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | बताता है कि वर्टिकल स्प्लिटर बार किस स्थिति में दिखाया जाना चाहिए। एक वर्टिकल स्प्लिटर बार स्लाइड को साइड सामग्री क्षेत्र से अलग करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानान्तर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानान्तर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन का लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानान्तर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ करती है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशिष्ट कार्यान्वयन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशिष्ट कार्यान्वयन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | बताता है कि क्षैतिज स्प्लिटर बार किस स्थिति में दिखाया जाना चाहिए। एक क्षैतिज स्प्लिटर बार स्लाइड को स्लाइड के नीचे के सामग्री क्षेत्र से अलग करता है। |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | निर्दिष्ट करता है कि उपयोगकर्ता मानक सामान्य दृश्य में तीन सामग्री क्षेत्रों के बजाय पूर्ण-खिड़की एकल- सामग्री क्षेत्र देखना पसंद करता है या नहीं। यदि सक्षम किया गया, तो एप्लिकेशन पूरे विंडो में किसी एक सामग्री क्षेत्र को प्रदर्शित करना चुन सकता है। लिखें **bool**। |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | निर्दिष्ट करता है कि सामान्य दृश्य मोड में किसी भी सामग्री क्षेत्र में रूपरेखा सामग्री प्रदर्शित करने पर एप्लिकेशन को आइकन दिखाने चाहिए या नहीं। लिखें **bool**। |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | निर्दिष्ट करता है कि साइड क्षेत्र पर्याप्त छोटा होने पर वर्टिकल स्प्लिटर को न्यूनतम स्थिति में स्नैप करना चाहिए या नहीं। लिखें **bool**। |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | बताता है कि वर्टिकल स्प्लिटर बार किस स्थिति में दिखाया जाना चाहिए। एक वर्टिकल स्प्लिटर बार स्लाइड को साइड सामग्री क्षेत्र से अलग करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्गुमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानान्तर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणियाँ

निम्न उदाहरण यह दर्शाता है कि PowerPoint [Presentation](../presentation/) की [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/) गुणों को कैसे कॉन्फ़िगर किया जाता है। 
```cpp
// एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाले प्रस्तुति ऑब्जेक्ट को बनाएं
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [INormalViewProperties](../inormalviewproperties/)
* नामस्थान [Aspose::Slides](../)
* लायब्रेरी [Aspose.Slides](../../)