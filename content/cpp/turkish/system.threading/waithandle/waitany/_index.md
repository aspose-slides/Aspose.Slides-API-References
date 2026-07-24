---
title: WaitAny()
second_title: Aspose.Slides for C++ API Referansı
description: Herhangi bir tutamacın tetiklenmesini bekler.
type: docs
weight: 14
url: /tr/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metot


Herhangi bir tutamacın tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenilecek tutamaclar. |
| millisecondsTimeout | int | [Timeout](../../timeout/) bekleme süresi, milisaniye cinsinden; -1 sınırsız bekleme anlamına gelir, 0 kontrol-et-ve-dön anlamına gelir, pozitif değerler zaman aşımıdır. |

### Dönüş Değeri

Herhangi bir tutamacın tetiklenmesi durumunda True, zaman aşımı gerçekleştiğinde false döner.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metot


Herhangi bir tutamacın tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenilecek tutamaclar. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) bekleme süresini milisaniye olarak temsil eder, ya da sınırsız bekleme için -1 milisaniyeyi temsil eden bir [System::TimeSpan](../../../system/timespan/). |

### Dönüş Değeri

Herhangi bir tutamacın tetiklenmesi durumunda True, zaman aşımı gerçekleştiğinde false döner.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metot


Herhangi bir tutamacın tetiklenmesini bekler.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Beklenilecek tutamaclar. |

### Dönüş Değeri

waitHandles içindeki her öğe sinyal aldığında True; aksi takdirde metot hiç döndürmez.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [WaitHandle](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)