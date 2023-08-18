---
title: IsStringByteSequence
second_title: Aspose.Slides for C++ API Reference
description: Template magic to check if a type is a sequence of string characters.
type: docs
weight: 1574
url: /system/isstringbytesequence/
---
## IsStringByteSequence struct


Template magic to check if a type is a sequence of string characters.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | checked type. |
| CharT | Character type to check against. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)