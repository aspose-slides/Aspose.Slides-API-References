---
title: Timer()
second_title: Aspose.Slides for C++ API Referansı
description: Yapıcı.
type: docs
weight: 1
url: /tr/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) yapıcı


Yapıcı.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Zamanlayıcı tarafından çağrılacak işlev. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) yapıcı


Yapıcı.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Zamanlayıcı tarafından çağrılacak işlev. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Geri arama işlevi argümanı. |
| dueTime | **int64_t** | [Timeout](../../timeout/) geri arama işlevinin ilk çağrısından önce, milisaniye cinsinden; negatif değerler oluşturulduktan sonra zamanlayıcıyı planlamaz, böylece daha sonra yeniden zamanlanabilir. |
| period | **int64_t** | [Timeout](../../timeout/) ardışık geri arama işlevi çağrıları arasında, milisaniye cinsinden; sıfır ya da negatif değerler zamanlayıcının yalnızca bir kez çalıştırılması gerektiği anlamına gelir. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) yapıcı


Yapıcı.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Zamanlayıcı tarafından çağrılacak işlev. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Geri arama işlevi argümanı. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) geri arama işlevinin ilk çağrısından önce; negatif değerler oluşturulduktan sonra zamanlayıcıyı planlamaz, böylece daha sonra yeniden zamanlanabilir. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) ardışık geri arama işlevi çağrıları arasında; sıfır ya da negatif değerler zamanlayıcının yalnızca bir kez çalıştırılması gerektiği anlamına gelir. |

## İlgili

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Timer](../)
* Sınıf [Object](../../../system/object/)
* Sınıf [TimeSpan](../../../system/timespan/)
* İsim alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)