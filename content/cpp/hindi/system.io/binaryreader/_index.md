---
title: BinaryReader
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक रीडर का प्रतिनिधित्व करता है जो प्रिमिटिव डेटा टाइप्स को विशेष एन्कोडिंग में बाइनरी डेटा के रूप में पढ़ता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम एरर और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में घेरें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 92
url: /hi/system.io/binaryreader/
---
## BinaryReader क्लास

एक रीडर का प्रतिनिधित्व करता है जो प्रिमिटिव डेटा टाइप्स को विशेष एन्कोडिंग में बाइनरी डेटा के रूप में पढ़ता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम एरर और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में घेरें और इस पॉइंटर का उपयोग फ़ंक्शन के आर्ग्यूमेंट के रूप में पास करने के लिए करें।

```cpp
class BinaryReader : public System::IDisposable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | [BinaryReader](./) क्लास की एक इंस्टेंस बनाता है जो निर्दिष्ट स्ट्रीम से डेटा पढ़ता है UTF-8 एन्कोडिंग का उपयोग करके। |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | [BinaryReader](./) क्लास की एक इंस्टेंस बनाता है जो निर्दिष्ट स्ट्रीम से डेटा पढ़ता है निर्दिष्ट एन्कोडिंग का उपयोग करके। |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | [BinaryReader](./) क्लास की एक इंस्टेंस बनाता है जो निर्दिष्ट स्ट्रीम से डेटा पढ़ता है निर्दिष्ट एन्कोडिंग का उपयोग करके। |
| virtual void [Close](./close/)() | वर्तमान [BinaryReader](./) ऑब्जेक्ट और अंतर्निहित इनपुट स्ट्रीम को बंद करता है। |
| void [Dispose](./dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधन जारी करता है और आधारभूत स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | इनपुट स्ट्रीम लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी निर्माण को सक्षम करता है। |
| virtual int [PeekChar](./peekchar/)() | इनपुट स्ट्रीम से एक एकल अक्षर पढ़ता है बिना स्ट्रीम के रीड कर्सर को बदले। |
| virtual int [Read](./read/)() | इनपुट स्ट्रीम से एक एकल अक्षर पढ़ता है। |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | इनपुट स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | इनपुट स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है, उन्हें UTF-16 एन्कोडिंग में बदलता है और परिणामस्वरूप UTF-16 अक्षर को निर्दिष्ट स्थिति से शुरू होते हुए निर्दिष्ट कैरेक्टर एरे में लिखता है। |
| virtual **bool** [ReadBoolean](./readboolean/)() | इनपुट स्ट्रीम से एक बाइट पढ़ता है और उसका बूलियन प्रतिनिधित्व लौटाता है। |
| virtual **uint8_t** [ReadByte](./readbyte/)() | इनपुट स्ट्रीम से एक बाइट पढ़ता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | इनपुट स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है। |
| virtual char_t [ReadChar](./readchar/)() | इनपुट स्ट्रीम से एक एकल अक्षर पढ़ता है। |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | इनपुट स्ट्रीम से निर्दिष्ट संख्या में अक्षर पढ़ता है और उन्हें UTF-16 एन्कोडिंग में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | अमल में नहीं लाई गई। |
| virtual **double** [ReadDouble](./readdouble/)() | इनपुट स्ट्रीम से 8 बाइट्स पढ़ता है और उन्हें डबल-प्रेसिशन फ्लोटिंग पॉइंट मान के रूप में लौटाता है। |
| virtual **int16_t** [ReadInt16](./readint16/)() | इनपुट स्ट्रीम से 2 बाइट्स पढ़ता है और उन्हें 16-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual int [ReadInt32](./readint32/)() | इनपुट स्ट्रीम से 4 बाइट्स पढ़ता है और उन्हें 32-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual **int64_t** [ReadInt64](./readint64/)() | इनपुट स्ट्रीम से 8 बाइट्स पढ़ता है और उन्हें 64-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | इनपुट स्ट्रीम से एक बाइट पढ़ता है और उसे साइन्ड 8-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual **float** [ReadSingle](./readsingle/)() | इनपुट स्ट्रीम से 4 बाइट्स पढ़ता है और उन्हें सिंगल-प्रेसिशन फ्लोटिंग पॉइंट मान के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | वर्तमान स्ट्रीम से एक स्ट्रिंग पढ़ता है। स्ट्रिंग की लम्बाई पहले रखी जाती है, जिसे सात बिट्स के समूह में एन्कोड किया गया पूर्णांक है। |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | इनपुट स्ट्रीम से 2 बाइट्स पढ़ता है और उन्हें अनसाइन्ड 16-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | इनपुट स्ट्रीम से 4 बाइट्स पढ़ता है और उन्हें अनसाइन्ड 32-बिट पूर्णांक मान के रूप में लौटाता है। |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | इनपुट स्ट्रीम से 8 बाइट्स पढ़ता है और उन्हें अनसाइन्ड 64-बिट पूर्णांक मान के रूप में लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है मूल्य प्रकार ऑब्जेक्ट की nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को वीक पॉइंटर सेट करता है (शेयरड के बजाय)। कंटेनर्स में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर के वर्तमान मान को प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~BinaryReader](./~binaryreader/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)