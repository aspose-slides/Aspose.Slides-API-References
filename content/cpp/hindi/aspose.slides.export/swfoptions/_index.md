---
title: SwfOptions
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि प्रस्तुति को Swf फ़ॉर्मेट में कैसे सहेजा जाए।
type: docs
weight: 742
url: /hi/aspose.slides.export/swfoptions/
---
## SwfOptions क्लास

स्वफ़ फ़ॉर्मेट में प्रस्तुति को सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमॅंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_Compressed](./get_compressed/)() override | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ को संकुचित किया जाना चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किए गए फ़ॉन्ट को लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | संदर्भ मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की दृश्य शैली को लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। डिफ़ॉल्ट 95 है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | छवि जो व्यूअर के ऊपरी दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो सही ढंग से नहीं दिख सकता। |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है। केवल तभी प्रभावी जब [set_LogoImageBytes()](./set_logoimagebytes/) निर्दिष्ट हो। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | निचले पैन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | फुलस्क्रीन बटन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | बाएँ पैन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | पृष्ठों के चारों ओर की बॉर्डर दिखानी है या नहीं, निर्दिष्ट करता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | पेज स्टेपर को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowSearch](./get_showsearch/)() override | सर्च सेक्शन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | पूरा शीर्ष पैन दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | प्रेजेंटेशन [ISlidesLayoutOptions](../islideslayoutoptions/) निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त करता है। यह प्रॉपर्टी प्रकार [HandoutLayoutingOptions](../handoutlayoutingoptions/) के ऑब्जेक्ट असाइनमेंट को समर्थन नहीं देती। |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | बाएँ पैन खुला हुआ शुरू करें। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ को संकुचित किया जाना चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | जब स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | संदर्भ मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की दृश्य शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG छवियों की गुणवत्ता निर्दिष्ट करता है। डिफ़ॉल्ट 95 है। |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | छवि जो व्यूअर के ऊपरी दाएँ कोने में लोगो के रूप में प्रदर्शित होगी। छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो सही ढंग से नहीं दिख सकता। |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | लोगो के लिए पूर्ण हाइपरलिंक पता सेट करता है। केवल तभी प्रभावी जब [set_LogoImageBytes()](./set_logoimagebytes/) निर्दिष्ट हो। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | निचले पैन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | फुलस्क्रीन बटन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | बाएँ पैन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | पृष्ठों के चारों ओर की बॉर्डर दिखानी है या नहीं, निर्दिष्ट करता है। डिफ़ॉल्ट true है। |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | पेज स्टेपर को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | सर्च सेक्शन को दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | पूरा शीर्ष पैन दिखाएँ/छुपाएँ। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रेजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | प्रेजेंटेशन [ISlidesLayoutOptions](../islideslayoutoptions/) निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को सेट करता है। यह प्रॉपर्टी प्रकार [HandoutLayoutingOptions](../handoutlayoutingoptions/) के ऑब्जेक्ट असाइनमेंट को समर्थन नहीं देती। |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | बाएँ पैन खुला हुआ शुरू करें। flashvars में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न SWF दस्तावेज़ में एकीकृत दस्तावेज़ व्यूअर शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्गुमेंट को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
|  [SwfOptions](./swfoptions/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कनवर्ट करना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector प्रयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

निम्न उदाहरण दर्शाता है कि PowerPoint को SWF Flash में कैसे परिवर्तित किया जाए। 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [ISwfOptions](../iswfoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)