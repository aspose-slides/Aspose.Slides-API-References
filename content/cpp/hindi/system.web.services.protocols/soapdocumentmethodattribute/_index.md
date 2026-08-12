---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "निर्दिष्ट करता है कि मेथड से पास या वापस किए गए सभी SOAP संदेश Document फ़ॉर्मेटिंग का उपयोग करते हैं। इस वर्ग के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 53
url: /hi/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute वर्ग


निर्दिष्ट करता है कि इस मेथड से पास या लौटाए जाने वाले सभी SOAP संदेश Document फॉर्मेटिंग का उपयोग करते हैं। इस वर्ग के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमींटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली वाला फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली वाला फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [String](../../system/string/) [get_Action](./get_action/)() | 'SOAPAction' एट्रिब्यूट का मान प्राप्त करता है। |
| [String](../../system/string/) [get_Binding](./get_binding/)() | उस बाइंडिंग को प्राप्त करता है जिसके लिए XML वेब सेवा मेथड एक ऑपरेशन लागू कर रहा है। |
| **bool** [get_OneWay](./get_oneway/)() | एक मान प्राप्त करता है जो दर्शाता है कि क्लाइंट सर्वर के मेथड प्रोसेसिंग समाप्त होने का इंतज़ार नहीं करता। |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | 'Body' एलेमेंट के नीचे पैरामीटर एक एकल XML एलेमेंट के भीतर संलग्न हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | SOAP अनुरोध से जुड़ा XML एलेमेंट का नाम प्राप्त करता है, जो सेवा विवरण में एक ऑपरेशन के रूप में परिभाषित है। |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | SOAP अनुरोध से जुड़ा नेमस्पेस प्राप्त करता है। |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | SOAP प्रतिक्रिया से जुड़ा XML एलेमेंट का नाम प्राप्त करता है। |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | SOAP प्रतिक्रिया से जुड़ा नेमस्पेस प्राप्त करता है। |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | संदेश एन्कोडिंग विधि निर्धारित करने वाला मान प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट प्रकार पर लागू कस्टम एट्रिब्यूट को लौटाता है। |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | निर्दिष्ट प्रकार पर लागू सभी कस्टम एट्रिब्यूट्स लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Action](./set_action/)([String](../../system/string/)) | 'SOAPAction' एट्रिब्यूट का मान सेट करता है। |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | XML वेब सर्विस मेथड के लिए बाइंडिंग सेट करता है जिससे ऑपरेशन लागू हो रहा है। |
| void [set_OneWay](./set_oneway/)(**bool**) | ऐसा मान सेट करता है जो दर्शाता है कि क्लाइंट सर्वर के मेथड प्रोसेसिंग समाप्त होने का इंतज़ार नहीं करता। |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | ऐसा मान सेट करता है जो दर्शाता है कि पैरामीटर 'Body' एलेमेंट के नीचे एकल XML एलेमेंट में सम्मिलित हैं। |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | SOAP अनुरोध से जुड़े XML एलेमेंट का नाम सेट करता है, जो सेवा विवरण में ऑपरेशन के रूप में परिभाषित है। |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | SOAP अनुरोध से जुड़े नेमस्पेस को सेट करता है। |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | SOAP प्रतिक्रिया से जुड़े XML एलेमेंट का नाम सेट करता है। |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | SOAP प्रतिक्रिया से जुड़े नेमस्पेस को सेट करता है। |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | ऐसा मान सेट करता है जो संदेश एन्कोडिंग विधि निर्धारित करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनर में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और वापस करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | एक नया इंस्टेंस बनाता है। |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## देखें

* वर्ग [Attribute](../../system/attribute/)
* नामस्थान [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)