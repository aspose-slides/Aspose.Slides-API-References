---
title: WaitAll()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm tutamaçların tetiklenmesini bekler.
type: docs
weight: 1
url: /tr/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metod


Tüm tutamaçların tetiklenmesini bekler.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenecek tutamaçlar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) beklemek için milisaniye cinsinden; -1 sonsuz beklemeyi, 0 kontrol edip dönmeyi, pozitif değerler ise zaman aşımını ifade eder. |

### Dönüş Değeri

Tüm tutamaçlar tetiklendiğinde true, zaman aşımı aşıldığında false.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metod


Tüm tutamaçların tetiklenmesini bekler.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenecek tutamaçlar. |
| timeout | [TimeSpan](../../../system/timespan/) | Beklenmesi gereken milisaniye sayısını temsil eden bir [System::TimeSpan](../../../system/timespan/), ya da -1 milisaniyeyi temsil eden bir [System::TimeSpan](../../../system/timespan/). |

### Dönüş Değeri

Tüm tutamaçlar tetiklendiğinde true, zaman aşımı aşıldığında false.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metod


Tüm tutamaçların tetiklenmesini bekler.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenecek tutamaçlar. |

### Dönüş Değeri

Tüm waitHandles öğeleri bir sinyal aldığında true; aksi takdirde metod asla dönmez.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [WaitHandle](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* AdAlanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)