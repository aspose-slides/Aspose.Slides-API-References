---
title: IHtml5Options
second_title: Aspose.Slides for C++ एपीआई रेफ़रेंस
description: HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 170
url: /hi/aspose.slides.export/ihtml5options/
---
## IHtml5Options क्लास


HTML5 निर्यात विकल्पों का प्रतिनिधित्व करता है।

```cpp
class IHtml5Options : public virtual Aspose::Slides::Export::ISaveOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **bool** [get_AnimateShapes](./get_animateshapes/)() | शैलियों की एनीमेशन विकल्प लौटाता है। पढ़ें **bool**। |
| virtual **bool** [get_AnimateTransitions](./get_animatetransitions/)() | ट्रांज़िशन की एनीमेशन विकल्प लौटाता है। पढ़ें **bool**। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को लौटाता है। पढ़ता है [System::String](../../system/string/)। |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | यह दर्शाता है कि टेक्स्ट बिनाई (ligatures) के बिना रेंडर किया जाता है या नहीं। जब **true** सेट किया जाता है, तो रेंडरित आउटपुट में बिनाई निष्क्रिय हो जाएगी। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट है। |
| virtual **bool** [get_EmbedImages](./get_embedimages/)() | छवियों के एम्बेडिंग विकल्प लौटाता है। पढ़ें **bool**। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की दृश्य शैली लौटाता है। पढ़े [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँगे। पढ़े [System::String](../../system/string/)। |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | चित्रों के संपीड़न स्तर को दर्शाता है। पढ़े [PicturesCompression](../picturescompression/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अपडेट सहेजने के लिए कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | प्रस्तुति सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ने का निर्धारण करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने की मोड प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोड प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़े [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नए ऑब्जेक्ट को आरंभ करता है और उप-वर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नए ऑब्जेक्ट को आरंभ करता है और उप-वर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की संदर्भ के आधार पर तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की संदर्भ के आधार पर तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मान प्रकार वस्तु की nullptr के साथ संदर्भ-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझाकृत रेफ़रेंस काउंट घटाता है। |
| virtual void [set_AnimateShapes](./set_animateshapes/)(**bool**) | शैलियों की एनीमेशन विकल्प सेट करता है। लिखें **bool**। |
| virtual void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) | ट्रांज़िशन की एनीमेशन विकल्प सेट करता है। लिखें **bool**। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | स्रोत फ़ॉन्ट न मिलने पर उपयोग किए जाने वाले फ़ॉन्ट को सेट करता है। लिखता है [System::String](../../system/string/)। |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | यह सेट करता है कि टेक्स्ट बिनाई (ligatures) के बिना रेंडर किया जाए या नहीं। जब **true** सेट किया जाता है, तो रेंडरित आउटपुट में बिनाई निष्क्रिय हो जाएगी। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट है। |
| virtual void [set_EmbedImages](./set_embedimages/)(**bool**) | छवियों के एम्बेडिंग विकल्प सेट करता है। लिखें **bool**। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की दृश्य शैली सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) | निर्धारित करता है कि बाहरी संसाधन कहाँ संग्रहीत किए जाएँगे। लिखें [System::String](../../system/string/)। |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | चित्रों के संपीड़न स्तर को सेट करता है। लिखें [PicturesCompression](../picturescompression/)। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अपडेट सहेजने के लिए कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रस्तुति सहेजते समय JavaScript कॉल वाले हाइपरलिंक को छोड़ने का निर्धारण करता है। लिखें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने की मोड सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | वह ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोड प्रक्रिया जारी रहेगी या रद्द की जाएगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को कमजोर पॉइंटर (साझाकृत के बजाय) सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझाकृत रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझाकृत रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझाकृत रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
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




## देखें भी

* क्लास [ISaveOptions](../isaveoptions/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)