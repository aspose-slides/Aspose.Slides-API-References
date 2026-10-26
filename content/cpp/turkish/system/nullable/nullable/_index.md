---
title: Nullable()
second_title: Aspose.Slides for C++ API Referansı
description: Null değeri temsil eden bir örnek oluşturur.
type: docs
weight: 1
url: /tr/system/nullable/nullable/
---
## Nullable::Nullable() yapıcı

Null değeri temsil eden bir örnek oluşturur.

```cpp
System::Nullable<T>::Nullable()
```

## Nullable::Nullable(std::nullptr_t) yapıcı

Null değeri temsil eden bir örnek oluşturur.

```cpp
System::Nullable<T>::Nullable(std::nullptr_t)
```

## Nullable::Nullable(const T1\&) yapıcı

[Nullable](../) sınıfının, belirtilen değeri (gerekirse) temel tip T'nin değerine dönüştürülmüş şekilde temsil eden bir örneğini oluşturur.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const T1 &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Belirtilen değerin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T1\& | Yeni oluşturulan [Nullable](../) nesnesi tarafından temsil edilecek değerin sabit referansı |

## Nullable::Nullable(const Nullable\<T1\>\&) yapıcı

Belirtilen [Nullable](../) nesnesi tarafından temsil edilen bir değeri temsil eden bir örnek oluşturur. Belirtilen nullable nesne, oluşturulan örneğin temel tipinden farklı bir tipte değer temsil edebilir; bu durumda temsil edilen değer, T tipine dönüştürülür.

```cpp
template<typename T1> System::Nullable<T>::Nullable(const Nullable<T1> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | Belirtilen [Nullable](../) nesnesi tarafından temsil edilen değerin tipi |

## Bakınız

* Sınıf [Nullable](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)