---
title: GifOptions
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: GIF निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 53
url: /hi/aspose.slides.export/gifoptions/
---
## GifOptions क्लास

GIF निर्यात विकल्पों का प्रतिनिधित्व करता है।

```cpp
class GifOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IGifOptions
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थशास्त्र का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, यहाँ तक कि NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, यहाँ तक कि NaN, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() override | डिफ़ॉल्ट विलंब समय [ms] प्राप्त करता है। यह मूल्य तब उपयोग होगा जब [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) मेथड को नहीं बुलाया गया हो। डिफ़ॉल्ट मान 1000 है। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है। |
| [System::Drawing::Size](../../system.drawing/size/) [get_FrameSize](./get_framesize/)() override | फ़्रेम आकार प्राप्त करता है। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रेज़ेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ने का निर्धारण करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| **int32_t** [get_TransitionFps](./get_transitionfps/)() override | ट्रांज़िशन FPS [फ़्रेम/सेकंड] प्राप्त करता है। डिफ़ॉल्ट मान 25 है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [GifOptions](./gifoptions/)() | [GifOptions](./) क्लास का नया इंस्टैंस प्रारम्भ करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टैंस दर्शाता है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना मूल्य प्रकार ऑब्जेक्ट के साथ nullptr की। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) override | डिफ़ॉल्ट विलंब समय [ms] सेट करता है। यह मूल्य तब उपयोग होगा जब [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) मेथड को नहीं बुलाया गया हो। डिफ़ॉल्ट मान 1000 है। |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाला फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | निर्धारित करता है कि छिपी स्लाइड्स निर्यात की जाएँगी या नहीं। डिफ़ॉल्ट मान false है। |
| void [set_FrameSize](./set_framesize/)([System::Drawing::Size](../../system.drawing/size/)) override | फ़्रेम आकार सेट करता है। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रेज़ेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ने का निर्धारण करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_TransitionFps](./set_transitionfps/)(**int32_t**) override | ट्रांज़िशन FPS [फ़्रेम/सेकंड] सेट करता है। डिफ़ॉल्ट मान 25 है। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता है या सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त हो जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणी

निम्न उदाहरण दिखाता है कि कैसे कस्टम सेटिंग्स का उपयोग करके प्रस्तुतियों को एनीमेटेड GIF में परिवर्तित किया जाए। 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto gifOptions = System::MakeObject<GifOptions>();

gifOptions->set_FrameSize(System::Drawing::Size(960, 720)); // उत्पन्न GIF का आकार
gifOptions->set_DefaultDelay(2000); // प्रत्येक स्लाइड कितनी देर तक दिखेगी जब तक कि वह अगली पर बदली न जाए
gifOptions->set_TransitionFps(35); // बेहतर ट्रांज़िशन एनिमेशन गुणवत्ता के लिए FPS बढ़ाएँ

pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [IGifOptions](../igifoptions/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)