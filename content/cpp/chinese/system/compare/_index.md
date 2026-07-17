---
title: Compare()
second_title: Aspose.Slides for C++ API 参考
description: 比较两个值。
type: docs
weight: 2692
url: /zh/system/compare/
---
## System::Compare(const TA\&, const TB\&) 函数

比较两个值。

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TA | 第一个比较对象的类型 |
| TB | 第二个比较对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const TA\& | 第一个比较对象 |
| b | const TB\& | 第二个比较对象 |

### 返回值

- 1 如果 **a** 小于 **b**；0 如果值相等；1 如果 **a** 大于 **b**

## System::Compare(const TA\&, const TB\&) 函数

比较两个浮点值。

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TA | 第一个比较对象的类型 |
| TB | 第二个比较对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const TA\& | 第一个比较对象 |
| b | const TB\& | 第二个比较对象 |

### 返回值

- 1 如果 **a** 小于 **b**；0 如果值相等；1 如果 **a** 大于 **b**

## 另请参阅

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)