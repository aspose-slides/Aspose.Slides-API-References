---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 实现 'is' 声明模式的翻译。
type: docs
weight: 2276
url: /zh/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) function

实现 'is' 声明模式的翻译。

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| PatternT | 要检查的类型。 |
| ExpressionT | 左侧表达式的类型。 |
| ResultT | 结果表达式的类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | 将被检查的表达式。 |
| result | ResultT\& | 将被赋值为检查后类型的变量。 |

### 返回值

如果类型检查成功返回 true，false 否则。

## System::Is(const ExpressionT\&, const ConstantT\&) function

实现 'is' 常量模式的翻译。

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| ExpressionT | 左侧表达式的类型。 |
| ConstantT | 常量表达式的类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | 将被检查的表达式。 |
| constant | const ConstantT\& | 将与左侧表达式比较的表达式。 |

### 返回值

如果类型检查成功返回 true，false 否则。

## System::Is(const E\&, const A\&) function

顶层匹配函数。对值应用模式。

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| A | 模式类型（必须继承自 Details::Pattern）。 |
| E | 要匹配的值的类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| e | const E\& | 要匹配的值。 |
| a | const A\& | 要应用的模式。 |

### 返回值

如果模式匹配该值返回 true。

## 另请参见

* Namespace [System](../)
* Library [Aspose.Slides](../../)