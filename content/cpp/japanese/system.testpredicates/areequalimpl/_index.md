---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 浮動小数点数と算術型を等価比較します。
type: docs
weight: 27
url: /ja/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 関数

浮動小数点数と算術型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS オブジェクトの型。 |
| T2 | RHS オブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1 | LHS 値。 |
| rhs | const T2 | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

[Decimal](../../system/decimal/) のいずれか、または両方の値を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS オブジェクトの型。 |
| T2 | RHS オブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数

提供された Equals メソッドを使用してポインタでない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 関数

提供された Equals メソッドを使用してポインタでない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数

提供された operator == を使用してポインタでない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 関数

[SmartPtr](../../system/smartptr/) 値とボックス可能な型を等価比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T | LHS 値。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 関数

[SmartPtr](../../system/smartptr/) 値とボックス可能な型を等価比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 値。 |
| rhs | T | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 関数

アンボックスを使用して、文字列リテラルと [SmartPtr](../../system/smartptr/) 値を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const char16_t * | LHS 値。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 関数

アンボックスを使用して、文字列リテラルと [SmartPtr](../../system/smartptr/) 値を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 値。 |
| rhs | const char16_t * | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 関数

nullptr とランダム型を等価比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T | LHS 値。 |
| s | std::nullptr_t | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 関数

nullptr とランダム型を等価比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| rhs | std::nullptr_t | RHS 値。 |
| s | T | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

ポインタ型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

ポインタ型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 関数

[Nullable](../../system/nullable/) 値とランダム型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T1 | LHS 値。 |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 関数

ランダム型と [Nullable](../../system/nullable/) 値を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS 値。 |
| rhs | T2 | RHS 値。 |
| s | long long | 関数の実装を選択するためのサービスパラメータです。パラメータの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 関数

gtest アルゴリズムを使用してランダム型を等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T1 | LHS 値。 |
| rhs | T2 | RHS 値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* クラス [Object](../../system/object/)
* クラス [Stream](../../system.io/stream/)
* クラス [Nullable](../../system/nullable/)
* 構造体 [IsSmartPtr](../../system/issmartptr/)
* 構造体 [IsBoxable](../../system/isboxable/)
* 構造体 [IsStringByteSequence](../../system/isstringbytesequence/)
* 構造体 [IsNullable](../../system/isnullable/)
* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)