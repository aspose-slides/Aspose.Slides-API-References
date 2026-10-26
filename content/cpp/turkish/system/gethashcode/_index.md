---
title: GetHashCode()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen skaler değer için bir hash kodu döndürür.
type: docs
weight: 2484
url: /tr/system/gethashcode/
---
## System::GetHashCode(const T\&) fonksiyon

Belirtilen skaler değer için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği değerin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek değer |

### Dönüş Değeri

Belirtilen değer için üretilen hash kodu

## System::GetHashCode(const T\&) fonksiyon

Belirtilen nesne için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneyi işaret eden [SmartPtr](../smartptr/) |

### Dönüş Değeri

Belirtilen nesne için üretilen hash kodu

## System::GetHashCode(const T\&) fonksiyon

Belirtilen nesne (istisna) için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneyi içeren Exception Wrapper |

### Dönüş Değeri

Belirtilen nesne için üretilen hash kodu

## System::GetHashCode(const T\&) fonksiyon

Belirtilen nesne (akıllı işaretçi ya da istisna olmayan) için bir hash kodu döndürür.

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Fonksiyonun hash kodu ürettiği nesnenin tipi |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Hash kodu üretilecek nesneye const referans |

### Dönüş Değeri

Belirtilen nesne için üretilen hash kodu

## System::GetHashCode(const std::thread::id\&) fonksiyon

std::thread::id için özelleştirme; Belirtilen iş parçacığı nesnesi için hash kodunu döndürür.

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## Diğer Bağlantılar

* Yapı [IsSmartPtr](../issmartptr/)
* Yapı [IsExceptionWrapper](../isexceptionwrapper/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)