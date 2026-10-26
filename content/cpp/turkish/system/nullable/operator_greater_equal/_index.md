---
title: operator>=()
second_title: Aspose.Slides for C++ API Referansı
description: Her zaman false döner.
type: docs
weight: 183
url: /tr/system/nullable/operator_greater_equal/
---
## Nullable::operator>=(std::nullptr_t) const method

Her zaman false döner.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```

### Dönüş Değeri

Her zaman - false

## Nullable::operator>=(const T1\&) const method

Belirtilen nesne tarafından temsil edilen değere, mevcut nesne tarafından temsil edilen değerin, [operator>=()](./) uygulanarak büyük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Geçerli nesnenin temsil ettiği değer ile karşılaştırılacak değerin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Geçerli nesneyi karşılaştırmak için bir nesneye sabit referans |

### Dönüş Değeri

Geçerli nesnenin temsil ettiği değer, belirtilen nesnenin temsil ettiği değere büyük veya eşitse true, aksi takdirde - false

## Nullable::operator>=(const Nullable\<T1\>\&) const method

Belirtilen [Nullable](../) nesnesi tarafından temsil edilen değere, mevcut nesne tarafından temsil edilen değerin, [operator>=()](./) uygulanarak büyük veya eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | [Nullable](../) nesnesi ile karşılaştırmak için kullanılan değerin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | [Nullable](../) nesnesi ile karşılaştırmak için sabit referans |

### Dönüş Değeri

Geçerli nesnenin temsil ettiği değer, belirtilen [Nullable](../) nesnesinin temsil ettiği değere büyük veya eşitse true, aksi takdirde - false

## Diğer Bölümler

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)