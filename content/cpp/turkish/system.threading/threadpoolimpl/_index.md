---
title: ThreadPoolImpl
second_title: Aspose.Slides for C++ API Referansı
description: İş parçacığı havuzu iç verileri. Bu, erişim işlev(i)leri tarafından bellek yönetimi yapılan bir singleton tipidir. Bunu doğrudan örneklememelisiniz.
type: docs
weight: 235
url: /tr/system.threading/threadpoolimpl/
---
## ThreadPoolImpl sınıf


[Thread](../thread/) havuz iç verileri. Bu bir singleton türüdür ve bellek yönetimi erişim işlev(ler)i tarafından yapılır. Bunu doğrudan örneklememelisiniz.

```cpp
class ThreadPoolImpl
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Kullanılabilir iş parçacıklarının sayısını alır. |
| static **bool**\& [GetInitialized](./getinitialized/)() | Başlatma durumunun singleton'ını alır. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Eşzamanlı iş parçacıklarının azami sayısını alır. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | Havuz tarafından oluşturulan iş parçacıklarının minimum sayısını alır. |
| void [JoinAll](./joinall/)() | Tüm sahip olunan iş parçacıklarını birleştirir. Sonsuz bekler. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | İş öğesini kuyruğa ekler. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Havuzun sahip olduğu iş parçacıklarının sayısını ayarlar. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | Havuzun sahip olduğu iş parçacıklarının minimum sayısını ayarlar. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | Yapıcı. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | Yıkıcı. İş parçacıkları henüz sonlandırılmadıysa hepsini birleştirir. |
## Ayrıca Bakınız

* AdAlanı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)