---
title: QueueUserWorkItem()
second_title: Aspose.Slides for C++ API Referansı
description: İş öğesini kuyruğa ekler.
type: docs
weight: 1
url: /tr/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) yöntemi

İş öğesini kuyruğa ekler.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | Yürütülecek geri arama işlevi. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Geri arama işlevi argümanı. |

### Dönüş Değeri

Her zaman true döner.

## Diğer Bağlantılar

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [ThreadPoolImpl](../)
* Ad alanı [System::Threading](../../)
* Library [Aspose.Slides](../../../)