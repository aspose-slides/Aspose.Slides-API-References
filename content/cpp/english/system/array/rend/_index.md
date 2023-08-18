---
title: rend()
second_title: Aspose.Slides for C++ API Reference
description: Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.
type: docs
weight: 482
url: /system/array/rend/
---
## Array::rend() method


Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
reverse_iterator System::Array<T>::rend() noexcept
```


### Return Value

An iterator pointing to the theoretical element preceding the first element of the container.

## Array::rend() const method


Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
const_reverse_iterator System::Array<T>::rend() const noexcept
```


### Return Value

An iterator pointing to the theoretical element preceding the first element of the const-qualified container.

## See Also

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)