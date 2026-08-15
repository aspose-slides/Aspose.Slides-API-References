---
title: NotEqFailure()
second_title: Aspose.Slides for C++ API 參考文件
description: 格式化 != 斷言失敗的輸出。
type: docs
weight: 40
url: /zh-hant/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) 函式


格式化 != 斷言失敗的輸出。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側值類型。 |
| T2 | 右側值類型。 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | T1\& | 左側值。 |
| rhs | T2\& | 右側值。 |

### 回傳值

[Object](../../system/object/) 包裝失敗文字。

## 另請參閱

* 命名空間 [System::TestPredicates::Details](../)
* 函式庫 [Aspose.Slides](../../)