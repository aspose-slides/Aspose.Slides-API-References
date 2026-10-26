---
title: Subtract()
second_title: Aspose.Slides için C++ API Referansı
description: Geçerli nesnenin temsil ettiği değerden belirtilen zaman aralığının çıkarılması sonucunda tarih ve saat değerini temsil eden DateTime sınıfının yeni bir örneğini döndürür.
type: docs
weight: 326
url: /tr/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metodu


Geçerli nesnenin temsil ettiği değerden belirtilen zaman aralığının çıkarılması sonucunda tarih ve saat değerini temsil eden, yeni bir [DateTime](../) sınıfı örneği döndürür.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Çıkarılacak bir zaman aralığı |

### Dönüş Değeri

Geçerli nesnenin temsil ettiği değerden **duration** çıkarılması sonucunda tarih ve saat değerini temsil eden yeni bir [DateTime](../) sınıfı örneği.

## DateTime::Subtract(DateTime) const metodu


Geçerli nesne ve belirtilen nesneler tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../../timespan/) sınıfı örneği döndürür.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DateTime](../) | Hesaplanacak aralığın bir ucunu işaretleyen bir [DateTime](../) sınıfı örneği |

### Dönüş Değeri

Geçerli nesne ve **value** tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../../timespan/) sınıfı örneği.

## Ayrıca Bakınız

* Sınıf [DateTime](../)
* Sınıf [TimeSpan](../../timespan/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)