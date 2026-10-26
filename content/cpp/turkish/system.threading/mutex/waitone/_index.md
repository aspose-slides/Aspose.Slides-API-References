---
title: WaitOne()
second_title: Aspose.Slides C++ API Referansı
description: Mutex'i kilitler. Gerekirse sınırsız bekleme gerçekleştirir.
type: docs
weight: 53
url: /tr/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metot


Mutex'i kilitler. Gerekirse sınırsız bekleme gerçekleştirir.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Dönüş Değeri

Her zaman true döner çünkü mutex kilitlenene kadar dönmez.

## Mutex::WaitOne(int) metot


Mutex'i kilitler. Gerekirse bekleme yapar.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | Milisaniye cinsinden bekleme zaman aşımı. |

### Dönüş Değeri

Mutex kilitlendiyse true, zaman aşımı aşıldıysa false döner.

## Mutex::WaitOne(TimeSpan) metot


Mutex'i kilitler. Gerekirse bekleme yapar.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Beklenecek milisaniye sayısını temsil eden bir [System::TimeSpan](../../../system/timespan/) veya -1 milisaniye için sınırsız beklemeyi temsil eden bir [System::TimeSpan](../../../system/timespan/). |

### Dönüş Değeri

Mutex kilitlendiyse true, zaman aşımı aşıldıysa false döner.

## Ayrıca Bakınız

* Sınıf [Mutex](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)