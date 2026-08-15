---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API 參考
description: 不等比較 AreEqual 斷言的參數。
type: docs
weight: 40
url: /zh-hant/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) function

不等比較 AreEqual 斷言的參數。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS 物件類型。 |
| T2 | RHS 物件類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表達式。 |
| rhs_expr | const char * | RHS 表達式。 |
| lhs | T1\&& | LHS 值。 |
| rhs | T2\&& | RHS 值。 |

### 返回值

gtest 風格的斷言結果。

## 另請參閱

* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)