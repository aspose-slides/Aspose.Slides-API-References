---
title: ArrayInitializerCast()
second_title: Aspose.Slides C++ API Referansı
description: Dizi temel değerlerini dönüştürür (C# bunu örtük olarak yapar ancak C++ bunu yapmaz gibi görünmektedir).
type: docs
weight: 209
url: /tr/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metod


Dizi temel değerlerini dönüştürür (C# bunu örtük olarak yapar ancak C++ bunu yapmaz gibi görünmektedir).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| To | Hedef tip. |
| From | Kaynak tipler. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | From ... | Dönüştürülüp hedef diziye itilecek değerler. |

### Dönüş Değeri

[Array](../../array/) aynı sırada tüm argümanların dönüştürülmüş kopyalarını içerir.

## Ayrıca Bakınız

* Sınıf [ObjectExt](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)