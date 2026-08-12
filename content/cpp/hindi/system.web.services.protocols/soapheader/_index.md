---
title: SoapHeader
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "SOAP हेडर की सामग्री का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन दोष हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 79
url: /hi/system.web.services.protocols/soapheader/
---
## SoapHeader क्लास


SOAP हेडर की सामग्री का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class SoapHeader : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [String](../../system/string/) [get_Actor](./get_actor/)() | जब SOAP संस्करण 1.1 उपयोग किया जाता है, तब SOAP हेडर प्राप्तकर्ता का URI प्राप्त करता है। |
| **bool** [get_DidUnderstand](./get_didunderstand/)() | एक मान प्राप्त करता है जो दर्शाता है कि क्या SOAP हेडर सही ढंग से प्रोसेस किया गया है। |
| [String](../../system/string/) [get_EncodedMustUnderstand](./get_encodedmustunderstand/)() | जब SOAP संस्करण 1.1 उपयोग किया जाता है, तब 'mustUnderstand' विशेषता का मान प्राप्त करता है। |
| [String](../../system/string/) [get_EncodedMustUnderstand12](./get_encodedmustunderstand12/)() | जब SOAP संस्करण 1.2 उपयोग किया जाता है, तब 'mustUnderstand' विशेषता का मान प्राप्त करता है। |
| [String](../../system/string/) [get_EncodedRelay](./get_encodedrelay/)() | 'relay' विशेषता मान की स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| **bool** [get_MustUnderstand](./get_mustunderstand/)() | एक मान प्राप्त करता है जो दर्शाता है कि क्या SOAP हेडर को समझा जाना अनिवार्य है। |
| **bool** [get_Relay](./get_relay/)() | 'relay' विशेषता का मान प्राप्त करता है। |
| [String](../../system/string/) [get_Role](./get_role/)() | जब SOAP संस्करण 1.2 उपयोग किया जाता है, तब SOAP हेडर प्राप्तकर्ता का URI प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक इंस्टेंस दर्शाता है। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Actor](./set_actor/)([String](../../system/string/)) | जब SOAP संस्करण 1.1 उपयोग किया जाता है, तब SOAP हेडर प्राप्तकर्ता का URI सेट करता है। |
| void [set_DidUnderstand](./set_didunderstand/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि क्या SOAP हेडर सही ढंग से प्रोसेस किया गया है। |
| void [set_EncodedMustUnderstand](./set_encodedmustunderstand/)([String](../../system/string/)) | जब SOAP संस्करण 1.1 उपयोग किया जाता है, तब 'mustUnderstand' विशेषता का मान सेट करता है। |
| void [set_EncodedMustUnderstand12](./set_encodedmustunderstand12/)([String](../../system/string/)) | जब SOAP संस्करण 1.2 उपयोग किया जाता है, तब 'mustUnderstand' विशेषता का मान सेट करता है। |
| void [set_EncodedRelay](./set_encodedrelay/)([String](../../system/string/)) | 'relay' विशेषता मान की स्ट्रिंग प्रतिनिधित्व सेट करता है। |
| void [set_MustUnderstand](./set_mustunderstand/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि क्या SOAP हेडर को समझा जाना आवश्यक है। |
| void [set_Relay](./set_relay/)(**bool**) | 'relay' विशेषता का मान सेट करता है। |
| void [set_Role](./set_role/)([String](../../system/string/)) | जब SOAP संस्करण 1.2 उपयोग किया जाता है, तब SOAP हेडर प्राप्तकर्ता का URI सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बजाय इसके, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; बजाय इसके, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [SoapHeader](./soapheader/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlElement](../../system.xml/xmlelement/)\>) | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बजाय इसके, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; बजाय इसके, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)