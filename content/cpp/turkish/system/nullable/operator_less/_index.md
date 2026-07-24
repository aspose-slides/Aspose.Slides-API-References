---
title: operator<()
second_title: Aspose.Slides için C++ API Referansı
description: Her zaman false döner.
type: docs
weight: 170
url: /tr/system/nullable/operator_less/
---
## Nullable::operator<(std::nullptr_t) const method


Her zaman false döner.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## Nullable::operator<(const T1\&) const method


[operator<()](./) bu değerlere uygulanarak, mevcut nesnenin temsil ettiği değerin belirtilen değerden küçük olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Karşılaştırılacak değere sabit referans |

### Dönüş Değeri

Mecbur nesnenin temsil ettiği değer, belirtilen değerden küçükse true, aksi takdirde - false

## Nullable::operator<(const Nullable\<T1\>\&) const method


[operator<()](./) bu değerlere uygulanarak, mevcut nesnenin temsil ettiği değerin belirtilen [Nullable](../) nesnesinin temsil ettiği değerden küçük olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit referans |

### Dönüş Değeri

Mecbur nesnenin temsil ettiği değer, belirtilen [Nullable](../) nesnesinin temsil ettiği değerden küçükse true, aksi takdirde - false

## Ayrıca Bakınız

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)