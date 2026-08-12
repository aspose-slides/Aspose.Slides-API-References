---
title: ElapsedEventArgs
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: टाइमर इवेंट के आर्ग्यूमेंट्स।
type: docs
weight: 1
url: /hi/system.timers/elapsedeventargs/
---
## ElapsedEventArgs क्लास

टाइमर इवेंट के आर्ग्यूमेंट्स।

```cpp
class ElapsedEventArgs : public System::EventArgs
```

## विधियाँ

| Method | Description |
| --- | --- |
|  [ElapsedEventArgs](./elapsedeventargs/)(**int32_t**, **int32_t**) | दिए गए पैरामीटर के साथ आर्ग्यूमेंट ऑब्जेक्ट बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को एंप्लिमेंट करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को एंप्लिमेंट करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
|  [EventArgs](../../system/eventargs/eventargs/)() | कंस्ट्रक्टर। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [DateTime](../../system/datetime/) [get_SignalTime](./get_signaltime/)() | सिंगल टाइम प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करना लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, साथ ही नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत संस्करण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकृत संस्करण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर सेट करता है (साझा के बजाय)। कंटेनरों में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को डिक्रिमेंट करता है और लौटाता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में कन्वर्ट करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करना लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को डिक्रिमेंट करता है। सीधे कॉल न करें; इसके बजाय स्मार्ट पॉइंटर या ThisProtector उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | एक स्थैतिक सदस्य जो एक "empty" [EventArgs](../../system/eventargs/) साझा पॉइंटर (null-pointer) को दर्शाता है। |
## संबंधित देखें

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Timers](../)
* Library [Aspose.Slides](../../)