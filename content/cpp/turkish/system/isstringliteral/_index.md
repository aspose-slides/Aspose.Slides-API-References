---
title: IsStringLiteral
second_title: C++ için Aspose.Slides API Referansı
description: Bir tipin string literal olup olmadığını kontrol eden şablon büyüsü.
type: docs
weight: 1730
url: /tr/system/isstringliteral/
---
## IsStringLiteral struct

Şablon büyüsü, bir tipin string literal olduğunu kontrol eder.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | kontrol edilen tip. |
| CharT | karşılaştırılacak karakter tipi. |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)