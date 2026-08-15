---
title: AreNotSame()
second_title: Aspose.Slides for C++ API 參考文件
description: Are-not-same 比較參數以用於 AreSame 斷言的翻譯。
type: docs
weight: 92
url: /zh-hant/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1&, const T2&) 函式

Are-not-same-compares 參數用於 AreSame 斷言的翻譯。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T1 | LHS 物件類型。 |
| T2 | RHS 物件類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表達式。 |
| rhs_expr | const char * | RHS 表達式。 |
| lhs | const T1& | LHS 值。 |
| rhs | const T2& | RHS 值。 |

### 返回值

gtest 風格的斷言結果。

## 另見

* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)