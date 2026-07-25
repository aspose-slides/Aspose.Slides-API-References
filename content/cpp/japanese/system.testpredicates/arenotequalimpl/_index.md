---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 等価でない比較は、値のいずれかまたは両方が Decimal である場合に行われます。
type: docs
weight: 53
url: /ja/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


等価でない比較は、いずれかまたは両方の値が [Decimal](../../system/decimal/) である場合に行われます。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T1 | 左辺オブジェクトの型。 |
| T2 | 右辺オブジェクトの型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function


等価でない比較は、提供された Equals メソッドを使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T\& | 左辺の値。 |
| rhs | const T\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function


等価でない比較は、提供された Equals メソッドを使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | T\& | 左辺の値。 |
| rhs | const T\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function


等価でない比較は、operator != を使用してポインタ以外の型を比較します。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T\& | 左辺の値。 |
| rhs | const T\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function


等価でない比較は、[SmartPtr](../../system/smartptr/) の値を持つボックス化可能な型をアンボックスして比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | T | 左辺の値。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function


等価でない比較は、[SmartPtr](../../system/smartptr/) の値を持つボックス化可能な型をアンボックスして比較します。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左辺の値。 |
| rhs | T | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function


等価でない比較は、nullptr を持つランダム型を比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | T | 左辺の値。 |
| s | std::nullptr_t | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function


等価でない比較は、nullptr を持つランダム型を比較します。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) 型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| rhs | std::nullptr_t | 右辺の値。 |
| s | T | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function


等価比較は、ポインタ型を比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T1 | 左辺の型。 |
| T2 | 右辺の型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |
| s | long long | サービス パラメータは、関数の実装を選択するためのセレクタとして機能します；パラメータの値は無視されます |

### 戻り値

gtest スタイルのアサーション結果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function


等価比較は、gtest アルゴリズムを使用してランダム型を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T1 | 左辺の型。 |
| T2 | 右辺の型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | T1 | 左辺の値。 |
| rhs | T2 | 右辺の値。 |

### 戻り値

gtest スタイルのアサーション結果。

## 参照

* 型定義 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 型定義 [SharedPtr](../../system/sharedptr/)
* クラス [Object](../../system/object/)
* 構造体 [IsSmartPtr](../../system/issmartptr/)
* 構造体 [IsBoxable](../../system/isboxable/)
* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)