---
title: InternalAdd()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف ملف تعريف الارتباط المحدد إلى المجموعة.
type: docs
weight: 118
url: /ar/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) طريقة

يقوم بإضافة ملف تعريف الارتباط المحدد إلى المجموعة.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### معلمات

| المعامِل | النوع | الوصف |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | ملف تعريف الارتباط الذي سيتم إضافته. |
| isStrict | **bool** | صحيح عندما يجب أن يستبدل ملف تعريف الارتباط المحدد القديم، وإلا خاطئ. |

### قيمة الإرجاع

0 عندما تم استبدال ملف تعريف الارتباط المحدد للقديم، وإلا 1.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Cookie](../../cookie/)
* فئة [CookieCollection](../)
* نطاق [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)