---
title: AreSame()
second_title: Aspose.Slides for C++ API 參考文件
description: Are-same 比較 AreSame 斷言的參數。
type: docs
weight: 66
url: /zh-hant/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) 函式

Are-same 比較 AreSame 斷言的參數。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T1 | 左側物件類型。 |
| T2 | 右側物件類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左側運算式。 |
| rhs_expr | const char * | 右側運算式。 |
| lhs | const T1\& | 左側值。 |
| rhs | const T2\& | 右側值。 |

### 返回值

gtest 風格的斷言結果。

## 另見

* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)