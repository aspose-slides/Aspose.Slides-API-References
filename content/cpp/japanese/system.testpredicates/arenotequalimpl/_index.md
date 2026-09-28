---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: Not-equal は、Decimal である値のうち 1 つまたは両方を比較します。
type: docs
weight: 53
url: /ja/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数


Not-equal は、[Decimal](../../system/decimal/) である値のうち 1 つまたは両方を比較します。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS オブジェクト型。 |
| T2 | RHS オブジェクト型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数


Not-equal は、2 つの [System::String](../../system/string/) 値を比較し、null の [String](../../system/string/) に対してメンバー関数を呼び出すことを防止します。AreEqualImpl [String](../../system/string/) の上記オーバーロードと同じ推論ベースの除外理由のためにテンプレート化されています。

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型、[System::String](../../system/string/) に制限されます。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数


Not-equal は、提供された Equals メソッドを使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) 関数


Not-equal は、提供された Equals メソッドを使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 関数


Not-equal は、提供された operator != を使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T\& | LHS 値。 |
| rhs | const T\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 関数


Not-equal は、[SmartPtr](../../system/smartptr/) 値とボックス可能な型をアンボックスして比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T | LHS 値。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 関数


Not-equal は、[SmartPtr](../../system/smartptr/) 値とボックス可能な型をアンボックスして比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS 値。 |
| rhs | T | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 関数


Not-equal は、任意の型と nullptr を比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T | LHS 値。 |
| s | std::nullptr_t | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 関数


Not-equal は、任意の型と nullptr を比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| rhs | std::nullptr_t | RHS 値。 |
| s | T | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数


Equal は、ポインタ型を比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |
| s | long long | サービス パラメーターは、関数の実装を選択するセレクタとして機能します。パラメーターの値は無視されます。 |

### 戻り値

gtest-styled assertion result.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) 関数


Equal は、gtest アルゴリズムを使用して任意の型を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | LHS 型。 |
| T2 | RHS 型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T1 | LHS 値。 |
| rhs | T2 | RHS 値。 |

### 戻り値

gtest-styled assertion result.

## 関連項目

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)