---
title: Details_OperationCanceledException
second_title: Aspose.Slides for C++ API संदर्भ
description: "OperationCanceledException को एक थ्रेड में तब फेंका जाता है जब वह थ्रेड चलाए जा रहे ऑपरेशन को रद्द किया जाता है। इस क्लास के इंस्टेंस को मैन्युअल रूप से कभी न बनाएँ। उसके बजाय OperationCanceledException क्लास का उपयोग करें। OperationCanceledException क्लास के इंस्टेंस को कभी भी System::SmartPtr में नहीं लपेटें।"
type: docs
weight: 625
url: /hi/system/details_operationcanceledexception/
---
## Details_OperationCanceledException कक्षा


OperationCanceledException थ्रेड में तब फेंका जाता है जब उस थ्रेड द्वारा चलाए जा रहे ऑपरेशन को रद्द किया जाता है। इस कक्षा के इंस्टेंस को मैन्युअल रूप से कभी न बनाएँ। इसके बजाय OperationCanceledException कक्षा का उपयोग करें। OperationCanceledException कक्षा के इंस्टेंस को कभी भी [System::SmartPtr](../smartptr/) में नहीं लपेटें।

```cpp
class Details_OperationCanceledException : public System::Details_SystemException
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | कस्टम एक्सेप्शन डेटा के साथ शब्दकोश लौटाता है। |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | एक 32-बिट पूर्णांक मान लौटाता है जो वर्तमान ऑब्जेक्ट द्वारा दर्शाई गई अपवाद से जुड़ा HRESULT कोड है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | आंतरिक अपवाद को दर्शाने वाले ऑब्जेक्ट का रेफरेंस लौटाता है। |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | त्रुटि विवरण युक्त स्ट्रिंग लौटाता है। |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | स्टैक ट्रेस युक्त स्ट्रिंग लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | आंतरिक-सबसे गहरी अपवाद को दर्शाने वाले Exception ऑब्जेक्ट की कॉपी लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउन्टर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समान रूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समान रूप। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समान रूप। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफरेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT सेट करता है, जो एक कोडेड संख्यात्मक मान है जो विशेष अपवाद को सौंपा जाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को वैक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वैक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफरेंस काउंटर की वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वैक रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वैक रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) मेथड को लागू करता है जिसे [ExceptionWrapper](../exceptionwrapper/) क्लास द्वारा कॉल किया जाता है। तथ्य के बावजूद कि यह क्लास std::exception से विरासत में नहीं लेती है, डेराइव्ड क्लासेस प्रोटेक्टेड/प्राइवेट मेंबर्स का उपयोग कर अपनी लॉजिक लागू कर सकती हैं। इस मेथड इम्प्लीमेंटेशन को [ExceptionWrapper](../exceptionwrapper/) में ले जाने से वह लॉजिक टूट सकता है। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* कक्षा [Details_SystemException](../details_systemexception/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)