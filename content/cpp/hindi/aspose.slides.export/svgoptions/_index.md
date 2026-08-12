---
title: SVGOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
weight: 703
url: /hi/aspose.slides.export/svgoptions/
---
## SVGOptions क्लास

एक SVG विकल्प का प्रतिनिधित्व करता है।

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | डिफ़ॉल्ट सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [SVGOptions](./)। |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | एक बूलियन फ़्लैग यह दर्शाता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true हो तो कटे हुए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)। |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। **bool** पढ़ें। |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | एक मूल्य प्राप्त करता है जो दर्शाता है कि टेक्स्ट लिगेचर का उपयोग किए बिना रेंडर किया जाता है या नहीं। जब **true** पर सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। **bool** पढ़ें। |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। [Aspose.Slides](../../aspose.slides/) SVG राइटिंग इंजन ने इस समस्या का वर्कअराउंड लागू किया है: यह तीर वाले लाइन के अंत को काट देता है, ताकि लाइन मार्करों के साथ ओवरलैप न करे। यह विकल्प ऐसे व्यवहार को बंद कर देता है। **bool** पढ़ें। |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | बाहरी रूप से लोड किए गए फ़ॉन्ट्स को संभालने के तरीके को निर्धारित करता है। [SvgExternalFontsHandling](../svgexternalfontshandling/) पढ़ें। |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | ग्रेडिएंट की विज़ुअल शैली लौटाता है। [GradientStyle](../../aspose.slides/gradientstyle/) पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | निर्यात किए गए दस्तावेज़ में [Ink](../../aspose.slides.ink/) ऑब्जेक्ट्स की दिखावट को नियंत्रित करने के विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। **int32_t** पढ़ें। |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा लौटाता है। **int32_t** पढ़ें। |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | चित्रों के संपीड़न स्तर को दर्शाता है |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को शेप कन्वर्ज़न नियंत्रित करने देता है। [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) पढ़ें। |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | सबसे सरल और सबसे छोटे SVG फ़ाइल जनरेशन के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [SVGOptions](./)। |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | प्रजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को स्किप करना है या नहीं, यह निर्दिष्ट करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | रेंडरिंग के समय शेप की निर्दिष्ट घुमाव को लागू करना है या नहीं, यह निर्धारित करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **true** है। |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | क्या टेक्स्ट फ्रेम रेंडरिंग एरिया में शामिल होगा या नहीं, यह निर्धारित करता है। **bool** पढ़ें। डिफ़ॉल्ट मान **false** है। |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं, यह निर्धारित करता है। **bool** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रखी जाए या रद्द कर दी जाए। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ें। |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | सबसे सटीक SVG फ़ाइल जनरेशन के लिए सेटिंग्स लौटाता है। केवल-पढ़ने योग्य [SVGOptions](./)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट के साथ जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस को nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किया गया फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | एक बूलियन फ़्लैग यह दर्शाता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true हो तो कटे हुए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)। |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | SVG में 3D टेक्स्ट निष्क्रिय है या नहीं निर्धारित करता है। **bool** लिखें। |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | एक मूल्य सेट करता है जो दर्शाता है कि टेक्स्ट लिगेचर के बिना रेंडर किया जाता है या नहीं। जब **true** पर सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट होती है। |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। **bool** लिखें। |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। [Aspose.Slides](../../aspose.slides/) SVG राइटिंग इंजन ने इस समस्या का वर्कअराउंड लागू किया है: यह तीर वाले लाइन के अंत को काट देता है, ताकि लाइन मार्करों के साथ ओवरलैप न करे। यह विकल्प ऐसे व्यवहार को बंद कर देता है। **bool** लिखें। |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | बाहरी रूप से लोड किए गए फ़ॉन्ट्स को संभालने के तरीके को निर्धारित करता है। [SvgExternalFontsHandling](../svgexternalfontshandling/) लिखें। |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | ग्रेडिएंट की विज़ुअल शैली सेट करता है। [GradientStyle](../../aspose.slides/gradientstyle/) लिखें। |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। **int32_t** लिखें। |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा सेट करता है। **int32_t** लिखें। |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | चित्रों के संपीड़न स्तर को दर्शाता है |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | प्रगति अपडेट को प्रतिशत में सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। [IProgressCallback](../../aspose.slides/iprogresscallback/) देखें। |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को शेप कन्वर्ज़न नियंत्रित करने देता है। [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) लिखें। |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | प्रजेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को स्किप करना है या नहीं, यह निर्दिष्ट करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | रेंडरिंग के समय शेप की निर्दिष्ट घुमाव को लागू करना है या नहीं, यह निर्धारित करता है। **bool** लिखें। डिफ़ॉल्ट मान **true** है। |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | टेक्स्ट फ्रेम रेंडरिंग एरिया में शामिल होगा या नहीं, यह निर्धारित करता है। **bool** लिखें। डिफ़ॉल्ट मान **false** है। |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं, यह निर्धारित करता है। **bool** लिखें। |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट लौटाता या सेट करता है जो चेतावनियों को प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रखी जाए या रद्द कर दी जाए। [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [SVGOptions](./svgoptions/)() | [SVGOptions](./) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | [SVGOptions](./) क्लास की नई इंस्टेंस को लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट करके इनिशियलाइज़ करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [SaveOptions](../saveoptions/)
* क्लास [ISVGOptions](../isvgoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)