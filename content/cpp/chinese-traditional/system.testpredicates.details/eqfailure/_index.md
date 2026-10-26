---
title: EqFailure()
second_title: Aspose.Slides C++ API 參考
description: 將 == 斷言失敗格式化為輸出。
type: docs
weight: 27
url: /zh-hant/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) 函式

將 == 斷言失敗格式化為輸出。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側值類型。 |
| T2 | 右側值類型。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1\& | 左側值。 |
| rhs | T2\& | 右側值。 |

### 返回值

[Object](../../system/object/) 包裹的失敗文字。

## 另見

* 命名空間 [System::TestPredicates::Details](../)
* 函式庫 [Aspose.Slides](../../)