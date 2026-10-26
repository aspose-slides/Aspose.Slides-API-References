---
title: AreBoxedValuesEqual()
second_title: Aspose.Slides for C++ API 参考
description: 对两个 Boxed 类型进行相等比较。
type: docs
weight: 79
url: /zh/system.testpredicates.details.sharedptrasserts/areboxedvaluesequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *, const char *, const SharedPtr\<BoxedValueBase\>\&, const SharedPtr\<BoxedValueBase\>\&) 函数

对两个 Boxed 类型进行相等比较。

```cpp
testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreBoxedValuesEqual(const char *lhs_expr, const char *rhs_expr, const SharedPtr<BoxedValueBase> &lhs, const SharedPtr<BoxedValueBase> &rhs)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | 左侧值。 |
| rhs | const [SharedPtr](../../system/sharedptr/)\<[BoxedValueBase](../../system/boxedvaluebase/)\>\& | 右侧值。 |

### 返回值

gtest-styled assertion result.

## 另见

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [BoxedValueBase](../../system/boxedvaluebase/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)