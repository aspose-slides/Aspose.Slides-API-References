---
title: AreNotSameImpl()
second_title: Aspose.Slides の C++ API リファレンス
description: Are-not-sameはスマートポインタを比較します。
type: docs
weight: 105
url: /ja/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) 関数


Are-not-sameはスマートポインタを比較します。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### テンプレートパラメーター

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
| s | long long | 関数実装のセレクタとして機能するサービスパラメーターです。パラメーターの値は無視されます。 |

### 戻り値

gtest 形式のアサーション結果。

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) 関数


Are-not-sameは非ポインタ値を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### テンプレートパラメーター

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

### 戻り値

gtest 形式のアサーション結果。

## 関連項目

* 構造体 [IsSmartPtr](../../system/issmartptr/)
* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)