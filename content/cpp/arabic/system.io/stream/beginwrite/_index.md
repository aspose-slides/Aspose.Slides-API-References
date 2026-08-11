---
title: BeginWrite()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يبدأ عملية كتابة غير متزامنة.
type: docs
weight: 170
url: /ar/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) طريقة

يبدأ عملية كتابة غير متزامنة.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### المعلمات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن يحتوي على البيانات التي سيتم كتابتها |
| offset | int | إزاحة ذات أساس صفر في **buffer** تشير إلى الموضع الذي يبدأ منه البيانات للكتابة |
| count | int | عدد البايتات للكتابة |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عندما تكتمل العملية |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية كتابة غير متزامنة بشكل فريد |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الكتابة غير المتزامنة التي تم بدءها

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [Stream](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)