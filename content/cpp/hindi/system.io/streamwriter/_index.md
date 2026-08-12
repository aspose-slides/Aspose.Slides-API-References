---
title: StreamWriter
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "ऐसे राइटर का प्रतिनिधित्व करता है जो अक्षरों को बाइट स्ट्रीम में लिखता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रन-टाइम त्रुटियां और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों के तर्क के रूप में पास करें।"
type: docs
weight: 391
url: /hi/system.io/streamwriter/
---
## StreamWriter क्लास

अक्षरों को बाइट स्ट्रीम में लिखने वाला एक राइटर दर्शाता है। इस क्लास के ऑब्जेक्ट को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रन-टाइम त्रुटियां और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों के तर्क के रूप में पास करें।

```cpp
class StreamWriter : public System::IO::TextWriter
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Close](./close/)() override | स्ट्रीम को बंद करता है और प्राप्त संसाधनों को मुक्त करता है। |
| void [Dispose](./dispose/)() override | वर्तमान वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual void [Dispose](./dispose/)(**bool**) | वर्तमान वस्तु द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और अंतर्निहित स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, साथ ही NaN भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, साथ ही NaN भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [Flush](./flush/)() override | बफ़र की सामग्री को अंतर्निहित स्ट्रीम में फ़्लश करता है और फिर अंतर्निहित स्ट्रीम को फ़्लश करता है। |
| **bool** [get_AutoFlush](./get_autoflush/)() const | एक मान लौटाता है जो दर्शाता है कि [StreamWriter](./) प्रत्येक बार जब मेथड [StreamWriter::Write](./write/) को कॉल किया जाता है तो डेटा को अंतर्निहित स्ट्रीम में फ़्लश करेगा या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | अंतर्निहित स्ट्रीम का प्रतिनिधित्व करने वाली वस्तु के लिए एक साझा पॉइंटर लौटाता है। |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | वर्तमान में उपयोग की जा रही एन्कोडिंग लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | वर्तमान में उपयोग की जा रही [IFormatProvider](../../system/iformatprovider/) वस्तु लौटाता है। |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | वर्तमान में उपयोग की जा रही [IFormatProvider](../../system/iformatprovider/) वस्तु लौटाता है। |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | एक लाइन समाप्त करने वाली स्ट्रिंग लौटाता है। |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | एक लाइन समाप्त करने वाली स्ट्रिंग लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का analog। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का analog। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँच करे कि वस्तु targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का analog। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का analog। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | एक मान लौटाता है जो दर्शाता है कि [StreamWriter](./) प्रत्येक बार जब मेथड [StreamWriter::Write](./write/) को कॉल किया जाता है तो डेटा को अंतर्निहित स्ट्रीम में फ़्लश करेगा या नहीं। |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | एक लाइन समाप्ति स्ट्रिंग सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर mode में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | निर्दिष्ट अंतर्निहित स्ट्रिम में UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स वाले बफ़र के साथ अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स वाले बफ़र के साथ निर्दिष्ट अंतर्निहित स्ट्रिम में अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | निर्दिष्ट एन्कोडिंग का उपयोग करके और निर्दिष्ट आकार के बफ़र के साथ निर्दिष्ट अंतर्निहित स्ट्रिम में अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। एक पैरामीटर निर्धारित करता है कि जब [StreamWriter](./) वस्तु को डिस्पोज़ किया जाए तो अंतर्निहित स्ट्रिम को बंद करना चाहिए या नहीं। |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | UTF-8 एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स वाले बफ़र के साथ निर्दिष्ट फ़ाइल में अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | निर्दिष्ट एन्कोडिंग का उपयोग करके और डिफ़ॉल्ट आकार 1024 बाइट्स वाले बफ़र के साथ निर्दिष्ट फ़ाइल में अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। एक पैरामीटर यह निर्धारित करता है कि डेटा फ़ाइल में जोड़ना है या फ़ाइल को अधिलेखित करना है। |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | निर्दिष्ट एन्कोडिंग और बफ़र आकार के साथ निर्दिष्ट फ़ाइल में अक्षर लिखने वाला [StreamWriter](./) वस्तु का एक इंस्टेंस बनाता है। एक पैरामीटर यह निर्धारित करता है कि डेटा फ़ाइल में जोड़ना है या फ़ाइल को अधिलेखित करना है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का analog। कस्टम वस्तुओं को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(char_t) override | निर्दिष्ट अक्षर को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [String](../../system/string/)\&) override | निर्दिष्ट स्ट्रिंग को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | निर्दिष्ट वस्तु के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | निर्दिष्ट एरे के सभी अक्षर स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट अक्षर एरे से UTF-16 अक्षरों की निर्दिष्ट उप-सीमा को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const char_t *) override | निर्दिष्ट c-स्ट्रींग को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | निर्दिष्ट वस्तु के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**bool**) | निर्दिष्ट बूलियन मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) वस्तु के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**double**) | निर्दिष्ट डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(int) | निर्दिष्ट 32-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**int64_t**) | निर्दिष्ट 64-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**float**) | निर्दिष्ट सिंगल-प्रेसिशन फ़्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | निर्दिष्ट अनसाइनड 32-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | निर्दिष्ट अनसाइनड 64-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) वस्तु के स्ट्रिंग प्रतिनिधित्व को स्ट्रीम में लिखता है। |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फ़ॉर्मेट के अनुसार फॉर्मेट करके स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)() override | लाइन समाप्ति अक्षरों को स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | निर्दिष्ट स्ट्रिंग को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | निर्दिष्ट वस्तु के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | निर्दिष्ट एरे के सभी अक्षर को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट अक्षर एरे से UTF-16 अक्षरों की निर्दिष्ट उप-सीमा को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const char_t *) override | निर्दिष्ट c-स्ट्रींग को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | निर्दिष्ट वस्तु के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | निर्दिष्ट बूलियन मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | निर्दिष्ट अक्षर को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | निर्दिष्ट [Decimal](../../system/decimal/) वस्तु के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | निर्दिष्ट डबल-प्रेसिशन फ़्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(int) | निर्दिष्ट 32-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | निर्दिष्ट 64-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | निर्दिष्ट सिंगल-प्रेसिशन फ़्लोटिंग पॉइंट मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | निर्दिष्ट अनसाइनड 32-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | निर्दिष्ट अनसाइनड 64-बिट इंटेज़र मान के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट [TypeInfo](../../system/typeinfo/) वस्तु के स्ट्रिंग प्रतिनिधित्व को लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | निर्दिष्ट मानों को निर्दिष्ट फ़ॉर्मेट के अनुसार फॉर्मेट करके लाइन-समाप्ति अक्षरों के साथ स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
|  [~StreamWriter](./~streamwriter/)() | Destructor. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructor. |

## देखें भी

* क्लास [TextWriter](../textwriter/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)