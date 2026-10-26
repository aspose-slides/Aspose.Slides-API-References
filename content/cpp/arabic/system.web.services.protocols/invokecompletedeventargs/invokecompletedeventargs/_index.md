---
title: InvokeCompletedEventArgs()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يقوم بإنشاء مثيل جديد.
type: docs
weight: 14
url: /ar/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) منشئ

يقوم بإنشاء مثيل جديد.

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### Arguments

| معامل | نوع | وصف |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | أي خطأ حدث أثناء عملية غير متزامنة. |
| cancelled | **bool** | قيمة تشير إلى ما إذا تم إلغاء العملية غير المتزامنة. |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | كائن الحالة الاختياري المقدم من المستخدم الذي يُمرّر إلى طريقة [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | مجموعة من نتائج العملية غير المتزامنة. |

## انظر أيضًا

* تعريف نوع [Exception](../../../system/exception/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Object](../../../system/object/)
* فئة [InvokeCompletedEventArgs](../)
* مساحة اسم [System::Web::Services::Protocols](../../)
* مكتبة [Aspose.Slides](../../../)