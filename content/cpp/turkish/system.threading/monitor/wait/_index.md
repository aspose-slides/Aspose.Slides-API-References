---
title: Wait()
second_title: C++ için Aspose.Slides API Referansı
description: Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Belirtilen zaman aşımı süresi geçerse, iş parçacığı hazır kuyruğuna girer. İsteğe bağlı olarak, beklemeden önce eşzamanlı bağlam için senkronizasyon alanından çıkar ve ardından alanı yeniden edinir. Henüz uygulanmadı.
type: docs
weight: 53
url: /tr/system.threading/monitor/wait/
---
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t, bool) yöntemi

Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Belirtilen zaman aşımı süresi geçerse, iş parçacığı hazır kuyruğuna girer. İsteğe bağlı olarak, beklemeden önce eşzamanlı bağlam için senkronizasyon alanından çıkar ve ardından alanı yeniden edinir. Henüz uygulanmadı.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan, bool) yöntemi

Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Belirtilen zaman aşımı süresi geçerse, iş parçacığı hazır kuyruğuna girer. İsteğe bağlı olarak, beklemeden önce eşzamanlı bağlam için senkronizasyon alanından çıkar ve ardından alanı yeniden edinir. Henüz uygulanmadı.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout, bool exitContext)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, int32_t) yöntemi

Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Belirtilen zaman aşımı süresi geçerse, iş parçacığı hazır kuyruğuna girer. Henüz uygulanmadı.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, int32_t millisecondsTimeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&, TimeSpan) yöntemi

Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Belirtilen zaman aşımı süresi geçerse, iş parçacığı hazır kuyruğuna girer. Henüz uygulanmadı.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj, TimeSpan timeout)
```
## Monitor::Wait(const SharedPtr\<Object\>\&) yöntemi

Bir nesnedeki kilidi serbest bırakır ve geçerli iş parçacığını kilidi yeniden elde edene kadar bloke eder. Henüz uygulanmadı.

```cpp
static bool System::Threading::Monitor::Wait(const SharedPtr<Object> &obj)
```
## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Monitor](../)
* Sınıf [TimeSpan](../../../system/timespan/)
* Ad Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)