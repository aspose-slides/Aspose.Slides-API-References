---
title: Details_SoapException
second_title: Aspose.Slides for C++ API संदर्भ
description: "जब SOAP पर मेथड को कॉल किया जाता है और त्रुटि होती है तो फेंके गए अपवाद को दर्शाता है। इस क्लास के उदाहरणों को मैन्युअल रूप से कभी नहीं बनाएं। इसके बजाय SoapException क्लास का उपयोग करें। SoapException क्लास के उदाहरणों को System::SmartPtr में कभी न रैप करें।"
type: docs
weight: 1
url: /hi/system.web.services.protocols/details_soapexception/
---
## Details_SoapException क्लास

SOAP पर विधि को कॉल करने पर और त्रुटि होने पर फेंका गया अपवाद दर्शाता है। इस क्लास के उदाहरणों को मैन्युअल रूप से कभी न बनाएं। इसके बजाय SoapException क्लास का उपयोग करें। SoapException क्लास के उदाहरणों को [System::SmartPtr](../../system/smartptr/) में कभी न रैप करें।

```cpp
class Details_SoapException : public System::Details_SystemException
```

## विधियां

| मेथड | विवरण |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | एक नया उदाहरण बनाता है। |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | एक नया उदाहरण बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN कोई भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [String](../../system/string/) [get_Actor](./get_actor/)() | SOAP संस्करण 1.1 उपयोग किए जाने पर वह कोड हिस्सा लौटाता है जहाँ अपवाद फेंका गया। |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | 'namespace:localname' स्वरूप में नेमस्पेस योग्य स्थानीय नाम लौटाता है जो SOAP फ़ॉल्ट कोड को निर्दिष्ट करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | कस्टम अपवाद डेटा के साथ शब्दकोश लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | फेंके गए अपवाद के बारे में विवरण लौटाता है। |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | 32-बिट पूर्णांक मान लौटाता है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए अपवाद से संबंधित HRESULT कोड है। |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | आंतरिक अपवाद को दर्शाने वाले ऑब्जेक्ट का रेफरेंस लौटाता है। |
| [String](../../system/string/) [get_Lang](./get_lang/)() | वह भाषा लौटाता है जिसका उपयोग अपवाद गुणों को स्थानीयकृत करने के लिये किया जाता है। |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | त्रुटि विवरण वाली स्ट्रिंग लौटाता है। |
| [String](../../system/string/) [get_Node](./get_node/)() | SOAP संस्करण 1.2 उपयोग किए जाने पर वह कोड हिस्सा लौटाता है जहाँ अपवाद फेंका गया। |
| [String](../../system/string/) [get_Role](./get_role/)() | वह XML वेब सेवा की भूमिका लौटाता है जो अपवाद फेंकती है। |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | स्टैक ट्रेस वाली स्ट्रिंग लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | 'subcode' XML तत्व से वैकल्पिक जानकारी लौटाता है। |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | सबसे अंदरूनी अपवाद को प्रदर्शित करने वाले Exception ऑब्जेक्ट की कॉपी लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफरेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | निर्दिष्ट कोड 'Client' SOAP फ़ॉल्ट कोड के बराबर है या नहीं जाँचता है। |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | निर्दिष्ट कोड 'MustUnderstand' SOAP फ़ॉल्ट कोड के बराबर है या नहीं जाँचता है। |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | निर्दिष्ट कोड 'Server' SOAP फ़ॉल्ट कोड के बराबर है या नहीं जाँचता है। |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | निर्दिष्ट कोड 'VersionMismatch' SOAP फ़ॉल्ट कोड के बराबर है या नहीं जाँचता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने के लिये सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारंभ करता है और उपवर्गों की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | साझा रेफ़रेंस काउंट को निर्दिष्ट मान द्वारा घटाता है। |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | HRESULT सेट करता है, जो विशिष्ट अपवाद को सौंपा गया कोडेड संख्यात्मक मान है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्प्लेट आर्गुमेंट को कमजोर पॉइंटर (साझा नहीं) बनाता है। कंटेनर में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर का मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual const char * [what](../../system/details_exception/what/)() const | [what()](../../system/details_exception/what/) मेथड को लागू करता है जिसे [ExceptionWrapper](../../system/exceptionwrapper/) क्लास द्वारा बुलाया जाता है। यद्यपि यह क्लास std::exception से नहीं विरासत में मिली है, डेराइव्ड क्लासेस इस मेथड को लागू करने के लिये protected/private सदस्यों का उपयोग कर सकते हैं। इस मेथड का कार्यान्वयन [ExceptionWrapper](../../system/exceptionwrapper/) में ले जाने से वह लॉजिक टूट सकता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | एक SOAP फ़ॉल्ट कोड जो क्लाइंट कॉल को दर्शाता है जो गलत फ़ॉर्मेटेड है या आवश्यक जानकारी नहीं रखता। |
| static [DetailElementName](./detailelementname/) | 'namespace:localname' स्वरूप में नेमस्पेस योग्य स्थानीय नाम। |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | एक SOAP फ़ॉल्ट कोड जो संकेत देता है कि 'MustUnderstand' एट्रिब्यूट वाले SOAP तत्व को प्रोसेस नहीं किया गया। |
| static [ServerFaultCode](./serverfaultcode/) | एक SOAP फ़ॉल्ट कोड जो सर्वर पर हुई त्रुटि को दर्शाता है। |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | एक SOAP फ़ॉल्ट कोड जो अमान्य नेमस्पेस को दर्शाता है। |

## देखें

* क्लास [Details_SystemException](../../system/details_systemexception/)
* नेमस्पेस [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)