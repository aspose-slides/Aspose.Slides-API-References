---
title: operator<=()
second_title: Aspose.Slides için C++ API Referansı
description: Her zaman false döner.
type: docs
weight: 196
url: /tr/system/nullable/operator_less_equal/
---
## Nullable::operator<=(std::nullptr_t) const metodu


Her zaman false döner.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## Nullable::operator<=(const T1\&) const metodu


Belirtilen değere, mevcut nesnenin temsil ettiği değerin, bu değerlere [operator<=()](./) uygulayarak daha az veya eşit olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
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

True if the value represented by the current object is less or equal to the specified value, otherwise - false

## Nullable::operator<=(const Nullable\<T1\>\&) const metodu


Belirtilen [Nullable](../) nesnesinin temsil ettiği değerle, mevcut nesnenin temsil ettiği değerin, bu değerlere [operator<=()](./) uygulayarak daha az veya eşit olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | [Nullable](../) nesnesine karşılaştırmak için sabit bir referans |

### Dönüş Değeri

True if the value represented by the current object is less or equal to the value represented by the specified [Nullable](../) object, otherwise - false

## Bakınız

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)