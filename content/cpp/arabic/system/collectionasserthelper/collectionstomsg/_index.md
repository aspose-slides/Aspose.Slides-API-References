---
title: CollectionsToMsg()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: يقوم بتسلسل مجموعتين لتمثيلهما في الرسالة.
type: docs
weight: 53
url: /ar/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) طريقة

يقوم بتسلسل مجموعتين لتمثيلهما في الرسالة.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T1 | نوع عنصر المجموعة المتوقعة. |
| T2 | نوع عنصر المجموعة الفعلية. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | سلسلة مخصصة يتم إدراجها قبل القيمة المتوقعة في الرسالة الناتجة |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | المجموعة المتوقعة. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | المجموعة الفعلية. |

### قيمة الإرجاع

رسالة سهلة الفهم حول محتويات المجموعات.

## انظر أيضا

* Typedef [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* مساحة الاسم [System](../../)
* Library [Aspose.Slides](../../../)