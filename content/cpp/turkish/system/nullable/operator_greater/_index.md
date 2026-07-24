---
title: operator>()
second_title: Aspose.Slides for C++ API Referansı
description: Her zaman false döndürür.
type: docs
weight: 157
url: /tr/system/nullable/operator_greater/
---
## Nullable::operator>(std::nullptr_t) const metot


Her zaman false döndürür.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## Nullable::operator>(const T1\&) const metot


[operator>()](./) uygulayarak, mevcut nesnenin temsil ettiği değerin belirtilen değerden büyük olup olmadığını belirler.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak değerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Karşılaştırılacak değere sabit bir referans |

### Dönüş Değeri

Değer, mevcut nesnenin temsil ettiği değer belirtilen değerden büyükse true, aksi takdirde false

## Nullable::operator>(const Nullable\<T1\>\&) const metot


[operator>()](./) uygulayarak, mevcut nesnenin temsil ettiği değerin belirtilen [Nullable](../) nesnesinin temsil ettiği değerden büyük olup olmadığını belirler.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Karşılaştırılacak [Nullable](../) nesnesinin temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Karşılaştırılacak [Nullable](../) nesnesine sabit bir referans |

### Dönüş Değeri

Değer, mevcut nesnenin temsil ettiği değer belirtilen [Nullable](../) nesnesinin temsil ettiği değerden büyükse true, aksi takdirde false

## İlgili

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)