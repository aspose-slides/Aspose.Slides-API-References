---
title: ObjectType
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑब्जेक्ट प्रकार के गेटर को लागू करने वाली स्थैतिक विधियों को प्रदान करता है। यह कोई इंस्टेंस सेवाएँ नहीं देने वाला स्थैतिक प्रकार है। आपको इसे किसी भी माध्यम से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 1158
url: /hi/system/objecttype/
---
## ObjectType वर्ग

ऑब्जेक्ट प्रकार के गेटर को लागू करने वाले स्थैतिक विधियाँ प्रदान करता है। यह कोई इंस्टेंस सेवाएँ नहीं देने वाला स्थैतिक प्रकार है। आपको इसे किसी भी तरीके से इंस्टेंस नहीं बनाना चाहिए।

```cpp
class ObjectType
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() अनुवाद लागू करता है। स्मार्ट पॉइंटर्स के लिए ओवरलोड। |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() अनुवाद लागू करता है। संरचनाओं के लिए ओवरलोड। |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() अनुवाद लागू करता है। एक्सेप्शन के लिए ओवरलोड। |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() अनुवाद लागू करता है। प्रिमिटिव टाइप्स के लिए ओवरलोड। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() अनुवाद लागू करता है। [Nullable](../nullable/) प्रकार के लिए ओवरलोड। |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। प्रिमिटिव टाइप्स के लिए ओवरलोड। |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। एन्नम टाइप्स के लिए ओवरलोड। |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। [Nullable](../nullable/) के लिए ओवरलोड। |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। MutlicastDelegate के लिए ओवरलोड। |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | typeof() अनुवाद लागू करता है। स्ट्रिंग टाइप के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() अनुवाद लागू करता है। **uint8_t** के लिए ओवरलोड। |

## देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)