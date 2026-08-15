---
title: SameFailure()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 'same' 斷言失敗格式化為輸出。
type: docs
weight: 53
url: /zh-hant/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) 函式

為輸出格式化 'same' 斷言失敗。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS 值類型。 |
| T2 | RHS 值類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表達式。 |
| rhs_expr | const char * | RHS 表達式。 |
| lhs | T1\& | LHS 值。 |
| rhs | T2\& | RHS 值。 |

### 返回值

[Object](../../system/object/) 包裝失敗文字。

## 另請參閱

* 命名空間 [System::TestPredicates::Details](../)
* 函式庫 [Aspose.Slides](../../)