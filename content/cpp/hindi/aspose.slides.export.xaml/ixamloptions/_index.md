---
title: IXamlOptions
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: विकल्प जो नियंत्रित करते हैं कि XAML दस्तावेज़ कैसे सहेजा जाता है।
type: docs
weight: 1
url: /hi/aspose.slides.export.xaml/ixamloptions/
---
## IXamlOptions क्लास

Options that control how a XAML document is saved.

```cpp
class IXamlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/isaveoptions/get_defaultregularfont/)() | फ़ॉन्ट लौटाता है जो स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() | निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात की जाएँगी या नहीं। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की दृश्य शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() | IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अद्यतन सहेजने के लिए कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| virtual **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/get_skipjavascriptlinks/)() | प्रस्तुति सहेजते समय JavaScript कॉल वाले हायपरलिंक्स को छोड़ना है या नहीं निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और यह तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को कम करता है। |
| virtual void [set_DefaultRegularFont](../../aspose.slides.export/isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | फ़ॉन्ट सेट करता है जो स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) | निर्धारित करता है कि छिपी हुई स्लाइड्स निर्यात की जाएँगी या नहीं। |
| virtual void [set_GradientStyle](../../aspose.slides.export/isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की दृश्य शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| virtual void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) | IOutputSaver इंटरफ़ेस का कार्यान्वयन दर्शाता है। |
| virtual void [set_ProgressCallback](../../aspose.slides.export/isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अद्यतन सहेजने के लिए कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| virtual void [set_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रस्तुति सहेजते समय JavaScript कॉल वाले हायपरलिंक्स को छोड़ना है या नहीं निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_WarningCallback](../../aspose.slides.export/isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और यह तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक विकी पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को विकी मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | विकी रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | विकी रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणियाँ

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## संबंधित देखें

* क्लास [ISaveOptions](../../aspose.slides.export/isaveoptions/)
* नेमस्पेस [Aspose::Slides::Export::Xaml](../)
* लाइब्रेरी [Aspose.Slides](../../)