---
title: IsStringByteSequence
second_title: Aspose.Slides için C++ API Referansı
description: Bir tipin dize karakterlerinden oluşan bir dizi olup olmadığını kontrol etmek için şablon sihri.
type: docs
weight: 1717
url: /tr/system/isstringbytesequence/
---
## IsStringByteSequence struct

Şablon sihri bir tipin dize karakterlerinden oluşan bir dizi olup olmadığını kontrol etmek için.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | kontrol edilen tip. |
| CharT | karşılaştırılacak karakter tipi. |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)