---
title: QueueUserWorkItem()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف عنصر عمل إلى قائمة الانتظار.
type: docs
weight: 1
url: /ar/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) طريقة

يضيف عنصر عمل إلى قائمة الانتظار.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | دالة الاستدعاء للتنفيذ. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | وسيط دالة الاستدعاء. |

### قيمة الإرجاع

دائمًا ما يعيد true.

## انظر أيضًا

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)