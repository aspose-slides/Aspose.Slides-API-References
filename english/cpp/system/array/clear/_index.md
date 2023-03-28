---
title: Clear()
second_title: Aspose.Slides for C++ API Reference
description: Not supported because the array represented by the current object is read-only.
type: docs
weight: 53
url: /cpp/system/array/clear/
---
## Array::Clear() method


Not supported because the array represented by the current object is read-only.

```cpp
virtual void System::Array<T>::Clear() override
```


## See Also

* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Array::Clear(const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\&, int, int) method


Replaces **count** values starting at the **startIndex** index in the specified array with default values.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Type | Type of elements in the target array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Target array |
| startIndex | int | Index at which to start replacing the items |
| count | int | The number of items to replace |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
