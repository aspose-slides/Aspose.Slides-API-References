---
title: IPdfOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि एक प्रस्तुति को Pdf प्रारूप में कैसे सहेजा जाता है।
type: docs
weight: 274
url: /hi/aspose.slides.export/ipdfoptions/
---
## IPdfOptions क्लास

Provides options that control how a presentation is saved in Pdf format.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | फ़्लैग्स का सेट शामिल करता है जो यह निर्धारित करता है कि दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियां दी जानी चाहिए। देखें [PdfAccessPermissions](../pdfaccesspermissions/)। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एक एरे लौटाता है जिसे [Aspose.Slides](../../aspose.slides/) सामान्य मानना चाहिए। पढ़ें [System::String](../../system/string/)[]। |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | यदि **true** हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | यह दर्शाता है कि क्या प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए। यदि **bool**.true सेट किया गया हो, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा। |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | जनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। पढ़ें [PdfCompliance](../pdfcompliance/)। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला फ़ॉन्ट लौटाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true रखें। पढ़ें **bool**। |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। पढ़ें **bool**। |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | ASCII अक्षरों 32-127 के लिए True टाइप फ़ॉन्ट एम्बेड करने के लिए true रखें। [Fonts](../../aspose.slides/fonts/) 127 से अधिक अक्षर कोड हमेशा एम्बेड होते हैं। पढ़ें **bool**। |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | ग्रेडिएंट की दृश्य शैली लौटाता है। पढ़ें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | छवि का पारदर्शी रंग प्राप्त करता है। |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | प्रेज़ेंटेशन से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true रखें। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | एक्सपोर्टेड दस्तावेज़ में [Ink](../../aspose.slides.ink/) वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../iinkoptions/)। |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | PDF दस्तावेज़ के अंदर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान लौटाता है। पढ़ें **uint8_t**। |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट कर रहा है। पढ़ें [System::String](../../system/string/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | प्रतिशत में प्रगति अद्यतन को सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | यदि फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं यह दर्शाता है। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता बढ़ा सकता है। पढ़ें **bool**। |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | प्रेजेंटेशन में उपयोग किए गए सभी मेटाफाइल्स को PNG छवियों में परिवर्तित करने के लिए true रखें। पढ़ें **bool**। |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | निर्दिष्ट करता है कि जनरेट किया गया दस्तावेज़ छुपी स्लाइड्स को शामिल करे या नहीं। डिफ़ॉल्ट **false** है। |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | प्रेजेंटेशन को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना चाहिए या नहीं यह निर्दिष्ट करता है। पढ़ें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | प्रेजेंटेशन एक्सपोर्ट करते समय स्लाइड्स को पेज पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | PDF दस्तावेज़ के अंदर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान लौटाता है। |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | दस्तावेज़ में सभी टेक्स्ट सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। पढ़ें [PdfTextCompression](../pdftextcompression/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास को कॉपी कन्स्ट्रक्ट करने देता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास को कॉपी कन्स्ट्रक्ट करने देता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | फ़्लैग्स का सेट शामिल करता है जो यह निर्धारित करता है कि दस्तावेज़ को उपयोगकर्ता पहुँच के साथ खोलने पर कौन से एक्सेस अनुमतियां दी जानी चाहिए। देखें [PdfAccessPermissions](../pdfaccesspermissions/)। |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | फ़ॉन्ट परिवारों के उपयोगकर्ता-परिभाषित नामों की एरे सेट करता है जिसे [Aspose.Slides](../../aspose.slides/) सामान्य मानना चाहिए। लिखें [System::String](../../system/string/)[]। |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | यदि **true** हो तो निर्दिष्ट पारदर्शी रंग को छवि पर लागू करता है। |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | यह दर्शाता है कि क्या प्रत्येक छवि के लिए सबसे प्रभावी संपीड़न (डिफ़ॉल्ट के बजाय) स्वचालित रूप से चयनित होना चाहिए। यदि **bool**.true सेट किया गया हो, तो प्रस्तुति की प्रत्येक छवि के लिए सबसे उपयुक्त संपीड़न एल्गोरिद्म चुना जाएगा, जिससे उत्पन्न PDF दस्तावेज़ का आकार छोटा होगा। |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | जनरेट किए गए PDF दस्तावेज़ के लिए वांछित अनुरूपता स्तर। लिखें [PdfCompliance](../pdfcompliance/)। |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | यदि स्रोत फ़ॉन्ट नहीं मिलता है तो उपयोग किया जाने वाला फ़ॉन्ट सेट करता है। लिखता है [System::String](../../system/string/)। |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | प्रत्येक स्लाइड के चारों ओर काली फ्रेम खींचने के लिए true रखें। लिखें **bool**। |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | निर्धारित करता है कि फ़ॉन्ट के सभी अक्षर एम्बेड किए जाएँ या केवल उपयोग किए गए उपसमुच्चय। लिखें **bool**। |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | ASCII अक्षर 32-127 के लिए True टाइप फ़ॉन्ट एम्बेड करने के लिए true रखें। 127 से अधिक अक्षर कोड हमेशा एम्बेड होते हैं [Fonts](../../aspose.slides/fonts/)। लिखें **bool**। |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | ग्रेडिएंट की दृश्य शैली सेट करता है। लिखें [GradientStyle](../../aspose.slides/gradientstyle/)। |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | छवि का पारदर्शी रंग सेट करता है। |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | प्रेजेंटेशन से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true रखें। लिखें **bool**। |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | PDF दस्तावेज़ के अंदर JPEG छवियों की गुणवत्ता निर्धारित करने वाला मान सेट करता है। लिखें **uint8_t**। |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | PDF दस्तावेज़ की सुरक्षा के लिए उपयोगकर्ता पासवर्ड सेट करना। लिखें [System::String](../../system/string/)। |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | प्रतिशत में प्रगति अद्यतन को सहेजने के लिए एक कॉलबैक ऑब्जेक्ट दर्शाता है। देखें [IProgressCallback](../../aspose.slides/iprogresscallback/)। |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | यदि फ़ॉन्ट बोल्ड शैली का समर्थन नहीं करता है तो टेक्स्ट को बिटमैप के रूप में रास्टराइज़ करके PDF में सहेजना चाहिए या नहीं यह दर्शाता है। यह तरीका कुछ फ़ॉन्ट्स के लिए परिणामस्वरूप PDF में टेक्स्ट की गुणवत्ता बढ़ा सकता है। लिखें **bool**। |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | प्रेजेंटेशन में उपयोग किए गए सभी मेटाफाइल्स को PNG छवियों में बदलने के लिए true रखें। लिखें **bool**। |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | निर्दिष्ट करता है कि जनरेट किया गया दस्तावेज़ छुपी स्लाइड्स को शामिल करे या नहीं। डिफ़ॉल्ट **false** है। |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | प्रेजेंटेशन को सहेजते समय जावास्क्रिप्ट कॉल वाले हाइपरलिंक्स को छोड़ना चाहिए या नहीं यह निर्दिष्ट करता है। लिखें **bool**। डिफ़ॉल्ट मान **false** है। |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | प्रेजेंटेशन एक्सपोर्ट करते समय स्लाइड्स को पेज पर रखने के मोड को सेट करता है [ISlidesLayoutOptions](../islideslayoutoptions/)। |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | PDF दस्तावेज़ के अंदर छवियों के रिज़ॉल्यूशन को निर्धारित करने वाला मान सेट करता है। |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | दस्तावेज़ में सभी टेक्स्ट सामग्री के लिए उपयोग किए जाने वाले संपीड़न प्रकार को निर्दिष्ट करता है। लिखें [PdfTextCompression](../pdftextcompression/)। |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियों को प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द होगी। लिखें [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाकर लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [ISaveOptions](../isaveoptions/)
* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)