---
title: operator-()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen zaman aralığının, mevcut nesne tarafından temsil edilen değerden çıkarılması sonucunda elde edilen tarih ve saat değerini temsil eden DateTime sınıfının yeni bir örneğini döndürür.
type: docs
weight: 651
url: /tr/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const method

Mevcut nesnenin temsil ettiği değerden belirtilen zaman aralığının çıkarılması sonucunda elde edilen tarih ve saat değerini temsil eden [DateTime](../) sınıfının yeni bir örneğini döndürür.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Çıkarılacak bir zaman aralığı |

### Dönüş Değeri

Mevcut nesnenin temsil ettiği değerden **value** çıkarılması sonucunda elde edilen tarih ve saat değerini temsil eden [DateTime](../) sınıfının yeni bir örneğini döndürür.

## DateTime::operator-(DateTime) const method

[TimeSpan](../../timespan/) sınıfının, mevcut ve belirtilen nesneler tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir örneğini döndürür.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DateTime](../) | Hesaplanacak aralığın bir ucunu belirten [DateTime](../) sınıfının bir örneği |

### Dönüş Değeri

Mevcut nesne ve **value** tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden [TimeSpan](../../timespan/) sınıfının bir örneğini döndürür.

## Ayrıca Bakınız

* Sınıf [DateTime](../)
* Sınıf [TimeSpan](../../timespan/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)