---
title: Details_ArgumentNullException
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 339
url: /hi/system/details_argumentnullexception/
---
## Details_ArgumentNullException क्लास




```cpp
class Details_ArgumentNullException : public System::Details_ArgumentException
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सिमेंटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | कस्टम अपवाद डेटा के साथ शब्दकोश लौटाता है। |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए अपवाद से जुड़ा HRESULT कोड वाला 32-बिट पूर्णांक मान लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | आंतरिक अपवाद को दर्शाने वाली वस्तु का संदर्भ लौटाता है। |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | त्रुटि विवरण शामिल करने वाली स्ट्रिंग लौटाता है। |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | स्टैक ट्रेस वाली स्ट्रिंग लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | सबसे आंतरिक अपवाद को दर्शाने वाली Exception वस्तु की प्रतिलिपि लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) विधि का समांतर। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समांतर। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) विधि का समांतर। कस्टम प्रकारों की क्लोनीयिंग को सक्षम करता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नई वस्तु को प्रारम्भ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नई वस्तु को प्रारम्भ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT को सेट करता है, जो एक कोडित संख्यात्मक मान है जो एक विशिष्ट अपवाद को सौंपा जाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'tवें टेम्प्लेट आर्ग्यूमेंट को एक वैक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वैक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वैक रेफ़रेंस काउंटर को बढ़ाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वैक रेफ़रेंस काउंटर को घटाता है। सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) विधि को लागू करता है जिसे [ExceptionWrapper](../exceptionwrapper/) क्लास द्वारा कॉल किया जाता है। जबकि यह क्लास std::exception से विरासत में नहीं मिला है, डेरिव्ड क्लासेस संरक्षित/निजी सदस्य का उपयोग करके अपना तर्क लागू कर सकते हैं। इस विधि का कार्यान्वयन [ExceptionWrapper](../exceptionwrapper/) में ले जाने से वह तर्क बिगड़ सकता है। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [Details_ArgumentException](../details_argumentexception/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)