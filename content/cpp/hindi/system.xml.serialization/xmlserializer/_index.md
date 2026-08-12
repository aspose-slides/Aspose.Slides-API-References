---
title: XmlSerializer
second_title: Aspose.Slides for C++ API संदर्भ
description: "ऑब्जेक्ट्स को XML दस्तावेज़ में तथा उनसे क्रमबद्ध (सीरियलाइज़) और पुनः क्रमबद्ध (डीसीरियलाइज़) करता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शन को तर्क के रूप में पास करने के लिए उपयोग करें।"
type: docs
weight: 66
url: /hi/system.xml.serialization/xmlserializer/
---
## XmlSerializer क्लास

Performs serialization and deserialization of objects into and from XML documents. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class XmlSerializer : public System::Object
```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [CanDeserialize](./candeserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | जाँचता है कि विशिष्ट रीडर डीसिरियलाइज़ेबल स्थिति में है या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>, [String](../../system/string/)) | XML दस्तावेज़ को ऑब्जेक्ट में डीसिरियलाइज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अभिप्राय का उपयोग करके ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उद्देश्यों के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप का क्लोन बनाना सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/)) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/), [String](../../system/string/)) | दस्तावेज़ को XML में सिरीयलाइज़ करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को कमजोर पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट को स्ट्रिंग में कन्वर्ट करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वींक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वींक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | एन्कोडिंग नेमस्पेस का नाम। |
| static [WsdlNamespace](./wsdlnamespace/) | WSDL नेमस्पेस का नाम। |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | WSDL टाइप्स नेमस्पेस का नाम। |
## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Xml::Serialization](../)
* लाइब्रेरी [Aspose.Slides](../../)