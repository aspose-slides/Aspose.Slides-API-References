---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API Reference
description: namespace Details
type: docs
weight: 1
url: /cpp/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) function


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Return Value

True if both **lhs** and **rhs** are floating point values, false otherwise.
## Remarks


Checks that two floating point values are both NaNs. Handles situation when non-signalling NaN is supported. 
## See Also

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
## System::TestPredicates::AreFPNaN(T1, T2) function


Checks that two floating point values are both NaNs. Handles situation when non-signalling NaN is not supported.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Return Value

Always returns false as NaN value is not supported.

## See Also

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
