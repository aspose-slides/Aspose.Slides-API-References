---
title: AreEqualContainer()
second_title: Aspose.Slides for C++ API Reference
description: Equal-compares two containers using operator == on elements. Works for non-SmartPtr elements.
type: docs
weight: 1
url: /cpp/system.testpredicates.details.sharedptrasserts/areequalcontainer/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function


Equal-compares two containers using operator == on elements. Works for non-SmartPtr elements.

```cpp
template<typename T1,typename T2> std::enable_if<!System::IsSmartPtr<typenameT1::value_type>::value &&!System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS container type. |
| T2 | RHS container type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS container. |
| rhs | const T2\& | RHS container. |

### Return Value

True if contained elements and sizes match, false otherwise.

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)
## System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1\&, const T2\&) function


Equal-compares two containers using [System::Object::Equals](../../system/object/equals/) on elements. Works for [SmartPtr](../../system/smartptr/) elements.

```cpp
template<typename T1,typename T2> std::enable_if<System::IsSmartPtr<typenameT1::value_type>::value &&System::IsSmartPtr<typenameT2::value_type>::value, bool>::type System::TestPredicates::Details::SharedPtrAsserts::AreEqualContainer(const T1 &lhs, const T2 &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS container type. |
| T2 | RHS container type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs | const T1\& | LHS container reference. |
| rhs | const T2\& | RHS container reference. |

### Return Value

True if contained elements and sizes match, false otherwise.

## See Also

* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)
