---
title: Details_TimeZoneNotFoundException
second_title: Aspose.Slides for C++ API संदर्भ
description: "TimeZoneNotFoundException तब फेंका जाता है जब समय क्षेत्र जानकारी नहीं मिलती है। इस क्लास की इंस्टेंस को मैन्युअल रूप से कभी न बनाएँ। इसके बजाय TimeZoneNotFoundException क्लास का उपयोग करें। TimeZoneNotFoundException क्लास की इंस्टेंस को कभी भी System::SmartPtr में न लपेटें।"
type: docs
weight: 729
url: /hi/system/details_timezonenotfoundexception/
---
## Details_TimeZoneNotFoundException क्लास

TimeZoneNotFoundException तब फेंका जाता है जब समय क्षेत्र जानकारी नहीं मिलती है। इस क्लास की इंस्टेंस को मैन्युअल रूप से कभी न बनाएँ। इसके बजाय TimeZoneNotFoundException क्लास का उपयोग करें। TimeZoneNotFoundException क्लास की इंस्टेंस को कभी भी [System::SmartPtr](../smartptr/) में न रखें।

```cpp
class Details_TimeZoneNotFoundException : public System::Details_Exception
```

## मेथड्स

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | C# [Object.Equals](../object/equals/) सेमांटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | कस्टम एक्सेप्शन डेटा के साथ शब्दकोष लौटाता है। |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | एक 32-बिट पूर्णांक मान लौटाता है जो वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए अपवाद से संबंधित HRESULT कोड होता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | आंतरिक अपवाद को दर्शाते हुए वस्तु का संदर्भ लौटाता है। |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | त्रुटि विवरण वाला स्ट्रिंग लौटाता है। |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | स्टैक ट्रेस वाला स्ट्रिंग लौटाता है। |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | सबसे भीतर के अपवाद को दर्शाने वाले Exception वस्तु की प्रति लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | C# [Object.GetHashCode()](../object/gethashcode/) मेथड का समानांतर। कस्टम वस्तुओं की हैशिंग को सक्षम करता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../object/gettype/) कॉल का समानांतर। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | C# lock() कथन की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नई वस्तु को प्रारंभ करता है और उपवर्गों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नई वस्तु को प्रारंभ करता है और उपवर्गों की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशिष्टीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशिष्टीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT सेट करता है, जो एक विशेष अपवाद को सौंपा गया कोडित संख्यात्मक मान है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्गुमेंट को एक वेक पॉइंटर सेट करता है (शेयर किए गए के बजाय)। कंटेनरों में पॉइंटर को वेक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाते हुए लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | C# lock() कथन की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | वेक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | वेक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual const char * [what](../details_exception/what/)() const | [what()](../details_exception/what/) मेथड को लागू करता है जिसे [ExceptionWrapper](../exceptionwrapper/) क्लास द्वारा बुलाया जाता है। यद्यपि यह क्लास std::exception से विरासत में नहीं है, व्युत्पन्न क्लासें संरक्षित/निजी सदस्यों का उपयोग करके अपना लॉजिक लागू कर सकती हैं। इस मेथड के कार्यान्वयन को [ExceptionWrapper](../exceptionwrapper/) में ले जाने से वह लॉजिक टूट सकता है। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [Details_Exception](../details_exception/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)