---
title: ISVGOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
weight: 404
url: /hi/aspose.slides.export/isvgoptions/
---
## ISVGOptions क्लास

Represents an SVG options.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग होने वाला फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहें। यदि true तो क्रॉप किए गए हिस्से हटा दिए जाएंगे, यदि false तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल बड़ा हो सकता है) पढ़ें **bool**। |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | एक मान प्राप्त करता है जो संकेत करता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। जब **true** सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट है। |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। पढ़ें **bool**। |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 में मार्कर्स के लिए इनसेट्स परिभाषित करने की क्षमता नहीं है। [Aspose.Slides](../../aspose.slides/) SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड रखता है: यह तीर वाले लाइन के अंत को क्रॉप करता है, इसलिए लाइन मार्कर्स को ओवरलैप नहीं करती। यह विकल्प इस व्यवहार को बंद कर देता है। पढ़ें **bool**। |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ें [SvgExternalFontsHandling](../svgexternalfontshandling/)। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की दृश्य शैली लौटाता है। पढ़ें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | निर्यात किए गए दस्तावेज़ में [Ink](../../aspose.slides.ink/) ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ें **int32_t**। |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | मेटा फ़ाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा लौटाता है। पढ़ें **int32_t**। |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | चित्रों के संपीड़न स्तर को दर्शाता है। पढ़ें [PicturesCompression](../picturescompression/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अपडेट को सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को शेप परिवर्तन को नियंत्रित करने की अनुमति देता है। पढ़ें [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | प्रेज़ेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, निर्दिष्ट करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, निर्धारित करता है। पढ़ें **bool**। डिफ़ॉल्ट मान true है। |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं, निर्धारित करता है। पढ़ें **bool**। डिफ़ॉल्ट मान false है। |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजना है या नहीं, निर्धारित करता है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रोक दी जाएगी। पढ़ें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हेशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग होने वाला फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहें। यदि true है तो क्रॉप किए गए हिस्से हटाए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध किए जाएंगे (जिससे फ़ाइल बड़ा हो सकता है) लिखें **bool**। |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | SVG में 3D टेक्स्ट अक्षम है या नहीं, निर्धारित करता है। लिखें **bool**। |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | एक मान सेट करता है जो संकेत करता है कि टेक्स्ट बिना लिगेचर के रेंडर किया गया है या नहीं। जब **true** सेट किया जाता है, तो रेंडर आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी **false** पर सेट है। |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। लिखें **bool**। |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 में मार्कर्स के लिए इनसेट्स परिभाषित करने की क्षमता नहीं है। [Aspose.Slides](../../aspose.slides/) SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड रखता है: यह तीर वाले लाइन के अंत को क्रॉप करता है, ताकि लाइन मार्कर्स को ओवरलैप न करे। यह विकल्प इस व्यवहार को बंद कर देता है। लिखें **bool**। |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। लिखें [SvgExternalFontsHandling](../svgexternalfontshandling/)। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की दृश्य शैली सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। लिखें **int32_t**। |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | मेटा फ़ाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा सेट करता है। लिखें **int32_t**। |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | चित्रों के संपीड़न स्तर को दर्शाता है। लिखें [PicturesCompression](../picturescompression/)। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अपडेट को सहेजने के लिए एक कॉलबैक ऑब्जेक्ट का प्रतिनिधित्व करता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | एक कॉलबैक इंटरफ़ेस लौटाता और सेट करता है जो उपयोगकर्ता को शेप परिवर्तन को नियंत्रित करने की अनुमति देता है। लिखें [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रेज़ेंटेशन सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना है या नहीं, निर्दिष्ट करता है। लिखें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, निर्धारित करता है। लिखें **bool**। डिफ़ॉल्ट मान true है। |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं, निर्धारित करता है। लिखें **bool**। डिफ़ॉल्ट मान false है। |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजना है या नहीं, निर्धारित करता है। लिखें **bool**। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रूक जाएगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक वैक प्वाइंटर (शेयर किए हुए के बजाय) सेट करें। कंटेनरों में पॉइंटर को वैक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [ISaveOptions](../isaveoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)