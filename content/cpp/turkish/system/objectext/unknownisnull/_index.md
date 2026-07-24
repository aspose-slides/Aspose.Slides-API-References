---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ API Referansı
description: Bilinmeyen türdeki nesnenin nullptr olup olmadığını kontrol eder. Skaler olmayan türler için aşırı yükleme.
type: docs
weight: 144
url: /tr/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metod

Bilinen olmayan türdeki nesnenin nullptr olup olmadığını kontrol eder. Skaler olmayan türler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) tür. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) kontrol edilecek. |

### Dönüş değeri

Eğer 'obj == nullptr' true ise, false aksi takdirde.

## ObjectExt::UnknownIsNull(T) metod

Bilinen olmayan türdeki nesnenin nullptr olup olmadığını kontrol eder. Skaler türler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) tür. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) kontrol edilecek. |

### Dönüş değeri

Her zaman false döndürür.

## Ayrıca bakınız

* Sınıf [ObjectExt](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)