---
title: ILoadOptions
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेज़ेंटेशन लोड करते समय अतिरिक्त विकल्प (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।
type: docs
weight: 2796
url: /hi/aspose.slides/iloadoptions/
---
## ILoadOptions क्लास

प्रेज़ेंटेशन लोड करते समय अतिरिक्त विकल्प (जैसे फ़ॉर्मेट या डिफ़ॉल्ट फ़ॉन्ट) निर्दिष्ट करने की अनुमति देता है।

```cpp
class ILoadOptions : public virtual System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | बाइनरी लार्ज ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों को दर्शाता है, जैसे अस्थायी फाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प किसी विशिष्ट वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात सेट करने के लिए अभिप्रेत हैं। |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला एशियन फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला रेगुलर फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला सिम्बोल फ़ॉन्ट लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा लौटाता है। [System::String](../../system/string/) पढ़ता है। |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | निर्धारित करता है कि [Aspose.Slides](../) प्रेज़ेंटेशन लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले एक्सटर्नल फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेज़ेंटेशन की पूरी आयु तक उपलब्ध रहते हैं और अन्य प्रेज़ेंटेशन्स के साथ साझा नहीं किए जाते |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | विच्छेद अनुरोधों की निगरानी के लिए टोकन। |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | लोड करने के लिए प्रेज़ेंटेशन के फ़ॉर्मेट को लौटाता है। [Slides::LoadFormat](../loadformat/) पढ़ता है। |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | यह प्रॉपर्टी तब अर्थपूर्ण होती है जब प्रेज़ेंटेशन फ़ाइल पासवर्ड संरक्षित हो। true मान का अर्थ है कि एन्क्रिप्टेड प्रेज़ेंटेशन फ़ाइल से केवल डॉक्यूमेंट प्रॉपर्टीज़ लोड की जानी चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रेज़ेंटेशन लोड की जानी चाहिए। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल की डॉक्यूमेंट प्रॉपर्टीज़ सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो डॉक्यूमेंट प्रॉपर्टीज़ लोड नहीं की जा सकेंगी और अपवाद फेंका जाएगा। **bool** पढ़ता है। |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | पासवर्ड प्राप्त करता है। [System::String](../../system/string/) पढ़ता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | एक्सटर्नल रिसोर्सेज़ लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को लौटाता है। [IResourceLoadingCallback](../iresourceloadingcallback/) पढ़ता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | विकल्प दर्शाता है जिनका उपयोग अतिरिक्त स्प्रेडशीट व्यवहार निर्दिष्ट करने के लिए किया जा सकता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | एक ऑब्जेक्ट लौटाता है जो चेतावनियाँ प्राप्त करता है और तय करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) पढ़ता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | बाइनरी लार्ज ऑब्जेक्ट्स (BLOBs) को संभालने के व्यवहार को प्रबंधित करने के लिए उपयोग किए जा सकने वाले विकल्पों को दर्शाता है, जैसे अस्थायी फाइलों का उपयोग या मेमोरी में अधिकतम BLOBs बाइट्स। ये विकल्प किसी विशिष्ट वातावरण या आवश्यकताओं के लिए सर्वोत्तम प्रदर्शन/मेमोरी खपत अनुपात सेट करने के लिए अभिप्रेत हैं। |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला एशियन फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला रेगुलर फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | स्रोत फ़ॉन्ट नहीं मिलने पर उपयोग होने वाला सिम्बोल फ़ॉन्ट सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | प्रेज़ेंटेशन टेक्स्ट के लिए डिफ़ॉल्ट भाषा सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | निर्धारित करता है कि [Aspose.Slides](../) प्रेज़ेंटेशन लोडिंग के दौरान सभी एम्बेडेड बाइनरी ऑब्जेक्ट्स को हटाएगा या नहीं। |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | प्रेज़ेंटेशन द्वारा उपयोग किए जाने वाले एक्सटर्नल फ़ॉन्ट्स के स्रोत निर्दिष्ट करता है। ये फ़ॉन्ट्स प्रेज़ेंटेशन की पूरी आयु तक उपलब्ध रहते हैं और अन्य प्रेज़ेंटेशन्स के साथ साझा नहीं किए जाते |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | विच्छेद अनुरोधों की निगरानी के लिए टोकन। |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | लोड करने के लिए प्रेज़ेंटेशन के फ़ॉर्मेट को सेट करता है। [Slides::LoadFormat](../loadformat/) लिखता है। |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | यह प्रॉपर्टी तब अर्थपूर्ण होती है जब प्रेज़ेंटेशन फ़ाइल पासवर्ड संरक्षित हो। true मान का अर्थ है कि एन्क्रिप्टेड प्रेज़ेंटेशन फ़ाइल से केवल डॉक्यूमेंट प्रॉपर्टीज़ लोड की जानी चाहिए और पासवर्ड को अनदेखा किया जाना चाहिए। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके पूरी एन्क्रिप्टेड प्रेज़ेंटेशन लोड की जानी चाहिए। यदि प्रेज़ेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा अनदेखा किया जाता है। यदि एन्क्रिप्टेड फ़ाइल की डॉक्यूमेंट प्रॉपर्टीज़ सार्वजनिक नहीं हैं और प्रॉपर्टी मान true है तो डॉक्यूमेंट प्रॉपर्टीज़ लोड नहीं की जा सकेंगी और अपवाद फेंका जाएगा। **bool** लिखता है। |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | पासवर्ड सेट करता है। [System::String](../../system/string/) लिखता है। |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | एक्सटर्नल रिसोर्सेज़ लोडिंग को प्रबंधित करने वाले कॉलबैक इंटरफ़ेस को सेट करता है। [IResourceLoadingCallback](../iresourceloadingcallback/) लिखता है। |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | विकल्प दर्शाता है जिनका उपयोग अतिरिक्त स्प्रेडशीट व्यवहार निर्दिष्ट करने के लिए किया जा सकता है। |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | एक ऑब्जेक्ट सेट करता है जो चेतावनियाँ प्राप्त करता है और निर्धारित करता है कि लोडिंग प्रक्रिया जारी रहेगी या समाप्त होगी। [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) लिखता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को इन्क्रिमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को डिक्रीमेंट करता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को इन्क्रिमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को डिक्रीमेंट करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)