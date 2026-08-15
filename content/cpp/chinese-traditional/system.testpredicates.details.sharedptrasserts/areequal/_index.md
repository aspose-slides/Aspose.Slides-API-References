---
title: AreEqual()
second_title: Aspose.Slides for C++ API 參考
description: 對 AreEqual 斷言的參數進行等值比較。
type: docs
weight: 92
url: /zh-hant/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) 函式


Equal-compares 參數以用於 AreEqual 斷言的比較。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### 回傳值

gtest 風格的斷言結果。

## 另請參閱

* 命名空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 函式庫 [Aspose.Slides](../../)