---
title: MarkdownSaveOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 547
url: /hi/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions क्लास

प्रस्तुति को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों का प्रतिनिधित्व करता है।

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर मान लिया जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर मान लिया जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | संसाधनों वाले दस्तावेज़ को सहेजने के लिए बेस पाथ निर्दिष्ट करता है। डिफ़ॉल्ट वर्तमान एप्लिकेशन निर्देशिका है। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देशन निर्दिष्ट करता है। डिफ़ॉल्ट **TextOnly** है। |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देशन निर्दिष्ट करता है। डिफ़ॉल्ट **Multi-markdown** है। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | मार्कडाउन निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | इमेज सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट **[Images](../../aspose.slides/images/)** है। |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \r(मैकोज़) या \n(यूनिक्स) या \r\n(विंडोज) होनी चाहिए या नहीं। डिफ़ॉल्ट **Unix** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रतिशत में प्रगति अपडेट को सहेजने के लिए कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | यदि **true** सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल व्हाइटस्पेस वाली पंक्तियों को हटा देता है। डिफ़ॉल्ट **false** है। |
| **bool** [get_ShowComments](./get_showcomments/)() const | निर्धारित करता है कि उत्पन्न दस्तावेज़ में टिप्पणियाँ दिखाई दें या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी हुई स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाए या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना चाहिए या नहीं, निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | मार्कडाउन आउटपुट में स्लाइड नंबर हेडर के लिए प्रयुक्त फ़ॉर्मेट स्ट्रिंग प्राप्त करता है। फ़ॉर्मेट में \"{0}\" प्लेसहोल्डर होना चाहिए, जिसे निर्यात के दौरान स्लाइड इंडेक्स से बदल दिया जाएगा। उदाहरण: \"# Slide {0}\" \"# Slide 1\", \"# Slide 2\" आदि उत्पन्न करेगा। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | कंस्ट्रक्टर। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस को nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | संसाधनों वाले दस्तावेज़ को सहेजने के लिए बेस पाथ निर्दिष्ट करता है। डिफ़ॉल्ट वर्तमान एप्लिकेशन निर्देशिका है। |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देशन निर्दिष्ट करता है। डिफ़ॉल्ट **TextOnly** है। |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विनिर्देशन निर्दिष्ट करता है। डिफ़ॉल्ट **Multi-markdown** है। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | मार्कडाउन निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | इमेज सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट **[Images](../../aspose.slides/images/)** है। |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \r(मैकोज़) या \n(यूनिक्स) या \r\n(विंडोज) होनी चाहिए या नहीं। डिफ़ॉल्ट **Unix** है। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रतिशत में प्रगति अपडेट को सहेजने के लिए कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | यदि **true** सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल व्हाइटस्पेस वाली पंक्तियों को हटा देता है। डिफ़ॉल्ट **false** है। |
| void [set_ShowComments](./set_showcomments/)(**bool**) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में टिप्पणियाँ दिखाई दें या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी हुई स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाए या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना चाहिए या नहीं, निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | मार्कडाउन आउटपुट में स्लाइड नंबर हेडर के लिए प्रयुक्त फ़ॉर्मेट स्ट्रिंग सेट करता है। फ़ॉर्मेट में \"{0}\" प्लेसहोल्डर होना चाहिए, जिसे निर्यात के दौरान स्लाइड इंडेक्स से बदल दिया जाएगा। उदाहरण: \"# Slide {0}\" \"# Slide 1\", \"# Slide 2\" आदि उत्पन्न करेगा। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर किया हुआ नहीं) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Markdown निर्यात के दौरान प्रत्येक non-SVG इमेज (बिटमैप या मेटाफाइल) के लिए बुलाया जाता है।  
निर्दिष्ट *link* उपयोग करने के लिए **true** लौटाएँ,  
या डिफ़ॉल्ट सेविंग लॉजिक लागू करने के लिए **false**। |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Markdown निर्यात के दौरान प्रत्येक SVG इमेज के लिए बुलाया जाता है।  
निर्दिष्ट *link* उपयोग करने के लिए **true** लौटाएँ,  
या डिफ़ॉल्ट सेविंग लॉजिक लागू करने के लिए **false**। |

## टिप्पणी

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)