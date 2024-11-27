---
title: Compare()
second_title: Aspose.Slides for C++ API Reference
description: Compares two values.
type: docs
weight: 2406
url: /system/compare/
---
## System::Compare(const TA\&, const TB\&) function


Compares two values.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Return Value

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## System::Compare(const TA\&, const TB\&) function


Compares two floating point values.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Return Value

-1 if **a** compares less than **b**; 0 if the values are equal; 1 if **a** compares greater than **b**

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)