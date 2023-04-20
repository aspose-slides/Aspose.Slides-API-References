---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ API Reference
description: Checks whether unknown type object is nullptr. Overload for non-scalar types.
type: docs
weight: 144
url: /cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Checks whether unknown type object is nullptr. Overload for non-scalar types.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Return Value

True if 'obj == nullptr' is true, false otherwise.

## ObjectExt::UnknownIsNull(T) method


Checks whether unknown type object is nullptr. Overload for scalar types.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Return Value

Always returns false.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)