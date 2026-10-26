---
title: TextWriter
second_title: Aspose.Slides for C++ API संदर्भ
description: "विभिन्न गंतव्यों पर अक्षरों की अनुक्रम लिखने वाले राइटर्स का प्रतिनिधित्व करने वाली क्लासों के लिए एक बेस क्लास। इस क्लास के ऑब्जेक्ट को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही अलोकेट किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन में आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 443
url: /hi/system.io/textwriter/
---
## TextWriter क्लास

विभिन्न गंतव्यों पर अक्षरों की अनुक्रम लिखने वाले राइटर्स को दर्शाने वाली क्लासों के लिए एक बेस क्लास।  
[System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही इस क्लास के ऑब्जेक्ट को अलोकेट किया जाना चाहिए।  
स्टैक पर या operator new का उपयोग करके इस प्रकार का इंस्टेंस कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं।  
इस क्लास को हमेशा [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन में आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class TextWriter : public System::IDisposable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual void [Close](./close/)() | स्ट्रीम को बंद करता है और प्राप्त संसाधनों को रिलीज़ करता है। |
| void [Dispose](./dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग की गई सभी संसाधनों को रिलीज़ करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual void [Flush](./flush/)() | बफ़र की सामग्री को अंतर्निहित स्ट्रीम में फ़्लश करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | वर्तमान में उपयोग किए जा रहे एन्कोडिंग को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | वर्तमान में उपयोग किए जा रहे [IFormatProvider](../../system/iformatprovider/) ऑब्जेक्ट को लौटाता है। |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | वर्तमान में उपयोग किए जा रहे [IFormatProvider](../../system/iformatprovider/) ऑब्जेक्ट को लौटाता है। |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | एक लाइन टर्मिनेटर स्ट्रिंग लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | एक लाइन टर्मिनेटर स्ट्रिंग सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**bool**) | निर्दिष्ट बूलियन मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(char_t) | निर्दिष्ट अक्षर को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**double**) | निर्दिष्ट डबल-प्रिसीजन फ़्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(int) | निर्दिष्ट 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**int64_t**) | निर्दिष्ट 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**float**) | निर्दिष्ट सिंगल-प्रिसीजन फ़्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**uint32_t**) | निर्दिष्ट अनसाइनड 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**uint64_t**) | निर्दिष्ट अनसाइनड 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | निर्दिष्ट एरे के सभी कैरेक्टर्स को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | निर्दिष्ट एरे से UTF-16 कैरेक्टर्स की निर्दिष्ट सबरेंज को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const char_t *) | निर्दिष्ट C-स्ट्रिंग को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट फ़ॉर्मेट के अनुसार फ़ॉर्मेटेड मानों को स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)() | लाइन टर्मिनेटर कैरेक्टर्स को स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | निर्दिष्ट ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**bool**) | निर्दिष्ट बूलियन मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(char_t) | निर्दिष्ट अक्षर को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**double**) | निर्दिष्ट डबल-प्रिसीजन फ़्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(int) | निर्दिष्ट 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**int64_t**) | निर्दिष्ट 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**float**) | निर्दिष्ट सिंगल-प्रिसीजन फ़्लोटिंग पॉइंट मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रिंग को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | निर्दिष्ट अनसाइनड 32-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | निर्दिष्ट अनसाइनड 64-बिट इंटीजर मान की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | निर्दिष्ट एरे के सभी कैरेक्टर्स को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | निर्दिष्ट एरे से UTF-16 कैरेक्टर्स की निर्दिष्ट सबरेंज को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const char_t *) | निर्दिष्ट C-स्ट्रिंग को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट फ़ॉर्मेट के अनुसार फ़ॉर्मेटेड मानों को लाइन-टर्मिनेटर कैरेक्टर्स के साथ स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
| virtual  [~TextWriter](./~textwriter/)() | डिस्ट्रक्टर। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के साझा पॉइंटर के लिए एक उपनाम। |

## देखें भी

* क्लास [IDisposable](../../system/idisposable/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)