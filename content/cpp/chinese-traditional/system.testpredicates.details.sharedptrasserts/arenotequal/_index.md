---
title: AreNotEqual()
second_title: Aspose.Slides C++ API 參考
description: 對 AreNotEqual 斷言的參數執行不相等比較。
type: docs
weight: 131
url: /zh-hant/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) 函式

不相等比較 AreNotEqual 斷言的參數。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## 另見

* 名稱空間 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 程式庫 [Aspose.Slides](../../)