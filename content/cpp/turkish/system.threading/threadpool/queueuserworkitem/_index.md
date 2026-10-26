---
title: QueueUserWorkItem()
second_title: Aspose.Slides için C++ API Referansı
description: Callback parametresi olmadan bir iş öğesini kuyruğa ekler.
type: docs
weight: 14
url: /tr/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) yöntemi

Callback parametresi olmadan bir iş öğesini kuyruğa ekler.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | İş olarak kullanılacak callback fonksiyonu. |

### Dönüş Değeri

Her zaman true döner.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) yöntemi

Callback parametresi olmadan bir iş öğesini kuyruğa ekler.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | İş olarak kullanılacak callback fonksiyonu. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | İş fonksiyonu parametresi. |

### Dönüş Değeri

Her zaman true döner.

## İlgili

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ThreadPool](../)
* Sınıf [Object](../../../system/object/)
* Ad Alanı [System::Threading](../../)
* Kitaplık [Aspose.Slides](../../../)