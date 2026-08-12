---
title: IHtmlOptions
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 222
url: /hi/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions क्लास

Represents a HTML exporting options.

```cpp
class IHtmlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। पढ़ता है [System::String](../../system/string/)। |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | एक बूलियन फ़्लैग संकेत करता है कि काटे गए भाग दस्तावेज़ का हिस्सा बने रहें। यदि true है तो काटे गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल बड़ा हो सकता है) पढ़ें **bool**। |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | एक मान प्राप्त करता है जो यह दर्शाता है कि पाठ लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की विज़ुअल स्टाइल लौटाता है। पढ़ता है [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() | HTML टेम्पलेट लौटाता है। पढ़ता है [IHtmlFormatter](../ihtmlformatter/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | निर्यातित दस्तावेज़ में [Ink](../../aspose.slides.ink/) वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है। पढ़ें **uint8_t**। |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | चित्र संपीड़न स्तर को दर्शाता है। पढ़ता है [PicturesCompression](../picturescompression/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अपडेट सहेजने के लिए कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छुपी स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट **false** है। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | प्रेजेंटेशन को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्धारित करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() | स्लाइड इमेज फ़ॉर्मेट विकल्प लौटाता है। पढ़ता है [ISlideImageFormat](../islideimageformat/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | प्रेजेंटेशन निर्यात करते समय स्लाइड को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर रखने के लिए True - इससे लेआउट रिस्पॉन्सिव बनता है। अन्यथा False। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या निरस्त की जाएगी। पढ़ता है [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। लिखता है [System::String](../../system/string/)। |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | एक बूलियन फ़्लैग संकेत करता है कि काटे गए भाग दस्तावेज़ का हिस्सा बने रहें। यदि true है तो काटे गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल बड़ा हो सकता है) लिखें **bool**। |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि पाठ लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की विज़ुअल स्टाइल सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) | HTML टेम्पलेट सेट करता है। लिखें [IHtmlFormatter](../ihtmlformatter/)। |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | PDF दस्तावेज़ के भीतर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें **uint8_t**। |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | चित्र संपीड़न स्तर को दर्शाता है। लिखें [PicturesCompression](../picturescompression/)। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अपडेट सहेजने के लिए कॉलबैक ऑब्जेक्ट को दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छुपी स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट **false** है। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रेजेंटेशन को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक को छोड़ना है या नहीं, यह निर्धारित करता है। लिखें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) | स्लाइड इमेज फ़ॉर्मेट विकल्प सेट करता है। लिखें [ISlideImageFormat](../islideimageformat/)। |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | प्रेजेंटेशन निर्यात करते समय स्लाइड को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) | SVG कंटेनर से चौड़ाई और ऊँचाई गुणों को बाहर रखने के लिए True - इससे लेआउट रिस्पॉन्सिव बनता है। अन्यथा False। लिखें **bool**। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या निरस्त की जाएगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | नथ टेम्प्लेट आर्ग्युमेंट को कमजोर पॉइंटर सेट करता है (शेयर किए हुए के बजाय)। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [ISaveOptions](../isaveoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)