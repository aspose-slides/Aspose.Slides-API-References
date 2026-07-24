---
title: operator+()
second_title: Aspose.Slides for C++ API Referansı
description: Nullable<T> sınıfının varsayılan olarak oluşturulmuş bir örneğini döndürür.
type: docs
weight: 209
url: /tr/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const metod

Nullable<T> sınıfının varsayılan oluşturulmuş bir örneğini döndürür.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const metod

Nullable ve nullable olmayan değerleri toplar.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sağa operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | eklenecek değer. |

### Dönüş Değeri

Toplama sonucu.

## Nullable::operator+(const Nullable\<T1\>\&) const metod

Nullable değerleri toplar.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Sağa operand tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | eklenecek değer. |

### Dönüş Değeri

Toplama sonucu.

## Ayrıca Bakınız

* Sınıf [Nullable](../)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)