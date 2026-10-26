---
title: Details_UriFormatException
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "जब URI का स्वरूप वैध नहीं होता है, तब UriFormatException फेंका जाता है। इस क्लास की उदाहरणें मैन्युअल रूप से कभी न बनाएँ। इसके बजाय UriFormatException क्लास का उपयोग करें। UriFormatException क्लास की उदाहरणों को कभी भी System::SmartPtr में न लपेटें।"
type: docs
weight: 768
url: /hi/system/details_uriformatexception/
---
## Details_UriFormatException क्लास

UriFormatException तब फेंका जाता है जब URI का स्वरूप वैध नहीं होता है। इस क्लास की उदाहरणें मैन्युअल रूप से कभी न बनाएँ। इसके बजाय UriFormatException क्लास का उपयोग करें। UriFormatException क्लास की उदाहरणों को कभी भी [System::SmartPtr](../smartptr/) में न लपेटें।

```cpp
class Details_UriFormatException : public System::Details_FormatException
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सिद्धांत का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लॉटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लॉटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | कस्टम अपवर्जन डेटा के साथ शब्दकोश लौटाता है। |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | वर्तमान वस्तु द्वारा दर्शाए गए अपवर्जन से संबंधित HRESULT कोड वाली 32-बिट पूर्णांक मान लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | आंतरिक अपवर्जन का प्रतिनिधित्व करने वाली वस्तु का संदर्भ लौटाता है। |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | त्रुटि विवरण वाली स्ट्रिंग लौटाता है। |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | स्टैक ट्रेस वाली स्ट्रिंग लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | आंतरिकतम अपवर्जन को दर्शाने वाले Exception वस्तु की एक प्रतिलिपि लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से सम्बंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानुपाती। कस्टम वस्तुओं का हैशिंग सक्षम करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानुपाती। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानुपाती। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारम्भ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू प्रकार वस्तु की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और नलपॉइंट के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT सेट करता है, एक कोडेड संख्यात्मक मान जो एक विशिष्ट अपवर्जन को सौंपा जाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटरों को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | कमजोर रेफ़रेंस काउंटर को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंटर को घटाता है। इसे सीधे नहीं बुलाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) मेथड को लागू करता है जिसे [ExceptionWrapper](../exceptionwrapper/) क्लास द्वारा बुलाया जाता है। यद्यपि यह क्लास std::exception से विरासत में नहीं ली गई है, डेरिव्ड क्लासें संरक्षित/निजी सदस्य का उपयोग करके अपना लॉजिक लागू कर सकती हैं। इस मेथड के कार्यान्वयन को [ExceptionWrapper](../exceptionwrapper/) में ले जाने से वह लॉजिक टूट सकता है। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## और देखें

* क्लास [Details_FormatException](../details_formatexception/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)