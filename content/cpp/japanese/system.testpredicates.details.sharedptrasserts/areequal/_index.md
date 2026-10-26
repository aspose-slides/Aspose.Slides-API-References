---
title: AreEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: AreEqual アサーションの変換のために引数を等価比較します。
type: docs
weight: 92
url: /ja/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1&, const T2&) 関数

AreEqual アサーションの翻訳のために引数を等価比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T1 | LHS オブジェクト型。 |
| T2 | RHS オブジェクト型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | const T1& | LHS 値。 |
| rhs | const T2& | RHS 値。 |

### 戻り値

gtest 形式のアサーション結果。

## 関連項目

* 名前空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* ライブラリ [Aspose.Slides](../../)