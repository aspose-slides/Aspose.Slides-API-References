---
title: "System::TestPredicates::Details"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 937
url: /ja/system.testpredicates.details/
---
## 関数

| 関数 | 説明 |
| --- | --- |
| std::enable_if_t<\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | 適切なシリアライザ関数を選択してオブジェクトを文字列に出力します。 |
| std::enable_if_t\<[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\> [PrintToString](./printtostring/)(const T\&) | ICollection スタイルのコンテナの要素（最大 32 個）を出力して文字列に変換します。 |
| std::string [PrintToString](./printtostring/)(std::nullptr_t) | nullptr を文字列に出力します。 |
| std::string [PrintToString](./printtostring/)(const [Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<**bool**\>\&) | [IEnumerable<bool>](../system.collections.generic/ienumerable/) コレクションの要素（最大 32 個）を出力して文字列に変換します。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, long long) | [System::Object](../system/object/) のサブクラスを ToString() メソッドで文字列に出力します。 |
| std::enable_if\<System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const [WeakPtr](../system/weakptr/)\<T\>\&, long long) | [System::Object](../system/object/) のサブクラスを ToString() メソッドで文字列に出力します。 |
| std::enable_if<\![TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&System::Details::HasToString\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | オブジェクトを ToString() メソッドで文字列に出力します。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&\![TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | オブジェクトを PrintTo メソッドで文字列に出力します。 |
| std::enable_if\<[TypeTraits::has_print_to_method](../system.testpredicates.typetraits/has_print_to_method/)\<T\>::value\&&[TypeTraits::IsEnumerable](../system.testpredicates.typetraits/isenumerable/)\<T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | オブジェクトを PrintTo メソッドで文字列に出力します。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const std::pair\<T1, T2\>\&, long long) | ペアを文字列に出力します。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const [Collections::Generic::KeyValuePair](../system.collections.generic/keyvaluepair/)\<T1, T2\>\&, long long) | ペアを文字列に出力します。 |
| std::enable_if\<[TypeTraits::IsCppContainer](../system.testpredicates.typetraits/iscppcontainer/)\<T\>::value\&&\!std::is_base_of\<[Object](../system/object/), T\>::value, std::string\>::type [PrintToStringImpl](./printtostringimpl/)(const T\&, long long) | STL スタイルのコンテナの要素（最大 32 個）を出力して文字列に変換します。 |
| std::string [PrintToStringImpl](./printtostringimpl/)(const T\&, int) | gtest が提供する関数を使用して他の型を文字列に出力します。 |
| testing::AssertionResult [EqFailure](./eqfailure/)(const char *, const char *, T1\&, T2\&) | == アサーション失敗を出力用に書式化します。 |
| testing::AssertionResult [NotEqFailure](./noteqfailure/)(const char *, const char *, T1\&, T2\&) | != アサーション失敗を出力用に書式化します。 |
| testing::AssertionResult [SameFailure](./samefailure/)(const char *, const char *, T1\&, T2\&) | 'same' アサーション失敗を出力用に書式化します。 |
| testing::AssertionResult [NotSameFailure](./notsamefailure/)(const char *, const char *, T1\&, T2\&) | 'not same' アサーション失敗を出力用に書式化します。 |