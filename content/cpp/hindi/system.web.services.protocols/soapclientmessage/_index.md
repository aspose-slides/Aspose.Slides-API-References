---
title: SoapClientMessage
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "एक भेजी गई SOAP अनुरोध या प्राप्त SOAP प्रतिक्रिया में डेटा का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ उत्पन्न हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 40
url: /hi/system.web.services.protocols/soapclientmessage/
---
## SoapClientMessage क्लास

Represents the data in a SOAP request sent or a SOAP response received. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapClientMessage : public System::Web::Services::Protocols::SoapMessage
```

## विधियाँ

| Method | Description |
| --- | --- |
| void [CollectHeaders](../soapmessage/collectheaders/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, [SoapHeaderDirection](../soapheaderdirection/)) | SOAP हेडर के आंतरिक संग्रह को सेट करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | वस्तुओं की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\> [FindHeader](../soapmessage/findheader/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>, const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट हेडर प्रकार द्वारा हेडर मैपिंग खोजें। |
| [String](../../system/string/) [get_Action](./get_action/)() override | 'SOAPAction' विशेषता का मान लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\> [get_Client](./get_client/)() | क्लाइंट प्रॉक्सी क्लास का एक इंस्टेंस लौटाता है। |
| [String](../../system/string/) [get_ContentEncoding](../soapmessage/get_contentencoding/)() | 'Content-Encoding' हेडर का मान प्राप्त करता है। |
| [String](../../system/string/) [get_ContentType](../soapmessage/get_contenttype/)() | 'Content-Type' हेडर का मान प्राप्त करता है। |
| [SoapException](../soapexception/) [get_Exception](../soapmessage/get_exception/)() | XML [Web](../../system.web/) सेवा मेथड द्वारा फेंकी गई अपवाद प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\> [get_Headers](../soapmessage/get_headers/)() | SOAP हेडर के संग्रह को लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_InParameters](../soapmessage/get_inparameters/)() | XML [Web](../../system.web/) सेवा मेथड में पास किए गए पैरामीटर प्राप्त करता है। |
| **bool** [get_IsSoap12](../soapmessage/get_issoap12/)() | एक मान लौटाता है जो दर्शाता है कि SOAP संस्करण 1.2 उपयोग किया गया है। |
| virtual **bool** [get_OneWay](./get_oneway/)() | एक मान लौटाता है जो दर्शाता है कि क्लाइंट सर्वर के मेथड प्रोसेस पूर्ण होने की प्रतीक्षा नहीं करता। |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_OutParameters](../soapmessage/get_outparameters/)() | XML [Web](../../system.web/) सेवा मेथड में पास किए गए आउटपुट पैरामीटर प्राप्त करता है। |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() override | उपयोग किए जा रहे SOAP संस्करण को लौटाता है। |
| [SoapMessageStage](../soapmessagestage/) [get_Stage](../soapmessage/get_stage/)() | SOAP संदेश की प्रोसेसिंग स्टेज प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [get_Stream](../soapmessage/get_stream/)() | SOAP संदेश डेटा को समाहित करने वाला स्ट्रीम प्राप्त करता है। |
| [String](../../system/string/) [get_Url](./get_url/)() override | XML [Web](../../system.web/) सेवा URL लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetInParameterValue](../soapmessage/getinparametervalue/)(**int32_t**) | निर्दिष्ट इंडेक्स पर इनपुट पैरामीटर मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetOutParameterValue](../soapmessage/getoutparametervalue/)(**int32_t**) | निर्दिष्ट इंडेक्स पर आउटपुट पैरामीटर मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetReturnValue](../soapmessage/getreturnvalue/)() | XML [Web](../../system.web/) सेवा मेथड का रिटर्न वैल्यू प्राप्त करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट को रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट को nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट घटाता है। |
| void [set_ContentEncoding](../soapmessage/set_contentencoding/)([String](../../system/string/)) | 'Content-Encoding' हेडर का मान सेट करता है। |
| void [set_ContentType](../soapmessage/set_contenttype/)([String](../../system/string/)) | 'Content-Type' हेडर का मान सेट करता है। |
| void [set_InParameters](../soapmessage/set_inparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | XML [Web](../../system.web/) सेवा मेथड में पास किए गए पैरामीटर सेट करता है। |
| void [set_InternalStream](../soapmessage/set_internalstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | SOAP संदेश डेटा को समाहित करने वाला स्ट्रीम सेट करता है। |
| void [set_OutParameters](../soapmessage/set_outparameters/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | XML [Web](../../system.web/) सेवा मेथड में पास किए गए आउटपुट पैरामीटर सेट करता है। |
| void [SetException](../soapmessage/setexception/)([SoapException](../soapexception/)) | XML [Web](../../system.web/) सेवा मेथड द्वारा फेंकी गई अपवाद सेट करता है। |
| void [SetHeaders](../soapmessage/setheaders/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHeaderCollection](../soapheadercollection/)\>) | SOAP हेडर के संग्रह को सेट करता है। |
| void [SetStage](../soapmessage/setstage/)([SoapMessageStage](../soapmessagestage/)) | SOAP संदेश की प्रोसेसिंग स्टेज सेट करता है। |
| void [SetStream](../soapmessage/setstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | SOAP संदेश डेटा को समाहित करने वाला स्ट्रीम सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक वेक प्वाइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर्स में पॉइंटर को वेक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [SoapClientMessage](./soapclientmessage/)([System::SharedPtr](../../system/sharedptr/)\<[SoapHttpClientProtocol](../soaphttpclientprotocol/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapMethodStubInfo\>, [String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | एक नया इंस्टेंस बनाता है। |
|  [SoapMessage](../soapmessage/soapmessage/)() | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| void [UpdateHeaderValues](../soapmessage/updateheadervalues/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<SoapHeaderMapping\>\>) | SOAP हेडर के आंतरिक संग्रह को अपडेट करता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वेक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वेक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [SoapMessage](../soapmessage/)
* नेमस्पेस [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)