---
title: operator!=()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut nesne tarafından temsil edilen değerin null olmadığını belirler.
type: docs
weight: 144
url: /tr/system/nullable/operator_not_equal/
---
## Nullable::operator!=(std::nullptr_t) const metot

Mevcut nesne tarafından temsil edilen değerin null olmadığını belirler.

```cpp
bool System::Nullable<T>::operator!=(std::nullptr_t) const
```

### Dönüş Değeri

Mevcut nesne tarafından temsil edilen değer null değilse true, aksi takdirde - false

## Nullable::operator!=(const T1\&) const metot

Mevcut nesne tarafından temsil edilen değerin belirtilen değere eşit olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator!=(const T1 &other) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Karşılaştırılacak değere sabit bir referans |

### Dönüş Değeri

Mevcut nesne tarafından temsil edilen değer belirtilen değere eşit değilse true, aksi takdirde - false

## Nullable::operator!=(const Nullable\<T1\>\&) const metot

Mevcut nesne tarafından temsil edilen değerin, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değere eşit olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator!=(const Nullable<T1> &other) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | [Nullable](../) nesnesinin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | [Nullable](../) nesnesine sabit bir referans |

### Dönüş Değeri

Mevcut nesne tarafından temsil edilen değer, belirtilen [Nullable](../) nesnesi tarafından temsil edilen değere eşit değilse true, aksi takdirde - false

## Ayrıca Bakınız

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)