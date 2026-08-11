---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 937
url: /fa/system.testpredicates.details/
---
## توابع

| تابع | توضیح |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | شی را به رشته تبدیل می‌کند با انتخاب تابع serializer مناسب. |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | کانتینرهای سبک ICollection را به رشته تبدیل می‌کند با چاپ عناصر آن‌ها (بیش از 32 عنصر نیست). |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | مقدار nullptr را به رشته تبدیل می‌کند. |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | مجموعه‌های [IEnumerable<bool>](../system.collections.generic/ienumerable/) را به رشته تبدیل می‌کند با چاپ عناصر آن‌ها (بیش از 32 عنصر نیست). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | زیرکلاس [System::Object](../system/object/) را به رشته تبدیل می‌کند با استفاده از متد ToString(). |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | زیرکلاس [System::Object](../system/object/) را به رشته تبدیل می‌کند با استفاده از متد ToString(). |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | شی را به رشته تبدیل می‌کند با استفاده از متد ToString(). |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | شی را به رشته تبدیل می‌کند با استفاده از متد PrintTo. |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | شی را به رشته تبدیل می‌کند با استفاده از متد PrintTo. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | جفت را به رشته تبدیل می‌کند. |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | جفت را به رشته تبدیل می‌کند. |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | کانتینرهای سبک STL را به رشته تبدیل می‌کند با چاپ عناصر آن‌ها (بیش از 32 عنصر نیست). |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | سایر انواع را به رشته تبدیل می‌کند با استفاده از توابع ارائه‌شده توسط gtest. |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | قالب‌بندی شکست ادعای == برای خروجی. |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | قالب‌بندی شکست ادعای != برای خروجی. |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | قالب‌بندی شکست ادعای 'same' برای خروجی. |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | قالب‌بندی شکست ادعای 'not same' برای خروجی. |