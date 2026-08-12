---
title: XpsOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति XPS स्वरूप में कैसे सहेजी जाती है।
type: docs
weight: 807
url: /hi/aspose.slides.export/xpsoptions/
---
## XpsOptions क्लास


विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति XPS प्रारूप में कैसे सहेजी जाती है।

```cpp
class XpsOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IXpsOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, जिसमें NaN भी शामिल है, के बराबर नहीं है, फिर भी दो NaN को समान मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, जिसमें NaN भी शामिल है, के बराबर नहीं है, फिर भी दो NaN को समान मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true. **bool** पढ़ें। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रगति अद्यतन को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG चित्रों में बदलने के लिए true। **bool** पढ़ें। |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज में छिपी स्लाइडें शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और यह तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true. **bool** लिखें। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रगति अद्यतन को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | प्रस्तुति में उपयोग किए गए सभी मेटा फ़ाइलों को PNG चित्रों में बदलने के लिए true. **bool** लिखें। |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज में छिपी स्लाइडें शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, यह निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और यह तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर किए हुए रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर किए हुए रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर किए हुए रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [XpsOptions](./xpsoptions/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टिप्पणी


निम्न उदाहरण दिखाता है कि डिफ़ॉल्ट सेटिंग्स का उपयोग करके प्रस्तुतियों को XPS में कैसे परिवर्तित किया जाए। 
```cpp
// एक Presentation ऑब्जेक्ट को instantiate करें जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
auto pres = System::MakeObject<Presentation>(u"Convert_XPS.pptx");

// प्रस्तुति को XPS दस्तावेज़ में सहेज रहा है
pres->Save(u"XPS_Output_Without_XPSOption_out.xps", SaveFormat::Xps);
```
निम्न उदाहरण दिखाता है कि कस्टम सेटिंग्स का उपयोग करके प्रस्तुतियों को XPS में कैसे परिवर्तित किया जाए। 
```cpp
// एक Presentation ऑब्जेक्ट को instantiate करें जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
auto pres = System::MakeObject<Presentation>(u"Convert_XPS_Options.pptx");

// TiffOptions क्लास को instantiate करें
System::SharedPtr<XpsOptions> options = System::MakeObject<XpsOptions>();
// MetaFiles को PNG के रूप में सहेजें
options->set_SaveMetafilesAsPng(true);
// प्रस्तुति को XPS दस्तावेज़ में सहेजें
pres->Save(u"XPS_With_Options_out.xps", SaveFormat::Xps, options);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [IXpsOptions](../ixpsoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)