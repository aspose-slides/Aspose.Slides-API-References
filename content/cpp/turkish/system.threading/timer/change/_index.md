---
title: Change()
second_title: Aspose.Slides for C++ API Referansı
description: Zamanlayıcıyı yeniden zamanlar veya iptal eder.
type: docs
weight: 14
url: /tr/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metot


Zamanlayıcıyı yeniden zamanlar veya iptal eder.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) bir sonraki geri çağırma fonksiyonu çağrısından önce, milisaniye cinsinden; negatif değerler zamanlayıcı planlanmış olsa bile iptal eder. |
| period | **int64_t** | [Timeout](../../timeout/) ardışık geri çağırma fonksiyonu çağrıları arasında, milisaniye cinsinden; sıfır veya negatif değerler zamanlayıcının yalnızca bir kez çalıştırılması gerektiği anlamına gelir. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metot


Zamanlayıcıyı yeniden zamanlar veya iptal eder.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) bir sonraki geri çağırma fonksiyonu çağrısından önce; negatif değerler zamanlayıcı planlanmış olsa bile iptal eder. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ardışık geri çağırma fonksiyonu çağrıları arasında; sıfır veya negatif değerler zamanlayıcının yalnızca bir kez çalıştırılması gerektiği anlamına gelir. |

## İlgili Bağlantılar

* Sınıf [Timer](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)