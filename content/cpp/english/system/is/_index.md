---
title: Is()
second_title: Aspose.Slides for C++ API Reference
description: Implements 'is' declaration pattern translation.
type: docs
weight: 2237
url: /system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) function


Implements 'is' declaration pattern translation.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| PatternT | type to check. |
| ExpressionT | left expression type. |
| ResultT | type of result expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| result | ResultT\& | variable which will be assigned to checked type. |

### Return Value

true if type check is successfull, false otherwise.

## System::Is(const ExpressionT\&, const ConstantT\&) function


Implements 'is' constant pattern translation.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ExpressionT | left expression type. |
| ConstantT | type of constant expression. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const ExpressionT\& | expression which will be checked. |
| constant | const ConstantT\& | expression which will be compared with left one. |

### Return Value

true if type check is successfull, false otherwise.

## System::Is(const E\&, const A\&) function


Top-level matching function. Applies a pattern to a value.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| A | Pattern type (must inherit from Details::Pattern). |
| E | Type of the value to match. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| e | const E\& | Value to match against. |
| a | const A\& | Pattern to apply. |

### Return Value

true if the pattern matches the value.

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)