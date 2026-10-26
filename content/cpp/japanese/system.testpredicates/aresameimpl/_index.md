---
title: AreSameImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: スマートポインタを比較します。
type: docs
weight: 79
url: /ja/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

スマートポインタを比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS オブジェクト型。 |
| T2 | RHS オブジェクト型。 |

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

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

例外を比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS オブジェクト型。 |
| T2 | RHS オブジェクト型。 |

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

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

ポインタでない値を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS オブジェクト型。 |
| T2 | RHS オブジェクト型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1\& | LHS 値。 |
| rhs | const T2\& | RHS 値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* 構造体 [IsSmartPtr](../../system/issmartptr/)
* 構造体 [IsExceptionWrapper](../../system/isexceptionwrapper/)
* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)