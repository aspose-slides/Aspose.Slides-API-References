---
title: IsStringByteSequence
second_title: Aspose.Slides C++ API hivatkozás
description: Sablon varázslat annak ellenőrzésére, hogy egy típus a karakterlánc karaktereinek sorozata-e.
type: docs
weight: 1717
url: /hu/system/isstringbytesequence/
---
## IsStringByteSequence struktúra


Sablon varázslat annak ellenőrzésére, hogy egy típus a karakterlánc karaktereinek sorozata-e.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```


### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | ellenőrzött típus. |
| CharT | ellenőrzéshez használt karakter típus. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)