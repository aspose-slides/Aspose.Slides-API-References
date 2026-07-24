---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut nesne tarafından temsil edilen değerin null olup olmadığını belirler.
type: docs
weight: 118
url: /tr/system/nullable/operator_equal_equal/
---
## Nullable::operator==(std::nullptr_t) const metot

Mevcut nesne tarafından temsil edilen değerin null olup olmadığını belirler.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```

### Dönüş Değeri

True if the value represented by the current object is null, otherwise - false

## Nullable::operator==(const T1&) const metot

Mevcut nesne tarafından temsil edilen değerin belirtilen değerle eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T1 | Karşılaştırılacak değerin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1& | Karşılaştırılacak değere sabit referans |

### Dönüş Değeri

True if the value represented by the current object is equal to the specified value, otherwise - false

## Nullable::operator==(const Nullable<T1>&) const metot

Mevcut nesne tarafından temsil edilen değerin belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerle eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)<T1>& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### Dönüş Değeri

True if the value represented by the current object is equal to the value represented by the specified [Nullable](../) object, otherwise - false

## Ayrıca bakınız

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)