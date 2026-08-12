---
title: ObjectExt
second_title: Aspose.Slides for C++ API संदर्भ
description: स्थिर विधियों को प्रदान करता है जो C# ऑब्जेक्ट विधियों का अनुकरण करती हैं, जो गैर-ऑब्जेक्ट C++ प्रकारों (स्ट्रिंग, संख्याएँ, आदि) के लिए कॉल की जाती हैं। यह एक स्थिर प्रकार है जिसमें कोई इंस्टेंस सेवाएँ नहीं होतीं। आपको इसे किसी भी तरीके से इंस्टेंस नहीं बनाना चाहिए।
type: docs
weight: 1145
url: /hi/system/objectext/
---
## ObjectExt क्लास

Provides static methods that emulate C# [Object](../object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectExt : public System::ObjectType
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | ऐरे मूलभूत मानों को परिवर्तित करता है (जो C# द्वारा निहित रूप से किया जाता है लेकिन C++ स्पष्ट रूप से नहीं करता)। |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | मान प्रकारों को बॉक्स करता है ताकि [Object](../object/) में परिवर्तित हो सकें। एनीम प्रकारों के लिए कार्यान्वयन। |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | मान प्रकारों को बॉक्स करता है ताकि [Object](../object/) में परिवर्तित हो सकें। गैर-एनीम प्रकारों के लिए कार्यान्वयन। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Nullable](../nullable/) प्रकारों को बॉक्स करता है ताकि [Object](../object/) में परिवर्तित हो सकें। |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | स्ट्रिंग मानों को बॉक्स करता है। |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | एनीम प्रकारों को बॉक्स करता है ताकि उन्हें [Object](../object/) के रूप में प्रसारित किया जा सके। |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | '??' ऑपरेटर अनुवाद का कार्यान्वयन नॉन-नलटेबल प्रकारों के लिए। |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | '??' ऑपरेटर अनुवाद का कार्यान्वयन नलटेबल प्रकारों के लिए। |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | '??=' ऑपरेटर अनुवाद का कार्यान्वयन। |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | '??' ऑपरेटर अनुवाद का कार्यान्वयन नॉन-नलटेबल प्रकारों के लिए। यदि RT2, RT1 में परिवर्तनीय हो तो ओवरलोड। |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) कॉलों के लिए प्रतिस्थापन जो C++ में किसी भी प्रकार के साथ काम करता है। स्मार्ट पॉइंटर प्रकारों के लिए ओवरलोड। |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | C# [Object.Equals](../object/equals/) कॉलों के लिए प्रतिस्थापन जो C++ में किसी भी प्रकार के साथ काम करता है। संरचना प्रकारों के लिए ओवरलोड। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) कॉलों के लिए प्रतिस्थापन जो C++ में किसी भी प्रकार के साथ काम करता है। स्कैलार प्रकारों के लिए ओवरलोड। |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | C# [Object.Equals](../object/equals/) कॉलों के लिए प्रतिस्थापन जो C++ में किसी भी प्रकार के साथ काम करता है। स्ट्रिंग लिटरल के साथ स्ट्रिंग तुलना के लिए ओवरलोड। |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | C# शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN समान माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के साथ भी बराबर नहीं होता। |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | C# शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN समान माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के साथ भी बराबर नहीं होता। |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | [GetHashCode()](./gethashcode/) कॉलों को लागू करता है; [Object](../object/) उपवर्गों और असंबंधित प्रकारों दोनों पर काम करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() अनुवाद को लागू करता है। स्मार्ट पॉइंटर्स के लिए ओवरलोड। |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() अनुवाद को लागू करता है। संरचनाओं के लिए ओवरलोड। |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() अनुवाद को लागू करता है। अपवर्तनों के लिए ओवरलोड। |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() अनुवाद को लागू करता है। प्रिमिटिव प्रकारों के लिए ओवरलोड। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() अनुवाद को लागू करता है। [Nullable](../nullable/) प्रकारों के लिए ओवरलोड। |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। प्रिमिटिव प्रकारों के लिए ओवरलोड। |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। एनीम प्रकारों के लिए ओवरलोड। |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। [Nullable](../nullable/) के लिए ओवरलोड। |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। MutlicastDelegate के लिए ओवरलोड। |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। संरचनाओं और पॉइंटर्स के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | typeof() अनुवाद को लागू करता है। स्ट्रिंग प्रकार के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() अनुवाद को लागू करता है। **uint8_t** के लिए ओवरलोड। |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। बॉक्स करने योग्य (मान) प्रकारों के लिए विशेषीकरण जो वास्तव में वही होते हैं। |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। पॉइंटर प्रकारों के लिए विशेषीकरण जो 'final' क्लासों के लिए अनुकूलित हैं। |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। पॉइंटर प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। मान प्रकारों के लिए विशेषीकरण। |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। अपरिवर्तनीय प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। पॉइंटर प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। अपवाद रैपर प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। नलटेबल प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। == ऑपरेटर परिभाषित वाले बॉक्स करने योग्य प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। == परिभाषित न किए गये बॉक्स करने योग्य प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। इंटरफ़ेस में बॉक्स किए गए मान प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। एनीम प्रकारों के लिए विशेषीकरण। |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। एनीम प्रकारों बनाम कमजोर पॉइंटर्स के लिए विशेषीकरण। |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 'is' ऑपरेटर अनुवाद को लागू करता है। [Nullable](../nullable/) प्रकार के लिए विशेषीकरण। |
| static **bool** [Is](./is/)(const char16_t *) | 'is' ऑपरेटर अनुवाद को लागू करता है। स्ट्रिंग लिटरल के लिए विशेषीकरण। |
| static **bool** [Is](./is/)(**int32_t**) | 'is' ऑपरेटर अनुवाद को लागू करता है। इंटीजर लिटरल के लिए विशेषीकरण। |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | जाँचता है कि ऑब्जेक्ट बॉक्स किया गया मान है या नहीं। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) को अज्ञात प्रकार में परिवर्तित करता है, स्मार्ट पॉइंटर्स और बॉक्स्ड वैल्यू स्थितियों दोनों को संभालते हुए। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/) को अज्ञात प्रकार में परिवर्तित करता है, स्मार्ट पॉइंटर्स और बॉक्स्ड वैल्यू स्थितियों दोनों को संभालते हुए। |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString मेथड के लिए प्रतिस्थापन जो किसी भी C++ प्रकार पर कार्य करता है। |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) में परिवर्तित करने के बाद मान प्रकारों को अनबॉक्स करता है। एनीम प्रकारों के लिए कार्यान्वयन। |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) में परिवर्तित करने के बाद मान प्रकारों को अनबॉक्स करता है। गैर-एनीम और गैर-नलटेबल प्रकारों के लिए कार्यान्वयन। |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/) में परिवर्तित करने के बाद मान प्रकारों को अनबॉक्स करता है। गैर-एनीम और गैर-नलटेबल प्रकारों के लिए कार्यान्वयन। |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | एनीम प्रकारों को पूर्णांक में अनबॉक्स करता है। |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | एनीम प्रकारों को परिवर्तित करता है। |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | स्ट्रिंग मानों को अनबॉक्स करता है। |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | बॉक्स्ड वैल्यू से स्ट्रिंग को अनबॉक्स करता है। |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | ऑब्जेक्ट को नलटेबल प्रकार में अनबॉक्स करता है। |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | जाँचता है कि अज्ञात प्रकार का ऑब्जेक्ट nullptr है या नहीं। गैर-स्कैलर प्रकारों के लिए ओवरलोड। |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | जाँचता है कि अज्ञात प्रकार का ऑब्जेक्ट nullptr है या नहीं। स्कैलर प्रकारों के लिए ओवरलोड। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | अज्ञात प्रकार को [Object](../object/) में परिवर्तित करता है, स्मार्ट पॉइंटर और वैल्यू प्रकार दोनों स्थितियों को संभालते हुए। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | अज्ञात प्रकार को [Object](../object/) में परिवर्तित करता है, स्मार्ट पॉइंटर और वैल्यू प्रकार दोनों स्थितियों को संभालते हुए। |
## देखें

* क्लास [ObjectType](../objecttype/)
* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)