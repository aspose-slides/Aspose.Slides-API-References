---
title: IsStringPointer
second_title: Aspose.Slides for C++ API Referansı
description: Bir tipin karakter dizisi işaretçisi olup olmadığını kontrol eden şablon sihri.
type: docs
weight: 1743
url: /tr/system/isstringpointer/
---
## IsStringPointer struct

Bir tipin karakter dizisi işaretçisi olup olmadığını kontrol eden şablon sihri.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```

### Template parameters

| Parametre | Açıklama |
| --- | --- |
| T | kontrol edilen tip. |
| CharT | karşılaştırılacak karakter tipi. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)