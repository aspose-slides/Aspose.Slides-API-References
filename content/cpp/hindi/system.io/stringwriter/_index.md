---
title: StringWriter
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक TextWriter को कार्यान्वित करता है जो जानकारी को स्ट्रिंग में लिखता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 417
url: /hi/system.io/stringwriter/
---
## StringWriter वर्ग

एक [TextWriter](../textwriter/) को लागू करता है जो जानकारी को स्ट्रिंग में लिखता है। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन को तर्क के रूप में पास करें।

```cpp
class StringWriter : public System::IO::TextWriter
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | स्ट्रीम को बंद करता है और अधिग्रहीत संसाधनों को मुक्त करता है। |
| void [Dispose](../textwriter/dispose/)() override | वर्तमान वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और आधारभूत स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धान्तों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual void [Flush](../textwriter/flush/)() | बफ़र की सामग्री को आधारभूत स्ट्रीम में फ़्लश करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | वर्तमान में उपयोग किए गए एन्कोडिंग को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | वर्तमान में उपयोग किया गया [IFormatProvider](../../system/iformatprovider/) ऑब्जेक्ट लौटाता है। |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | वर्तमान में उपयोग किया गया [IFormatProvider](../../system/iformatprovider/) ऑब्जेक्ट लौटाता है। |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ा रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान है। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | वर्तमान में उपयोग किया गया StringBuilder लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान है। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउण्ट को घटाता है। |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | एक लाइन टर्मिनेटर स्ट्रिंग सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्गुमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउण्टर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउण्ट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउण्ट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | निर्दिष्ट StringBuilder और [IFormatProvider](../../system/iformatprovider/) का उपयोग करके [StringWriter](./) का नया इंस्टेंस बनाता है। |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | निर्दिष्ट StringBuilder और वर्तमान संस्कृति से [IFormatProvider](../../system/iformatprovider/) का उपयोग करके [StringWriter](./) का नया इंस्टेंस बनाता है। |
| [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | निर्दिष्ट [IFormatProvider](../../system/iformatprovider/) का उपयोग करके [StringWriter](./) का नया इंस्टेंस बनाता है। |
| [StringWriter](./stringwriter/)() | वर्तमान संस्कृति से [IFormatProvider](../../system/iformatprovider/) का उपयोग करके [StringWriter](./) का नया इंस्टेंस बनाता है। |
| [String](../../system/string/) [ToString](./tostring/)() const override | अधीनस्थ स्ट्रिंग लौटाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउण्ट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउण्ट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(char_t) override | निर्दिष्ट अक्षर को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट कैरेक्टर ऐरे से निर्दिष्ट सबरेज का अक्षर स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [String](../../system/string/)\&) override | निर्दिष्ट स्ट्रिंग को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**bool**) | निर्दिष्ट बूलियन मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**double**) | निर्दिष्ट डबल-प्रिसीजन फ्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(int) | निर्दिष्ट 32-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**int64_t**) | निर्दिष्ट 64-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**float**) | निर्दिष्ट सिंगल-प्रिसीजन फ्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | निर्दिष्ट अनसाइन्ड 32-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | निर्दिष्ट अनसाइन्ड 64-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | निर्दिष्ट ऐरे के सभी अक्षरों को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(const char_t *) | निर्दिष्ट C-स्ट्रिंग को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फॉर्मेट के अनुसार फॉर्मेट करके स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)() | लाइन टर्मिनेटर कैरेक्टर्स को स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | निर्दिष्ट बूलियन मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | निर्दिष्ट अक्षर को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | निर्दिष्ट डबल-प्रिसीजन फ्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(int) | निर्दिष्ट 32-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | निर्दिष्ट 64-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | निर्दिष्ट सिंगल-प्रिसीजन फ्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | निर्दिष्ट अनसाइन्ड 32-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | निर्दिष्ट अनसाइन्ड 64-बिट पूर्णांक मान के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | निर्दिष्ट ऐरे के सभी अक्षरों को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | निर्दिष्ट कैरेक्टर ऐरे से UTF-16 अक्षरों की निर्दिष्ट सबरेज को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | निर्दिष्ट C-स्ट्रिंग को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) ऑब्जेक्ट के स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फॉर्मेट के अनुसार फॉर्मेट करके लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | डिस्ट्रक्टर। |
## संबंधित देखें

* क्लास [TextWriter](../textwriter/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)