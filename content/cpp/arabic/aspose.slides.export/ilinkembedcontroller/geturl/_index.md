---
title: GetUrl()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: "يرجع عنوان URL إلى كائن خارجي. تُستدعى هذه الطريقة دائمًا إذا أرجع ILinkEmbedController::GetObjectStoringLocation القيمة LinkEmbedDecision::Link وقد تُستدعى إذا أرجع ILinkEmbedController::GetObjectStoringLocation القيمة LinkEmbedDecision::Embed ولكن الإدراج غير ممكن. يمكن استدعاؤها عدة مرات لنفس معرّف الكائن."
type: docs
weight: 14
url: /ar/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) طريقة

Returns an URL to an external object. This method always called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Link](../../linkembeddecision/) and may be called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Embed](../../linkembeddecision/) but embedding is impossible. Can be called multiple time for same object id.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| id | **int32_t** | معرف الكائن. هذا المعرف يُحفظ فريدًا عبر العملية. |
| referrer | **int32_t** | معرف الكائن المرجعي أو 0، إذا كان الكائن مُشار إليه من قِبل المستند الجذر. قد يُستخدم لإنشاء رابط نسبي. |

### قيمة الإرجاع

عنوان URL للكائن الخارجي أو null إذا يجب تجاهل هذا الكائن.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [ILinkEmbedController](../)
* مساحة الأسماء [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)