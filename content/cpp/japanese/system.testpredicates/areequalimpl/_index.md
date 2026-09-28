---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ APIリファレンス
description: 浮動小数点と算術型を等価比較します。
type: docs
weight: 27
url: /ja/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 関数

浮動小数点と算術型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1 | LHS value. |
| rhs | const T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

[Decimal](../../system/decimal/) である値のいずれかまたは両方を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数

提供された Equals メソッドを使用して、ポインタではない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 関数

提供された Equals メソッドを使用して、ポインタではない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数

提供された operator == を使用して、ポインタではない型を等価比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 関数

[SmartPtr](../../system/smartptr/) 値とボックス可能な型を等価比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 関数

[SmartPtr](../../system/smartptr/) 値とボックス可能な型を等価比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 関数

アンボックスを使用して、文字列リテラルと [SmartPtr](../../system/smartptr/) 値を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const char16_t * | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 関数

アンボックスを使用して、文字列リテラルと [SmartPtr](../../system/smartptr/) 値を等価比較します。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | const char16_t * | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 関数

ランダム型と nullptr を等価比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 関数

ランダム型と nullptr を等価比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

ポインタ型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数

ポインタ型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 関数

[Nullable](../../system/nullable/) 値とランダム型を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 関数

ランダム型と [Nullable](../../system/nullable/) 値を等価比較します。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS value. |
| rhs | T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 関数

gtest アルゴリズムを使用してランダム型を等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数

2つの [System::String](../../system/string/) 値を等価比較し、null の [String](../../system/string/) 上でメンバー関数が呼び出されることを防止します。テンプレート化されているため（const [String](../../system/string/)& を受け取る単純なオーバーロードではなく）、char16_t の文字列リテラルと [String](../../system/string/) を比較するような混合型呼び出しが単一の一貫した T を推論できず、この候補から完全に除外されます。その結果、long long/int のセレクタパラメーターを介した包括的な AreEqualImpl<T1,T2> テンプレートとの競合や、曖昧なオーバーロード解決が発生しません。

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the function; the value of the parameter is ignored |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)