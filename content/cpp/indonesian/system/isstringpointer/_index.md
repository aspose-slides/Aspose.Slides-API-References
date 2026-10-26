---
title: IsStringPointer
second_title: Referensi API Aspose.Slides untuk C++
description: Sihir templat untuk memeriksa apakah suatu tipe adalah pointer ke string karakter.
type: docs
weight: 1743
url: /id/system/isstringpointer/
---
## IsStringPointer struct


Sihir templat untuk memeriksa apakah suatu tipe adalah pointer ke string karakter.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe yang diperiksa. |
| CharT | Tipe karakter untuk diperiksa. |

## Lihat Juga

* Ruang nama [System](../)
* Pustaka [Aspose.Slides](../../)