---
title: HasOperatorEqualsHelper()
second_title: Aspose.Slides for C++ API Reference
description: Helper function to determine whether specific class has operator ==.
type: docs
weight: 235
url: /system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) function


Helper function to determine whether specific class has operator ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to check. |
| Dummy | Dummy argument for SFINAE magic. |

### Return Value

Value of std::true_type if operator == is present and false otherwise.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) function


Helper function to determine whether specific class has operator ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```


### Return Value

Value of std::true_type if operator == is present and false otherwise.

## See Also

* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)