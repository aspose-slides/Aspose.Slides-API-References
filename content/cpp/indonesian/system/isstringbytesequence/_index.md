---
title: IsStringByteSequence
second_title: Referensi API Aspose.Slides untuk C++
description: Sihir templat untuk memeriksa apakah sebuah tipe merupakan urutan karakter string.
type: docs
weight: 1717
url: /id/system/isstringbytesequence/
---
## IsStringByteSequence struct

Sihir templat untuk memeriksa apakah sebuah tipe merupakan urutan karakter string.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | tipe yang diperiksa. |
| CharT | tipe karakter untuk dibandingkan. |

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)