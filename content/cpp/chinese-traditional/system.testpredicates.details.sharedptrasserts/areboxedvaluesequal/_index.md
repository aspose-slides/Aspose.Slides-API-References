---
title: AreBoxedValuesEqual()
second_title: Aspose.Slides for C++ API 參考文件
description: 比較兩個 Boxed 類型的相等性。
type: docs
weight: 79
url: /zh-hant/system.testpredicates.details.sharedptrasserts/areboxedvaluesequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *, const char *, const SharedPtr\<BoxedValueBase\>\&, const SharedPtr\<BoxedValueBase\>\&) 函式


比較兩個 Boxed 類型的相等性。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<BoxedValueBase> &lhs, const SharedPtr<BoxedValueBase> &rhs)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | LHS value. |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | RHS value. |

### 返回值

gtest-styled assertion result.

## 另見

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [BoxedValueBase](../../system/boxedvaluebase/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)