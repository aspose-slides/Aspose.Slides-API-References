---
title: GetName()
second_title: Aspose.Slides for C++ API Reference
description: Returns the name of the enumeration constant that has the specified value.
type: docs
weight: 40
url: /cpp/system/enum/getname/
---
## Enum::GetName(T) method


Returns the name of the enumeration constant that has the specified value.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value of enum constant whose name is to be returned |

### Return Value

The name of the specified enum constant

## See Also

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
