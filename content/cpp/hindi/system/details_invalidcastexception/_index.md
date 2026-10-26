---
title: Details_InvalidCastException
second_title: Aspose.Slides for C++ API संदर्भ
description: "InvalidCastException तब फेंका जाता है जब अमान्य स्पष्ट रूपांतरण के अमान्य कास्टिंग ऑपरेशन का प्रयास किया जाता है। इस क्लास की उदाहरणें मैन्युअली कभी न बनाएं। इसके बजाय InvalidCastException क्लास का उपयोग करें। InvalidCastException क्लास की उदाहरणों को कभी भी System::SmartPtr में न लपेटें।"
type: docs
weight: 495
url: /hi/system/details_invalidcastexception/
---
## Details_InvalidCastException क्लास

InvalidCastException तब फेंकी जाती है जब अमान्य स्पष्ट रूपांतरण के अमान्य कास्टिंग संचालन का प्रयास किया जाता है। इस क्लास की उदाहरणें मैन्युअली कभी न बनाएँ। इसके बजाय InvalidCastException क्लास का उपयोग करें। InvalidCastException क्लास की उदाहरणों को कभी भी [System::SmartPtr](../smartptr/) में न लपेटें।

```cpp
class Details_InvalidCastException : public System::Details_SystemException
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | कस्टम अपवाद डेटा के साथ शब्दकोश लौटाता है। |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | वर्तमान ऑब्जेक्ट द्वारा दर्शाए गए अपवाद से संबंधित HRESULT कोड वाला 32-बिट पूर्णांक मान लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | आंतरिक अपवाद को दर्शाने वाले ऑब्जेक्ट का संदर्भ लौटाता है। |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | त्रुटि विवरण वाली स्ट्रिंग लौटाता है। |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | स्टैक ट्रेस वाली स्ट्रिंग लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | सबसे अंदरूनी अपवाद को दर्शाने वाले Exception ऑब्जेक्ट की कॉपी लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ऑब्जेक्ट से जुड़ी संदर्भ काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानांतर। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को आरंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सब-क्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और सब-क्लास की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT सेट करता है, जो एक कोडेड संख्यात्मक मान है जो एक विशिष्ट अपवाद को सौंपा जाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक वैक्लिप पॉइंटर सेट करता है (साझा के बजाय)। कंटेनरों में पॉइंटर को वैक्लिप मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | वर्तमान ऑब्जेक्ट की स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वैक्लिप रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वैक्लिप रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का प्रयोग करें। |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) मेथड को लागू करता है जिसे [ExceptionWrapper](../exceptionwrapper/) क्लास द्वारा बुलाया जाता है। यह तथ्य कि यह क्लास std::exception से विरासत में नहीं मिला है, इसके बावजूद डेरिव्ड क्लासेस प्रोटेक्टेड/प्राइवेट मेंबर्स का उपयोग करके अपनी लॉजिक को लागू कर सकते हैं। इस मेथड की कार्यान्वयन को [ExceptionWrapper](../exceptionwrapper/) में स्थानांतरित करने से वह लॉजिक टूट सकता है। |
| virtual  [~Object](../object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## संबंधित देखें

* क्लास [Details_SystemException](../details_systemexception/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)