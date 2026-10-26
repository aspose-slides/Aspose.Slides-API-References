---
title: WaitOne()
second_title: Aspose.Slides for C++ API Referansı
description: Semaforu kilitler. Gerekirse sınırsız bekleme yapar.
type: docs
weight: 40
url: /tr/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() yöntemi


Semaforu kilitler. Gerekirse sınırsız bekleme yapar.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Dönüş Değeri

Semafor kilitlenene kadar döndürülmediği için her zaman true döner.

## Semaphore::WaitOne(int) yöntemi


Semaforu kilitler. Gerekirse bekleme yapar.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Milisaniye cinsinden bekleme zaman aşımı. |

### Dönüş Değeri

Semafor kilitlendiyse true, zaman aşımı aşıldıysa false döner.

## Ayrıca Bakınız

* Sınıf [Semaphore](../)
* AdAlanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)