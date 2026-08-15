---
title: "System::TestPredicates"
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 924
url: /zh-hant/system.testpredicates/
---
## 函式

| 函式 | 描述 |
| --- | --- |
| std::enable_if\<std::numeric_limits\<T1\>::has_quiet_NaN\&&std::numeric_limits\<T2\>::has_quiet_NaN, **bool**\>::type [AreFPNaN](./arefpnan/)(T1, T2) | 命名空間 [Details](../system.testpredicates.details/) |
| std::enable_if<\!std::numeric_limits\<T1\>::has_quiet_NaN||\!std::numeric_limits\<T2\>::has_quiet_NaN, **bool**\>::type [AreFPNaN](./arefpnan/)(T1, T2) | 檢查兩個浮點數值是否皆為 NaN。處理不支援非訊號化 NaN 的情況。 |
| testing::AssertionResult [AreEqual](./areequal/)(const char *, const char *, T1\&&, T2\&&) | 為 AreEqual 斷言翻譯進行等值比較參數。 |
| std::enable_if\<[TypeTraits::AreFPandArithmetic](../system.testpredicates.typetraits/arefpandarithmetic/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1, const T2, long long) | 為浮點數與算術類型進行等值比較。 |
| std::enable_if\<[TypeTraits::AnyOfDecimal](../system.testpredicates.typetraits/anyofdecimal/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為其中一個或兩個值為 [Decimal](../system/decimal/) 的情況進行等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 Equals 方法為非指標類型進行等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T\&, const T\&, long long) | 使用提供的 Equals 方法為非指標類型進行等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&std::is_class\<T\>::value\&&\!detail::has_method_equals\<T\>::value\&&detail::has_operator_equal\<T\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 operator == 為非指標類型進行等值比較。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value\&&\![IsStringByteSequence](../system/isstringbytesequence/)\<T, char16_t\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 為可裝箱的與 [SmartPtr](../system/smartptr/) 值進行等值比較。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value\&&\![IsStringByteSequence](../system/isstringbytesequence/)\<T, char16_t\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, T, long long) | 為可裝箱的與 [SmartPtr](../system/smartptr/) 值進行等值比較。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, const char16_t *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 為字串常量與 [SmartPtr](../system/smartptr/) 值使用解箱進行等值比較。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, const char16_t *, long long) | 為字串常量與 [SmartPtr](../system/smartptr/) 值使用解箱進行等值比較。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, T, std::nullptr_t, long long) | 為隨機類型與 nullptr 進行等值比較。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, std::nullptr_t, T, long long) | 為隨機類型與 nullptr 進行等值比較。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value\&&(\!std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT1::Pointee_\>::value||\!std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT2::Pointee_\>::value), testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為指標類型進行等值比較。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value\&&std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT1::Pointee_\>::value\&&std::is_base_of\<[System::IO::Stream](../system.io/stream/), typenameT2::Pointee_\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為指標類型進行等值比較。 |
| std::enable_if<\!std::is_null_pointer\<T1\>::value\&&\![IsNullable](../system/isnullable/)\<T1\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, T1, const [Nullable](../system/nullable/)\<T2\>\&, long long) | 為隨機類型與 [Nullable](../system/nullable/) 值進行等值比較。 |
| std::enable_if<\!std::is_null_pointer\<T2\>::value\&&\![IsNullable](../system/isnullable/)\<T2\>::value, testing::AssertionResult\>::type [AreEqualImpl](./areequalimpl/)(const char *, const char *, const [Nullable](../system/nullable/)\<T1\>\&, T2, long long) | 為 [Nullable](../system/nullable/) 值與隨機類型進行等值比較。 |
| testing::AssertionResult [AreEqualImpl](./areequalimpl/)(const char *, const char *, T1, T2, int) | 使用 gtest 演算法為隨機類型進行等值比較。 |
| testing::AssertionResult [AreNotEqual](./arenotequal/)(const char *, const char *, T1\&&, T2\&&) | 為 AreEqual 斷言翻譯進行不等值比較參數。 |
| std::enable_if\<[TypeTraits::AnyOfDecimal](../system.testpredicates.typetraits/anyofdecimal/)\<T1, T2\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為其中一個或兩個值為 [Decimal](../system/decimal/) 的情況進行不等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 Equals 方法為非指標類型進行不等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&detail::has_method_equals\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T\&, const T\&, long long) | 使用提供的 Equals 方法為非指標類型進行不等值比較。 |
| std::enable_if<\![IsSmartPtr](../system/issmartptr/)\<T\>::value\&&std::is_class\<T\>::value\&&\!detail::has_method_equals\<T\>::value\&&detail::has_operator_equal\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T\&, const T\&, long long) | 使用提供的 operator != 為非指標類型進行不等值比較。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, long long) | 為可裝箱的與 [SmartPtr](../system/smartptr/) 值使用解箱進行不等值比較。 |
| std::enable_if\<[IsBoxable](../system/isboxable/)\<T\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const [System::SharedPtr](../system/sharedptr/)\<[Object](../system/object/)\>\&, T, long long) | 為可裝箱的與 [SmartPtr](../system/smartptr/) 值使用解箱進行不等值比較。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T, std::nullptr_t, long long) | 為隨機類型與 nullptr 進行不等值比較。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, std::nullptr_t, T, long long) | 為隨機類型與 nullptr 進行不等值比較。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為指標類型進行等值比較。 |
| testing::AssertionResult [AreNotEqualImpl](./arenotequalimpl/)(const char *, const char *, T1, T2, int) | 使用 gtest 演算法為隨機類型進行等值比較。 |
| testing::AssertionResult [AreSame](./aresame/)(const char *, const char *, const T1\&, const T2\&) | 為 AreSame 斷言翻譯進行相同比較參數。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為智能指標進行相同比較。 |
| std::enable_if\<[IsExceptionWrapper](../system/isexceptionwrapper/)\<T1\>::value\&&[IsExceptionWrapper](../system/isexceptionwrapper/)\<T2\>::value, testing::AssertionResult\>::type [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為例外情況進行相同比較。 |
| testing::AssertionResult [AreSameImpl](./aresameimpl/)(const char *, const char *, const T1\&, const T2\&, int) | 為非指標值進行相同比較。 |
| testing::AssertionResult [AreNotSame](./arenotsame/)(const char *, const char *, const T1\&, const T2\&) | 為 AreSame 斷言翻譯進行非相同比較參數。 |
| std::enable_if\<[IsSmartPtr](../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../system/issmartptr/)\<T2\>::value, testing::AssertionResult\>::type [AreNotSameImpl](./arenotsameimpl/)(const char *, const char *, const T1\&, const T2\&, long long) | 為智能指標進行非相同比較。 |
| testing::AssertionResult [AreNotSameImpl](./arenotsameimpl/)(const char *, const char *, const T1\&, const T2\&, int) | 為非指標值進行非相同比較。 |
| testing::AssertionResult [IsInstanceOf](./isinstanceof/)(const char *, const char *, const [TypeInfo](../system/typeinfo/)\&, const T\&) | 為 IsInstanceOf 斷言翻譯比較參數。