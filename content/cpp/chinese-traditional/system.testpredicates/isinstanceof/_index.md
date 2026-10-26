---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API 參考
description: Is-instance-of 比較 IsInstanceOf 斷言的參數翻譯。
type: docs
weight: 118
url: /zh-hant/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) 函式

Is-instance-of 比較 IsInstanceOf 斷言的參數。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 參數型別。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表達式。 |
| rhs_expr | const char * | RHS 表達式。 |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | 一個 typeInfo 物件，代表一個類型，用以比較 **obj** 的類型。 |
| obj | const T\& | 一個物件，其類型將與指定的類型比較。 |

### 返回值

gtest 風格的斷言結果。

## 另請參閱

* 類別 [TypeInfo](../../system/typeinfo/)
* 命名空間 [System::TestPredicates](../)
* 函式庫 [Aspose.Slides](../../)