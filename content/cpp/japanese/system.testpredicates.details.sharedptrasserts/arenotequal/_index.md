---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API リファレンス
description: AreNotEqual アサーションのために引数が等しくないことを比較します。
type: docs
weight: 131
url: /ja/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) 関数


AreNotEqual アサーションのために引数が等しくないことを比較します。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左辺オブジェクトの型。 |
| T2 | 右辺オブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhs_expr | const char * | 左辺式。 |
| rhs_expr | const char * | 右辺式。 |
| lhs | const T1\& | 左辺の値。 |
| rhs | const T2\& | 右辺の値。 |

### 戻り値

gtest 形式のアサーション結果。

## 参照

* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)