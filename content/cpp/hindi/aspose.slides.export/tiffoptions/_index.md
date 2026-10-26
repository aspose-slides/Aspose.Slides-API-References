---
title: TiffOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रेजेंटेशन को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
weight: 768
url: /hi/aspose.slides.export/tiffoptions/
---
## TiffOptions क्लास


प्रेजेंटेशन को TIFF फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | रंगीन छवि को काली और सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) को [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) पर सेट किया गया हो। पढ़ें [BlackWhiteConversionMode](../blackwhiteconversionmode/)। डिफ़ॉल्ट है [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)। |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | संपीड़न प्रकार निर्दिष्ट करता है। पढ़ें [TiffCompressionTypes](../tiffcompressiontypes/)। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | जब स्रोत फ़ॉन्ट न मिले तो उपयोग किया गया फ़ॉन्ट लौटाता है। पढ़ता है [System::String](../../system/string/)। |
| **uint32_t** [get_DpiX](./get_dpix/)() override | डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्दिष्ट करता है। पढ़ें **uint32_t**। |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | डॉट्स प्रति इंच में वर्टिकल रेज़ोल्यूशन निर्दिष्ट करता है। पढ़ें **uint32_t**। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली लौटाता है। पढ़ें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि छवि आकार प्रस्तुति स्लाइड आकार के आधार पर गणना किया जाएगा। पढ़ें [System::Drawing::Size](../../system.drawing/size/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | निर्यातित दस्तावेज़ में [Ink](../../aspose.slides.ink/) ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [IInkOptions](../iinkoptions/)। |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। पढ़ें [ImagePixelFormat](../imagepixelformat/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रति प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रेजेंटेशन को सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना चाहिए या नहीं, निर्धारित करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। पढ़ें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष है। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष है। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | रंगीन छवि को काली और सफ़ेद छवि में बदलने के लिए एल्गोरिथ्म निर्दिष्ट करता है। यह विकल्प केवल तभी लागू होगा जब [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) को [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) या [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) पर सेट किया गया हो। लिखें [BlackWhiteConversionMode](../blackwhiteconversionmode/)। डिफ़ॉल्ट [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) है। |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | संपीड़न प्रकार निर्दिष्ट करता है। लिखें [TiffCompressionTypes](../tiffcompressiontypes/)। |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | जब स्रोत फ़ॉन्ट न मिले तो उपयोग किया गया फ़ॉन्ट सेट करता है। लिखता है [System::String](../../system/string/)। |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | डॉट्स प्रति इंच में क्षैतिज रेज़ोल्यूशन निर्दिष्ट करता है। लिखें **uint32_t**। |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | डॉट्स प्रति इंच में वर्टिकल रेज़ोल्यूशन निर्दिष्ट करता है। लिखें **uint32_t**। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | उत्पन्न TIFF छवि का आकार निर्दिष्ट करता है। डिफ़ॉल्ट मान 0x0 है, जिसका अर्थ है कि छवि आकार प्रस्तुति स्लाइड आकार के आधार पर गणना किया जाएगा। लिखें [System::Drawing::Size](../../system.drawing/size/)। |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | उत्पन्न छवियों के लिए पिक्सेल फ़ॉर्मेट निर्दिष्ट करता है। लिखें [ImagePixelFormat](../imagepixelformat/)। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रति प्रतिशत में प्रगति अद्यतन सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छुपी स्लाइड्स शामिल हों या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रेजेंटेशन सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ना चाहिए या नहीं, निर्दिष्ट करता है। लिखें **bool**। डिफ़ॉल्ट मान **false** है। |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | प्रेजेंटेशन निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'वें टेम्प्लेट आर्गुमेंट को वीक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [TiffOptions](./tiffoptions/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष है। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनल्यॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टिप्पणी


निम्नलिखित उदाहरण दर्शाता है कि डिफ़ॉल्ट आकार के साथ PowerPoint को TIFF में कैसे परिवर्तित किया जाए। 
```cpp
// एक Presentation ऑब्जेक्ट को बनाता है जो एक प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// प्रेजेंटेशन को TIFF दस्तावेज़ में सहेज रहा है
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
निम्नलिखित उदाहरण दर्शाता है कि कस्टम आकार के साथ PowerPoint को TIFF में कैसे परिवर्तित किया जाए। 
```cpp
// एक Presentation ऑब्जेक्ट को बनाता है जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// TiffOptions क्लास को बनाता है
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// संकुचन प्रकार सेट कर रहा है
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// संकुचन प्रकार
// Default - डिफ़ॉल्ट संकुचन योजना (LZW) को निर्दिष्ट करता है。
// None - कोई संकुचन नहीं दर्शाता है।
// CCITT3
// CCITT4
// LZW
// RLE
// गहराई संकुचन प्रकार पर निर्भर करती है और मैन्युअल रूप से सेट नहीं की जा सकती。
// रेज़ोल्यूशन इकाई हमेशा "2" के बराबर होती है (डॉट्स प्रति इंच) 
// छवि DPI सेट कर रहा है
opts->set_DpiX(200);
opts->set_DpiY(100);
// छवि आकार सेट करें
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Save the presentation to TIFF with specified image size
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
निम्नलिखित उदाहरण दर्शाता है कि कस्टम इमेज पिक्सेल फ़ॉर्मेट के साथ PowerPoint को TIFF में कैसे परिवर्तित किया जाए। 
```cpp
// एक Presentation ऑब्जेक्ट बनाता है जो एक Presentation फ़ाइल का प्रतिनिधित्व करता है
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// निर्दिष्ट छवि आकार के साथ प्रेजेंटेशन को TIFF में सहेजता है
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## संबंधित

* क्लास [SaveOptions](../saveoptions/)
* क्लास [ITiffOptions](../itiffoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)