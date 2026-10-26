---
title: "System::TestPredicates::Details"
second_title: مرجع API لـ Aspose.Slides للـ C++
description: 
type: docs
weight: 937
url: /ar/system.testpredicates.details/
---
## الدوال

| Function | Description |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | يطبع الكائن إلى سلسلة عن طريق اختيار دالة التسلسل المناسبة. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | يطبع الحاويات على نمط ICollection إلى سلسلة عن طريق طباعة عناصرها (ليس أكثر من 32). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | يطبع nullptr إلى سلسلة. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | يطبع مجموعات [IEnumerable<bool>](../system.collections.generic/ienumerable/) إلى سلسلة عن طريق طباعة عناصرها (ليس أكثر من 32). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | يطبع الفئة الفرعية [System::Object](../system/object/) إلى سلسلة باستخدام طريقة ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | يطبع الفئة الفرعية [System::Object](../system/object/) إلى سلسلة باستخدام طريقة ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | يطبع الكائن إلى سلسلة باستخدام طريقة ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | يطبع الكائن إلى سلسلة باستخدام طريقة PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | يطبع الكائن إلى سلسلة باستخدام طريقة PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | يطبع الزوج إلى سلسلة. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | يطبع الزوج إلى سلسلة. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | يطبع الحاويات على نمط STL إلى سلسلة عن طريق طباعة عناصرها (ليس أكثر من 32). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | يطبع الأنواع الأخرى إلى سلسلة باستخدام الدوال المقدمة من gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | يصيغ فشل التحقق == للإخراج. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | يصيغ فشل التحقق != للإخراج. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | يصيغ فشل التحقق 'same' للإخراج. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | يصيغ فشل التحقق 'not same' للإخراج. |