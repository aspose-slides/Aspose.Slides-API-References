---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli ve belirtilen TypeInfo nesnelerinin eşit olup olmadığını belirler.
type: docs
weight: 443
url: /tr/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const metot

Geçerli ve belirtilen [TypeInfo](../) nesnelerinin eşit olup olmadığını belirler.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argümanlar

| Parametre | Type | Açıklama |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Karşılaştırılacak [TypeInfo](../) nesnesi |

### Dönüş Değeri

Nesnelerin hash değerleri eşitse true, aksi takdirinde - false

## TypeInfo::operator==(std::nullptr_t) const metot

Geçerli [TypeInfo](../) nesnesinin bir null-nesne olup olmadığını belirler, yani herhangi bir türü temsil etmez.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Dönüş Değeri

Geçerli [TypeInfo](../) nesnesi bir null-nesne ise true, aksi takdirinde - false

## Ayrıca Bakınız

* Sınıf [TypeInfo](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)