---
title: IsBoxable
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tipin kutulanmasının desteklenip desteklenmediğini kontrol eden şablon önermesi.
type: docs
weight: 1665
url: /tr/system/isboxable/
---
## IsBoxable struct

Belirtilen tipin kutulanması destekleniyorsa kontrol eden şablon önermesi.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Kontrol edilecek tip |

## See Also

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)