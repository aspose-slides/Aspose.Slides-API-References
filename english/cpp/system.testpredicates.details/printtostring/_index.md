---
title: PrintToString()
second_title: Aspose.Slides for C++ API Reference
description: Prints object to string by selecting proper serializer function.
type: docs
weight: 1
url: /cpp/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) function


Prints object to string by selecting proper serializer function.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |

### Return Value

[String](../../system/string/) representations of object passed.

## See Also

* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
## System::TestPredicates::Details::PrintToString(const T\&) function


Prints ICollection-style containers to string by printing their elements (not more than 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |

### Return Value

Joint string representations of contained elements.

## See Also

* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
## System::TestPredicates::Details::PrintToString(std::nullptr_t) function


Prints nullptr to string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Return Value

\"nullptr\" string.

## See Also

* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
## System::TestPredicates::Details::PrintToString(const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\&) function


Prints [IEnumerable<bool>](../../system.collections.generic/ienumerable/) collections to string by printing their elements (not more than 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) to print. |

### Return Value

Joint string representations of contained elements.

## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
