---
title: IsStringPointer
second_title: Aspose.Slides for C++ API Reference
description: Template magic to check if a type is a pointer to character string.
type: docs
weight: 1678
url: /system/isstringpointer/
---
## IsStringPointer struct


Template magic to check if a type is a pointer to character string.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | checked type. |
| CharT | Character type to check against. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)