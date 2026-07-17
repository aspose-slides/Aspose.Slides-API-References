---
title: "System::TestPredicates"
second_title: Aspose.Slides for C++ API 参考
description: 
type: docs
weight: 924
url: /zh/system.testpredicates/
---
## 函数

| Function | Description |
| --- | --- |
| std::enable_if\<std::numeric_limits\<T1\>::has_quiet_NaN\&&std::numeric_limits\<T2\>::has_quiet_NaN, **bool**\>::type [AreFPNaN](./arefpnan/)(T1, T2) | 命名空间 [Details](../system.testpredicates.details/) |
| std::enable_if<\!std::numeric_limits\<T1\>::has_quiet_NaN||\!std::numeric_limits\<T2\>::has_quiet_NaN, **bool**\>::type [AreFPNaN](./arefpnan/)(T1, T2) | 检查两个浮点值是否都是 NaN。处理不支持非信号 NaN 的情况。 |
| testing::AssertionResult [AreEqual](./areequal/)(const char *, const char *, T1\&&, T2\&&) | 对 AreEqual 断言的翻译进行相等比较。 |
| std::enable_if\<[TypeTraits::AreFPandArithmetic](../system.testpredicates.typetraits/arefpandarithmetic/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1, const T2, long long) | 对浮点数与算术类型进行相等比较。 |
| std::enable_if\<[TypeTraits::AnyOfDecimal](../system.testpredicates.typetraits/anyofdecimal/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对其中一个或两个为 [Decimal](../system/decimal/) 的值进行相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 Equals 方法对非指针类型进行相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T\&, const T\&, long long) | 使用提供的 Equals 方法对非指针类型进行相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&std::is_class\<T\>::value\&&\!detail::has_method_equals\<T\>::value\&&detail::has_operator_equal\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 operator == 对非指针类型进行相等比较。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value\&&\![IsStringByteSequence](../system/isstringbytesequence/)\<T, char16_t\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 对可装箱的 [SmartPtr](../system/smartptr/) 值进行相等比较。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value\&&\![IsStringByteSequence](../system/isstringbytesequence/)\<T, char16_t\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, T, long long) | 对可装箱的 [SmartPtr](../system/smartptr/) 值进行相等比较。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, const char16_t *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 使用解箱，将字符串字面量与 [SmartPtr](../system/smartptr/) 值进行相等比较。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, const char16_t *, long long) | 使用解箱，将字符串字面量与 [SmartPtr](../system/smartptr/) 值进行相等比较。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, T, std::nullptr_t, long long) | 对随机类型与 nullptr 进行相等比较。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, std::nullptr_t, T, long long) | 对随机类型与 nullptr 进行相等比较。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value\&&(\!std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT1::Pointee_\>::value||\!std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT2::Pointee_\>::value), testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对指针类型进行相等比较。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value\&&std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT1::Pointee_\>::value\&&std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT2::Pointee_\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对指针类型进行相等比较。 |
| std::enable_if<\!std::is_null_pointer\<T1\>::value\&&\![IsNullable](../system/isnullable/)\<T1\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T1, const [Nullable](../system/nullable/)\<T2\>\&, long long) | 对随机类型与 [Nullable](../system/nullable/) 值进行相等比较。 |
| std::enable_if<\!std::is_null_pointer\<T2\>::value\&&\![IsNullable](../system/isnullable/)\<T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [Nullable](../system/nullable/)\<T1\>\&, T2, long long) | 对 [Nullable](../system/nullable/) 值与随机类型进行相等比较。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, T1, T2, int) | 使用 gtest 算法对随机类型进行相等比较。 |
| testing::AssertionResult [AreNotEqual](./arenotequal/)(const char *, const char *, T1\&&, T2\&&) | 对 AreEqual 断言的翻译进行不相等比较。 |
| std::enable_if\<[TypeTraits::AnyOfDecimal](../system.testpredicates.typetraits/anyofdecimal/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对其中一个或两个为 [Decimal](../system/decimal/) 的值进行不相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 Equals 方法对非指针类型进行不相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T\&, const T\&, long long) | 使用提供的 Equals 方法对非指针类型进行不相等比较。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&std::is_class\<T\>::value\&&\!detail::has_method_equals\<T\>::value\&&detail::has_operator_equal\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 operator != 对非指针类型进行不相等比较。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 使用解箱，对可装箱的 [SmartPtr](../system/smartptr/) 值进行不相等比较。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, T, long long) | 使用解箱，对可装箱的 [SmartPtr](../system/smartptr/) 值进行不相等比较。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T, std::nullptr_t, long long) | 对随机类型与 nullptr 进行不相等比较。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, std::nullptr_t, T, long long) | 对随机类型与 nullptr 进行不相等比较。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对指针类型进行相等比较。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T1, T2, int) | 使用 gtest 算法对随机类型进行相等比较。 |
| testing::AssertionResult [AreSame](./aresame/)(const char *, const char *, const T1\&, const T2\&) | 对 AreSame 断言的翻译进行相同比较。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对智能指针进行相同比较。 |
| std::enable_if\<[IsExceptionWrapper](../system/isexceptionwrapper/)\<T1\>::value\&&[IsExceptionWrapper](../system/isexceptionwrapper/)\<T2\>::value, testing::AssertionResult\>::type [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对异常进行相同比较。 |
| testing::AssertionResult [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, int) | 对非指针值进行相同比较。 |
| testing::AssertionResult [AreNotSame](./arenotsame/)(const char *, const char *, const T1\&, const T2\&) | 对 AreSame 断言的翻译进行非相同比较。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreNotSameImpl](./arenotsameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 对智能指针进行非相同比较。 |
| testing::AssertionResult [AreNotSameImpl](./arenotsameimpl/)(const char *, const char *, const T1\&, const T2\&, int) | 对非指针值进行非相同比较。 |
| testing::AssertionResult [IsInstanceOf](./isinstanceof/)(const char *, const char *, const [TypeInfo](../system/typeinfo/)\&, const T\&) | 对 IsInstanceOf 断言的翻译进行实例比较。 |