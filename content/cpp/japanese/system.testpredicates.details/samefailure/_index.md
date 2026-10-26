---
title: SameFailure()
second_title: Aspose.Slides for C++ API リファレンス
description: 出力用に 'same' アサーション失敗をフォーマットします。
type: docs
weight: 53
url: /ja/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) 関数


出力用に 'same' アサーション失敗をフォーマットします。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | LHS 値の型。 |
| T2 | RHS 値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 式。 |
| rhs_expr | const char * | RHS 式。 |
| lhs | T1\& | LHS 値。 |
| rhs | T2\& | RHS 値。 |

### 戻り値

[Object](../../system/object/) 失敗テキストをラップします。

## 参照

* 名前空間 [System::TestPredicates::Details](../)
* ライブラリ [Aspose.Slides](../../)