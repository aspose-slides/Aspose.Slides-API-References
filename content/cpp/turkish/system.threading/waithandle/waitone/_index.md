---
title: WaitOne()
second_title: Aspose.Slides for C++ API Referansı
description: Tutamacın sınırsız süre boyunca tetiklenmesini bekler.
type: docs
weight: 27
url: /tr/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metodu


Süre sınırlaması olmadan tutamacın tetiklenmesini bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Dönüş Değeri

Zaman aşımı oluşmadığı için her zaman true döndürür.

## WaitHandle::WaitOne(int) metodu


Tutmaca tetiklenene kadar bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) beklemek için, milisaniye cinsinden; -1 sonsuz bekleme, 0 kontrol edip dönme, pozitif değerler zaman aşımıdır. |

### Dönüş Değeri

Tutmaca tetiklenmişse true, zaman aşımı aşılmışsa false.

## WaitHandle::WaitOne(TimeSpan) metodu


Tutmaca tetiklenene kadar bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) beklenilecek milisaniye sayısını temsil eder, ya da -1 milisaniye beklemeyi sınırsız temsil eden [System::TimeSpan](../../../system/timespan/). |

### Dönüş Değeri

Tutmaca tetiklenmişse true, zaman aşımı aşılmışsa false.

## WaitHandle::WaitOne(int, bool) metodu


Tutmaca tetiklenene kadar bekler.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) beklemek için, milisaniye cinsinden; -1 sonsuz bekleme, 0 kontrol edip dönme, pozitif değerler zaman aşımıdır. |
| exitContext | **bool** | Doğru ise, bekleme tutamacın kilidini beklemeden önce bırakmalıdır. |

### Dönüş Değeri

Tutmaca tetiklenmişse true, zaman aşımı aşılmışsa false.

## İlgili

* Sınıf [WaitHandle](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)