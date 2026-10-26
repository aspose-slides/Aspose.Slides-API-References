---
title: EqFailure()
second_title: Aspose.Slides for C++ API リファレンス
description: 出力に対する == アサーション失敗をフォーマットします。
type: docs
weight: 27
url: /ja/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) 関数

出力に対する == アサーション失敗をフォーマットします。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺の値の型。 |
| T2 | 右辺の値の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | T1\& | 左辺の値。 |
| rhs | T2\& | 右辺の値。 |

### 戻り値

[Object](../../system/object/) 失敗テキストをラップします。

## 参照

* 名前空間 [System::TestPredicates::Details](../)
* ライブラリ [Aspose.Slides](../../)