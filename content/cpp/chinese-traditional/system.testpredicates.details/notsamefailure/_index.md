---
title: NotSameFailure()
second_title: Aspose.Slides for C++ API 參考文件
description: 為輸出格式化「不相同」斷言失敗。
type: docs
weight: 66
url: /zh-hant/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) 函式


格式化「不相同」斷言失敗以供輸出。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | 左側值類型。 |
| T2 | 右側值類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | 左側表達式。 |
| rhs_expr | const char * | 右側表達式。 |
| lhs | T1\& | 左側值。 |
| rhs | T2\& | 右側值。 |

### 回傳值

[Object](../../system/object/) 包裝失敗文字。

## 另請參閱

* 名稱空間 [System::TestPredicates::Details](../)
* 函式庫 [Aspose.Slides](../../)