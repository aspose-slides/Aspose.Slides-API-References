---
title: Html5Options
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 79
url: /hi/aspose.slides.export/html5options/
---
## Html5Options क्लास

Represents a HTML5 exporting options.

```cpp
class Html5Options : public Aspose::Slides::Export::SaveOptions,
                     public Aspose::Slides::Export::IHtml5Options
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) संगतियों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_AnimateShapes](./get_animateshapes/)() override | शेप्स एनीमेशन विकल्प लौटाता है। पढ़ें **bool**। |
| **bool** [get_AnimateTransitions](./get_animatetransitions/)() override | ट्रांज़िशन एनीमेशन विकल्प लौटाता है। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। पढ़ता है [System::String](../../system/string/)। |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | एक मान प्राप्त करता है जो दर्शाता है कि पाठ को लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब इसे **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएँगे। डिफॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| **bool** [get_EmbedImages](./get_embedimages/)() override | छवियों को एम्बेड करने का विकल्प लौटाता है। पढ़ें **bool**। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली लौटाता है। पढ़ता है [GradientStyle](../../aspose.slides/gradientstyle/)। |
| [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() override | निर्धारित करता है कि बाहरी संसाधनों को कहां संग्रहीत किया जाना चाहिए। पढ़ता है [System::String](../../system/string/)। |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | चित्रों के संपीड़न स्तर को दर्शाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ें **bool**। डिफॉल्ट मान **false** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | चेतावनियों को प्राप्त करने वाला और यह निर्णय लेने वाला ऑब्जेक्ट लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ता है [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंसर काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [Html5Options](./html5options/)() | डिफॉल्ट कंस्ट्रक्टर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है वैल्यू प्रकार के ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकृत रूप। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकृत रूप। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AnimateShapes](./set_animateshapes/)(**bool**) override | शेप्स एनीमेशन विकल्प सेट करता है। लिखें **bool**। |
| void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) override | ट्रांज़िशन एनीमेशन विकल्प सेट करता है। लिखें **bool**। |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। लिखता है [System::String](../../system/string/)। |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | पाठ को लिगेचर का प्रयोग किए बिना रेंडर किया जाए या नहीं, दर्शाने वाला मान सेट करता है। जब इसे **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाते हैं। डिफॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| void [set_EmbedImages](./set_embedimages/)(**bool**) override | छवि एम्बेड करने का विकल्प सेट करता है। लिखें **bool**। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) override | निर्धारित करता है कि बाहरी संसाधनों को कहां संग्रहीत किया जाना चाहिए। लिखें [System::String](../../system/string/)। |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | चित्रों के संपीड़न स्तर को दर्शाता है। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। लिखें **bool**। डिफॉल्ट मान **false** है। |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | चेतावनियों को प्राप्त करने वाला और यह तय करने वाला ऑब्जेक्ट लौटाता है या सेट करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक weak पॉइंटर (shared नहीं) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं कॉल किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## टिप्पणी

उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-shapes-and-transitions.html", SaveFormat::Html5, options);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [IHtml5Options](../ihtml5options/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)