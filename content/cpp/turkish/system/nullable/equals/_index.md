---
title: Equals()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesne tarafından temsil edilen değerin, belirtilen Nullable nesnesi tarafından temsil edilen değerle eşit olup olmadığını belirler.
type: docs
weight: 131
url: /tr/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const metodu

Geçerli nesne tarafından temsil edilen değerin, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerle eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Karşılaştırılacak [Nullable](../) nesnesine sabit bir referans |

### Dönüş Değeri

Geçerli nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerle eşitse True, aksi takdirde - false

## Diğer Bağlantılar

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)