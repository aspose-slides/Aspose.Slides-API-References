---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API 参考
description: Is-instance-of-比较 IsInstanceOf 断言的参数。
type: docs
weight: 118
url: /zh/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) 函数

Is-instance-of-比较 IsInstanceOf 断言的参数。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 参数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | 一个 typeInfo 对象，表示用于比较 **obj** 类型的目标类型 |
| obj | const T\& | 一个其类型需与指定类型比较的对象 |

### 返回值

gtest 风格的断言结果。

## 另请参见

* 类 [TypeInfo](../../system/typeinfo/)
* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)