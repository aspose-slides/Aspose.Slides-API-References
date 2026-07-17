---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 937
url: /zh/system.testpredicates.details/
---
## 函数

| Function | 描述 |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 通过选择合适的序列化函数将对象打印为字符串。 |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 通过打印其元素（不超过 32 个）将 ICollection 风格的容器打印为字符串。 |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | 将 nullptr 打印为字符串。 |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | 通过打印其元素（不超过 32 个）将 [IEnumerable<bool>](../system.collections.generic/ienumerable/) 集合打印为字符串。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | 使用 ToString() 方法将 [System::Object](../system/object/) 子类打印为字符串。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | 使用 ToString() 方法将 [System::Object](../system/object/) 子类打印为字符串。 |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 ToString() 方法将对象打印为字符串。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 PrintTo 方法将对象打印为字符串。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 使用 PrintTo 方法将对象打印为字符串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | 将 pair 打印为字符串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | 将 pair 打印为字符串。 |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | 通过打印其元素（不超过 32 个）将 STL 风格的容器打印为字符串。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | 使用 gtest 提供的函数将其他类型打印为字符串。 |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | 格式化 == 断言失败用于输出。 |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | 格式化 != 断言失败用于输出。 |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | 格式化 'same' 断言失败用于输出。 |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | 格式化 'not same' 断言失败用于输出。 |