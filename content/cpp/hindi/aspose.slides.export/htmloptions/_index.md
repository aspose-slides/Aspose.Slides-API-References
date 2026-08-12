---
title: HtmlOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 118
url: /hi/aspose.slides.export/htmloptions/
---
## HtmlOptions वर्ग

HTML निर्यात विकल्पों का प्रतिनिधित्व करता है।

```cpp
class HtmlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IHtmlOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाले फ़ॉन्ट को लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | एक बूलियन फ्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true हो तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बढ़ सकता है)। |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | एक मान प्राप्त करता है जो दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया गया है या नहीं। जब **true** सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की विज़ुअल शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() override | HTML टेम्पलेट लौटाता है। [IHtmlFormatter](../ihtmlformatter/) पढ़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | [Ink](../../aspose.slides.ink/) ऑब्जेक्ट्स के रूप को निर्यात किए गए दस्तावेज़ में नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है। **uint8_t** पढ़ता है। |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रत्येक प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। डिफ़ॉल्ट **false** है। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाली हाइपरलिंक्स को छोड़ना चाहिए या नहीं, यह निर्दिष्ट करता है। **bool** पढ़ता है। डिफ़ॉल्ट मान **false** है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() override | स्लाइड इमेज फ़ॉर्मेट विकल्प लौटाता है। [ISlideImageFormat](../islideimageformat/) पढ़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() override | SVG कंटेनर से चौड़ाई और ऊंचाई गुणों को बाहर रखने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। अन्यथा false। **bool** पढ़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट सेट या रिटर्न करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान रूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान रूप। |
| [HtmlOptions](./htmloptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | एक नया [HtmlOptions](./) ऑब्जेक्ट बनाता है जो कॉलबैक निर्दिष्ट करता है। |
| [HtmlOptions](./htmloptions/)() | एक नया [HtmlOptions](./) ऑब्जेक्ट बनाता है जो एकल HTML फ़ाइल में सहेजने के लिए उपयोग होता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान रूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान रूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयरड रेफ़रेंस काउंट को घटाता है। |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | जब स्रोत फ़ॉन्ट नहीं मिला तो उपयोग होने वाले फ़ॉन्ट को सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | एक बूलियन फ्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true हो तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बढ़ सकता है)। |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | टेक्स्ट को लिगेचर के बिना रेंडर करने का मान सेट करता है। जब **true** सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की विज़ुअल शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखता है। |
| void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) override | HTML टेम्पलेट सेट करता है। [IHtmlFormatter](../ihtmlformatter/) लिखता है। |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF दस्तावेज़ में JPEG छवियों की गुणवत्ता निर्धारित करने वाले मान को सेट करता है। **uint8_t** लिखता है। |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है। |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रत्येक प्रतिशत में प्रगति अपडेट सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल की जानी चाहिए या नहीं। डिफ़ॉल्ट **false** है। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रस्तुति को सहेजते समय जावास्क्रिप्ट कॉल वाली हाइपरलिंक्स को छोड़ना चाहिए या नहीं, यह निर्दिष्ट करता है। **bool** लिखता है। डिफ़ॉल्ट मान **false** है। |
| void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) override | स्लाइड इमेज फ़ॉर्मेट विकल्प सेट करता है। [ISlideImageFormat](../islideimageformat/) लिखता है। |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) override | SVG कंटेनर से चौड़ाई और ऊंचाई गुणों को बाहर रखने के लिए true - इससे लेआउट रिस्पॉन्सिव हो जाएगा। अन्यथा false। **bool** लिखता है। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट सेट या रिटर्न करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector इस्तेमाल करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector इस्तेमाल करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान रूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector इस्तेमाल करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector इस्तेमाल करें। |
| virtual [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [SaveOptions](../saveoptions/)
* वर्ग [IHtmlOptions](../ihtmloptions/)
* नामस्थान [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)