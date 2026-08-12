---
title: ISwfOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: विकल्प प्रदान करता है जो यह नियंत्रित करते हैं कि प्रस्तुति को SWF प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 469
url: /hi/aspose.slides.export/iswfoptions/
---
## ISwfOptions क्लास

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| virtual **bool** [get_Compressed](./get_compressed/)() | निर्दिष्ट करता है कि जेनरेट किया गया SWF डॉक्यूमेंट संपीड़ित होना चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | फ़ॉन्ट लौटाता है जो स्रोत फ़ॉन्ट न मिलने पर उपयोग किया जाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | संदर्भ मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की विज़ुअल स्टाइल लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG इमेज की क्वालिटी निर्दिष्ट करता है।\n\n डिफ़ॉल्ट 95 है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | छवि जो व्यूअर के ऊपर दाएँ कोने में लोगो के रूप में दर्शाई जाएगी।\n\n छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो ठीक से नहीं दिख सकता। |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | लोगो के लिए पूर्ण हाइपरलिंक पता प्राप्त करता है। यह केवल तब प्रभावी होता है जब [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) निर्दिष्ट किया गया हो। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | निचला पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | निर्दिष्ट करता है कि जेनरेट किया गया दस्तावेज़ छिपी हुई स्लाइड्स शामिल करे या नहीं। डिफ़ॉल्ट **false** है। |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | बाएँ पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | निर्दिष्ट करता है कि पृष्ठों के आसपास की सीमा दिखाई दे। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | पेज स्टेपर दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | सर्च सेक्शन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | पूरा टॉप पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | निर्दिष्ट करता है कि प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। यह प्रॉपर्टी **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** प्रकार के ऑब्जेक्ट्स को असाइन करने का समर्थन नहीं करती। |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | खुले बाएँ पैन के साथ शुरू करें। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | निर्दिष्ट करता है कि जेनरेट किया गया SWF डॉक्यूमेंट इंटीग्रेटेड डॉक्यूमेंट व्यूअर शामिल करे या नहीं। डिफ़ॉल्ट **true** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या बाधित होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानुपातिक। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानुपातिक। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानुपातिक। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानुपातिक। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट कम करता है। |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | निर्दिष्ट करता है कि जेनरेट किया गया SWF डॉक्यूमेंट संपीड़ित होना चाहिए या नहीं। डिफ़ॉल्ट **true** है। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | जब स्रोत फ़ॉन्ट न मिले तो उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | संदर्भ मेनू को सक्षम/अक्षम करता है। डिफ़ॉल्ट true है। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की विज़ुअल स्टाइल सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG इमेज की क्वालिटी निर्दिष्ट करता है।\n\n डिफ़ॉल्ट 95 है। |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | छवि जो व्यूअर के ऊपर दाएँ कोने में लोगो के रूप में दर्शाई जाएगी।\n\n छवि 32x64 पिक्सेल PNG होनी चाहिए, अन्यथा लोगो ठीक से नहीं दिख सकता। |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | लोगो के लिए पूर्ण हाइपरलिंक पता सेट करता है। यह केवल तब प्रभावी होता है जब [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) निर्दिष्ट किया गया हो। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | निचला पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | फ़ुलस्क्रीन बटन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | निर्दिष्ट करता है कि जेनरेट किया गया दस्तावेज़ छिपी हुई स्लाइड्स शामिल करे या नहीं। डिफ़ॉल्ट **false** है। |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | बाएँ पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | पृष्ठों के आसपास की सीमा दिखाई दे। डिफ़ॉल्ट true है। |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | पेज स्टेपर दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | सर्च सेक्शन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | पूरा टॉप पैन दिखाएँ/छिपाएँ। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट true है। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | निर्दिष्ट करता है कि प्रस्तुति सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | प्रस्तुति निर्यात करते समय स्लाइड्स को पेज पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। यह प्रॉपर्टी **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** प्रकार के ऑब्जेक्ट्स को असाइन करने का समर्थन नहीं करती। |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | खुले बाएँ पैन के साथ शुरू करें। फ्लैशवर्स में ओवरराइड किया जा सकता है। डिफ़ॉल्ट false है। |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | निर्दिष्ट करता है कि जेनरेट किया गया SWF डॉक्यूमेंट इंटीग्रेटेड डॉक्यूमेंट व्यूअर शामिल करे या नहीं। डिफ़ॉल्ट **true** है। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियां प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या बाधित होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानुपातिक। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [ISaveOptions](../isaveoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)