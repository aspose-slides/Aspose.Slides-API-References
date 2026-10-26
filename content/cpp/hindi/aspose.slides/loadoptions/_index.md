---
title: LoadOptions
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रस्तुति लोड करते समय अतिरिक्त विकल्प (जैसे प्रारूप या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 4395
url: /hi/aspose.slides/loadoptions/
---
## LoadOptions कक्षा

एक प्रस्तुति लोड करते समय अतिरिक्त विकल्प (जैसे प्रारूप या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शीला फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शीला फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Binary Large Objects (BLOBs) हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प विशेष पर्यावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात स्थापित करने के उद्देश्य से हैं। |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले एशियाई फ़ॉन्ट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले नियमित फ़ॉन्ट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | यदि स्रोत फ़ॉन्ट नहीं मिला तो उपयोग किए जाने वाले सिंबल फ़ॉन्ट को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | प्रस्तुति पाठ के लिए डिफ़ॉल्ट भाषा को लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | निर्धारित करता है कि [Aspose.Slides](../) प्रस्तुति लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति की पूरी आयु के दौरान उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते। |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | विच्छेद अनुरोधों की निगरानी के लिए टोकन। |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | लोड करने के लिए प्रस्तुति का प्रारूप लौटाता है। पढ़ें [Slides::LoadFormat](../loadformat/)। |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | यह प्रॉपर्टी तभी सार्थक होती है जब प्रस्तुति फ़ाइल पासवर्ड से संरक्षित हो। true का मान का अर्थ है कि केवल डॉक्यूमेंट प्रॉपर्टीज़ को एन्क्रिप्टेड प्रस्तुति फ़ाइल से लोड किया जाना चाहिए और पासवर्ड को नजरअंदाज किया जाना चाहिए। false का मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रस्तुति को लोड किया जाना चाहिए। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल की डॉक्यूमेंट प्रॉपर्टीज़ सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो डॉक्यूमेंट प्रॉपर्टीज़ को लोड नहीं किया जा सकता और अपवाद फेंका जाएगा। पढ़ें **bool**। |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | पासवर्ड प्राप्त करता है। पढ़ें [System::String](../../system/string/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | बाहरी संसाधन लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को लौटाता है। पढ़ें [IResourceLoadingCallback](../iresourceloadingcallback/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिए, ये विकल्प चार्ट्स के फ़ॉर्मूला गणना को प्रभावित करते हैं। |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | एक ऑब्जेक्ट लौटाता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। पढ़ें [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| [LoadOptions](./loadoptions/)() | नया डिफ़ॉल्ट लोड विकल्प बनाता है। |
| [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | नया लोड विकल्प बनाता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज को कॉपी कन्स्ट्रक्ट करने की अनुमति देता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Binary Large Objects (BLOBs) हैंडलिंग व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों का प्रतिनिधित्व करता है, जैसे अस्थायी फ़ाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प विशेष पर्यावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात स्थापित करने के उद्देश्य से हैं। |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो एशियाई फ़ॉन्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो नियमित फ़ॉन्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | यदि स्रोत फ़ॉन्ट नहीं मिला तो सिंबल फ़ॉन्ट सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | प्रस्तुति टेक्स्ट के लिए डिफ़ॉल्ट भाषा सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | निर्धारित करता है कि [Aspose.Slides](../) प्रस्तुति लोड करते समय सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | प्रस्तुति द्वारा उपयोग किए जाने वाले बाहरी फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रस्तुति की पूरी आयु के दौरान उपलब्ध होते हैं और अन्य प्रस्तुतियों के साथ साझा नहीं होते। |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | विच्छेद अनुरोधों की निगरानी के लिए टोकन। |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | लोड करने के लिए प्रस्तुति का प्रारूप सेट करता है। लिखें [Slides::LoadFormat](../loadformat/)। |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | यह प्रॉपर्टी तभी सार्थक होती है जब प्रस्तुति फ़ाइल पासवर्ड से संरक्षित हो। true का मान का अर्थ है कि केवल डॉक्यूमेंट प्रॉपर्टीज़ को एन्क्रिप्टेड प्रस्तुति फ़ाइल से लोड किया जाना चाहिए और पासवर्ड को नजरअंदाज किया जाना चाहिए। false का मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रस्तुति को लोड किया जाना चाहिए। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल की डॉक्यूमेंट प्रॉपर्टीज़ सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो डॉक्यूमेंट प्रॉपर्टीज़ को लोड नहीं किया जा सकता और अपवाद फेंका जाएगा। लिखें **bool**। |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | पासवर्ड सेट करता है। लिखें [System::String](../../system/string/)। |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | बाहरी संसाधन लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को सेट करता है। लिखें [IResourceLoadingCallback](../iresourceloadingcallback/)। |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | स्प्रेडशीट्स के विकल्प प्राप्त करता है। उदाहरण के लिए, ये विकल्प चार्ट्स के फ़ॉर्मूला गणना को प्रभावित करते हैं। |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | एक ऑब्जेक्ट सेट करता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या रद्द की जाएगी। लिखें [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* कक्षा [ILoadOptions](../iloadoptions/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)