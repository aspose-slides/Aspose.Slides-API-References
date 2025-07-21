---
title: IsStringLiteral
second_title: Aspose.Slides for C++ API Reference
description: Template magic to check if a type is a string literal.
type: docs
weight: 1639
url: /system/isstringliteral/
---
## IsStringLiteral struct


Template magic to check if a type is a string literal.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | checked type. |
| CharT | Character type to check against. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)