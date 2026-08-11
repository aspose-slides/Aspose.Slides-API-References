---
title: BeginRead()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبدأ عملية قراءة غير متزامنة.
type: docs
weight: 157
url: /ar/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) طريقة

يبدأ عملية قراءة غير متزامنة.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مخزن للقراءة |
| offset | int | إزاحة مبنية على الصفر في **buffer** تشير إلى الموضع الذي يبدأ عنده كتابة البيانات المقروءة |
| count | int | عدد البايتات للقراءة |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم للتعرّف الفريد على كل عملية قراءة غير متزامنة |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية القراءة غير المتزامنة التي تم بدأها

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [Object](../../../system/object/)
* فئة [Stream](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)