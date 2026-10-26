---
title: operator!=()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut ve belirtilen TypeInfo nesnelerinin eşit olmadığını belirler.
type: docs
weight: 456
url: /tr/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const method

Mevcut ve belirtilen [TypeInfo](../) nesnelerinin eşit olmadığını belirler.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | [TypeInfo](../) nesnesiyle karşılaştırmak için |

### Dönüş Değeri

Nesnelerin hash değerleri eşit değilse true, aksi takdirinde - false

## TypeInfo::operator!=(std::nullptr_t) const method

Mevcut [TypeInfo](../) nesnesinin null nesne olmadığını, yani bir tür temsil ettiğini belirler.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### Dönüş Değeri

[TypeInfo](../) nesnesi null nesne değilse true, aksi takdirinde - false

## Ayrıca Bakınız

* Sınıf [TypeInfo](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)