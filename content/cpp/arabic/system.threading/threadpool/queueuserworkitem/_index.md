---
title: QueueUserWorkItem()
second_title: مرجع API Aspose.Slides للغة C++
description: يضع عنصر العمل في الطابور الموجود مع callback بدون معاملات.
type: docs
weight: 14
url: /ar/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) طريقة

يضع عنصر العمل في الطابور الموجود مع callback بدون معاملات.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | دالة Callback للاستخدام كوظيفة. |

### القيمة المرجعة

دائمًا يرجع true.

## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) طريقة

يضع عنصر العمل في الطابور الموجود مع callback بدون معاملات.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| callback | [WaitCallback](../../waitcallback/) | دالة Callback للاستخدام كوظيفة. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | معامل دالة الوظيفة. |

### القيمة المرجعة

دائمًا يرجع true.

## انظر أيضًا

* تعريف النوع [WaitCallback](../../waitcallback/)
* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [ThreadPool](../)
* فئة [Object](../../../system/object/)
* مساحة الاسم [System::Threading](../../)
* مكتبة [Aspose.Slides](../../../)