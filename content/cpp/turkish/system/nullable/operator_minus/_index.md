---
title: operator-()
second_title: Aspose.Slides for C++ API Referansı
description: Nullable ve null işaretli değerleri çıkarır.
type: docs
weight: 222
url: /tr/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metod

Nullable ve null işaretli değerleri çıkarır.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sağ operand tipi, nullptr_t olmalıdır. |

### Dönüş Değeri

Boş [Nullable](../) nesnesi.

## Nullable::operator-(const T1\&) const metod

Nullable ve null olmayan değerleri çıkarır.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sağ operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | çıkarma değeri. |

### Dönüş Değeri

Çıkarma sonucu.

## Nullable::operator-(const Nullable\<T1\>\&) const metod

Nullable değerleri çıkarır.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sağ operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | çıkarma değeri. |

### Dönüş Değeri

Çıkarma sonucu.

## İlgili

* Sınıf [Nullable](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)