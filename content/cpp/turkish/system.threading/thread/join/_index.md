---
title: Join()
second_title: Aspose.Slides C++ için API Referansı
description: Yönetilen iş parçacığını birleştirir. Gerekirse sınırsız bekleme gerçekleştirir.
type: docs
weight: 196
url: /tr/system.threading/thread/join/
---
## Thread::Join() yöntemi

Yönetilen iş parçacığını birleştirir. Gerektiğinde sınırsız bekleme gerçekleştirir.

```cpp
void System::Threading::Thread::Join()
```
## Thread::Join(int) yöntemi

Yönetilen iş parçacığını birleştirir. Sınırlı bekleme gerçekleştirir.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsTimeout | int | Milisaniye cinsinden bekleme zaman aşımı. |

### Dönüş Değeri

True if thread başarılı bir şekilde birleştirildiyse, false if timeout aşımı gerçekleşti.

## Thread::Join(TimeSpan) yöntemi

Yönetilen iş parçacığını birleştirir. Sınırlı bekleme gerçekleştirir.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [TimeSpan](../../../system/timespan/) set to the amount of time to wait for the thread to terminate. |

### Dönüş Değeri

True if thread başarılı bir şekilde birleştirildiyse, false if timeout aşımı gerçekleşti.

## İlgili

* Sınıf [Thread](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)