---
title: AsyncCompletedEventArgs()
second_title: مرجع API Aspose.Slides للغة C++
description: المنشئ.
type: docs
weight: 1
url: /ar/system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/
---
## AsyncCompletedEventArgs::AsyncCompletedEventArgs() المنشئ

المنشئ.

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs()
```

## AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) المنشئ

يُهيئ مثيلاً جديداً من الفئة [System.ComponentModel.AsyncCompletedEventArgs](../).

```cpp
System::ComponentModel::AsyncCompletedEventArgs::AsyncCompletedEventArgs(const System::Exception &error, bool canceled, const System::SharedPtr<System::Object> &userState)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| error | const [System::Exception](../../../system/exception/)\& | أي خطأ حدث أثناء العملية غير المتزامنة. |
| canceled | **bool** | قيمة تشير إلى ما إذا كانت العملية غير المتزامنة قد أُلغيت. |
| userState | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | كائن الحالة الاختياري المقدم من المستخدم والذي يُمرّر إلى طريقة [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../backgroundworker/runworkerasync/)([System.Object](../../../system/object/)). |

## انظر أيضًا

* نوع معرف [Exception](../../../system/exception/)
* نوع معرف [SharedPtr](../../../system/sharedptr/)
* فئة [AsyncCompletedEventArgs](../)
* فئة [Object](../../../system/object/)
* نطاق [System::ComponentModel](../../)
* مكتبة [Aspose.Slides](../../../)