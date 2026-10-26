---
title: CompareTo()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut nesne tarafından temsil edilen ve DateTime sınıfının belirtilen örneği tarafından temsil edilen iki tarih ve saat değerini karşılaştırır ve değerlerin zaman çizelgesi üzerindeki göreceli konumlarını gösteren değeri döndürür.
type: docs
weight: 443
url: /tr/system/datetime/compareto/
---
## DateTime::CompareTo(DateTime) const metodu

Mevcut nesne tarafından temsil edilen ve belirtilen [DateTime](../) sınıfının bir örneği tarafından temsil edilen iki tarih ve saat değerini karşılaştırır ve değerlerin zaman çizelgesi üzerindeki göreceli konumlarını belirten değeri döndürür.

```cpp
constexpr int System::DateTime::CompareTo(DateTime value) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DateTime](../) | Mevcut nesneyle karşılaştırmak için [DateTime](../) sınıfının bir örneği |

### Dönüş Değeri

Mevcut nesne, **value** tarafından temsil edilen değerden daha erken bir değeri temsil ediyorsa 0'dan küçük bir değer; her iki nesne tarafından temsil edilen değerler aynı ise 0; mevcut nesne, **value** tarafından temsil edilen değerden daha sonraki bir değeri temsil ediyorsa 0'dan büyük bir değer.

## İlgili

* Sınıf [DateTime](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)