---
title: AreNotSame()
second_title: Aspose.Slides for C++ API リファレンス
description: Are-not-same は AreSame アサーションの引数を比較します。
type: docs
weight: 92
url: /ja/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) 関数

AreNotSame は AreSame アサーションの引数を比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)