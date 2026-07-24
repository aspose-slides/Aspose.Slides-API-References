---
title: operator-()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut nesnenin temsil ettiği değerden belirtilen zaman aralığının çıkarılması sonucu elde edilen tarih ve saat değerini temsil eden DateTimeOffset sınıfının yeni bir örneğini döndürür.
type: docs
weight: 521
url: /tr/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const method


Yeni bir [DateTimeOffset](../) sınıfının örneğini döndürür; bu örnek, mevcut nesnenin temsil ettiği değerden belirtilen zaman aralığının çıkarılması sonucu elde edilen tarih ve saat değerini temsil eder.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Çıkarılacak bir zaman aralığı |

### Dönüş Değeri

Yeni bir [DateTimeOffset](../) sınıfının örneği; bu örnek, mevcut nesnenin temsil ettiği değerden **value** çıkarılması sonrasında elde edilen tarih ve saat değerini temsil eder.

## DateTimeOffset::operator-(const DateTimeOffset\&) const method


Geçerli ve belirtilen nesneler tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../../timespan/) sınıfının örneğini döndürür.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Hesaplanacak aralığın bir ucunu işaret eden [DateTime](../../datetime/) sınıfının bir örneği |

### Dönüş Değeri

Geçerli nesne ve **other** tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../../timespan/) sınıfının örneği.

## Ayrıca Bakınız

* Sınıf [DateTimeOffset](../)
* Sınıf [TimeSpan](../../timespan/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)