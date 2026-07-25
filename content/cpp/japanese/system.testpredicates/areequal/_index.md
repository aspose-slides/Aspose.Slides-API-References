---
title: AreEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: AreEqual アサーションの引数を等価比較します。
type: docs
weight: 14
url: /ja/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) 関数

EqualはAreEqualアサーションの引数を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | LHS 値。 |
| rhs | T2\&& | RHS 値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)