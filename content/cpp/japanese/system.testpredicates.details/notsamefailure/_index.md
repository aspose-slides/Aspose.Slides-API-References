---
title: NotSameFailure()
second_title: Aspose.Slides for C++ API リファレンス
description: 「not same」アサーション失敗を出力用にフォーマットします。
type: docs
weight: 66
url: /ja/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) 関数

「not same」アサーション失敗を出力用にフォーマットします。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺の値型。 |
| T2 | 右辺の値型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺の式。 |
| rhs_expr | const char * | 右辺の式。 |
| lhs | T1\& | 左辺の値。 |
| rhs | T2\& | 右辺の値。 |

### 戻り値

[Object](../../system/object/) ラップされた失敗テキスト。

## 参照

* 名前空間 [System::TestPredicates::Details](../)
* ライブラリ [Aspose.Slides](../../)