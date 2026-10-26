---
title: StreamReader
second_title: C++ के लिये Aspose.Slides API संदर्भ
description: "एक रीडर को दर्शाता है जो बाइट स्ट्रीम से अक्षर पढ़ता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या अभिकथन दोषों का कारण बन सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 378
url: /hi/system.io/streamreader/
---
## StreamReader क्लास

एक रीडर को दर्शाता है जो बाइट स्ट्रीम से अक्षर पढ़ता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या अभिकथन दोषों का कारण बन सकता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class StreamReader : public System::IO::TextReader
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Close](./close/)() override | वर्तमान और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual void [Dispose](./dispose/)(**bool**) | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| void [Dispose](./dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | अंतर्निहित स्ट्रीम का प्रतिनिधित्व करने वाले ऑब्जेक्ट के लिए एक साझा पॉइंटर लौटाता है। |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | वर्तमान में उपयोगित एन्कोडिंग को लौटाता है। |
| **bool** [get_EndOfStream](./get_endofstream/)() | एक मान लौटाता है जो दर्शाता है कि क्या स्ट्रीम का अंत पहुँच गया है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| int [Peek](./peek/)() override | स्ट्रीम से एकल अक्षर पढ़ता है बिना स्ट्रीम के रीड कर्सर को बदले। |
| int [Read](./read/)() override | स्ट्रीम से एकल अक्षर पढ़ता है। |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है, उन्हें UTF-16 एन्कोडिंग में बदलता है और परिणामी UTF-16 अक्षरों को निर्दिष्ट स्थिति से शुरू होने वाले निर्दिष्ट कैरेक्टर ऐरे में लिखता है। |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | वर्तमान टेक्स्ट रीडर से निर्दिष्ट अधिकतम संख्या में अक्षर पढ़ता है और डेटा को निर्दिष्ट इंडेक्स से शुरू होने वाले बफ़र में लिखता है। |
| [String](../../system/string/) [ReadLine](./readline/)() override | स्ट्रीम से अक्षर पढ़ता है जब तक वर्तमान पंक्ति का अंत नहीं आ जाता। |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | स्ट्रीम से अक्षर पढ़ता है जब तक स्ट्रीम का अंत नहीं आ जाता। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | UTF-8 एन्कोडिंग और डिफ़ॉल्ट 1024 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | UTF-8 एन्कोडिंग और डिफ़ॉल्ट 1024 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बताता है कि बाइट ऑर्डर मार्क डिटेक्शन सक्षम होना चाहिए या नहीं। |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट 1024 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट 1024 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बाइट ऑर्डर मार्क डिटेक्शन को सक्षम करने का निर्धारण करता है। |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | निर्दिष्ट एन्कोडिंग और निर्दिष्ट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बाइट ऑर्डर मार्क डिटेक्शन को सक्षम करने का निर्धारण करता है। |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | UTF-8 एन्कोडिंग और डिफ़ॉल्ट 4096 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट फ़ाइल से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | UTF-8 एन्कोडिंग और डिफ़ॉल्ट 4096 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट फ़ाइल से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बाइट ऑर्डर मार्क डिटेक्शन को सक्षम करने का निर्धारण करता है। |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट 4096 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट फ़ाइल से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | निर्दिष्ट एन्कोडिंग और डिफ़ॉल्ट 4096 बाइट आकार के बफ़र का उपयोग करके निर्दिष्ट अंतर्निहित स्ट्रीम से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बाइट ऑर्डर मार्क डिटेक्शन को सक्षम करने का निर्धारण करता है। |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | निर्दिष्ट एन्कोडिंग और निर्दिष्ट आकार के बफ़र का उपयोग करके निर्दिष्ट फ़ाइल से अक्षर पढ़ने वाले [StreamReader](./) ऑब्जेक्ट का एक इंस्टेंस बनाता है। एक पैरामीटर बाइट ऑर्डर मार्क डिटेक्शन को सक्षम करने का निर्धारण करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैकल्पिक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैकल्पिक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
|  [~StreamReader](./~streamreader/)() | डिस्ट्रक्टर। |

## देखें

* क्लास [TextReader](../textreader/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)