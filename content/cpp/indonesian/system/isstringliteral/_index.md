---
title: IsStringLiteral
second_title: Aspose.Slides untuk Referensi API C++
description: Sihir templat untuk memeriksa apakah suatu tipe adalah literal string.
type: docs
weight: 1730
url: /id/system/isstringliteral/
---
## IsStringLiteral struct


Sihir templat untuk memeriksa apakah suatu tipe adalah literal string.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe yang diperiksa. |
| CharT | tipe karakter untuk diperiksa. |

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)