---
title: HexUnescape()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل التمثيل الست عشري المحدد لحرف إلى حرف.
type: docs
weight: 443
url: /ar/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) طريقة

يقوم بتحويل التمثيل الست عشري المحدد لحرف إلى حرف.

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | سلسلة تحتوي على التمثيل الست عشري لحرف |
| index | **int32_t**\& | الموضع في **pattern** حيث يبدأ التمثيل الست عشري لحرف |

### القيمة المرجعة

الحرف الممثّل بالترميز الست عشري في الموضع **index**. إذا لم يكن الحرف في **index** مُشفّرًا ست عشريًا، يتم إرجاع الحرف في **index**. يتم زيادة قيمة **index** للإشارة إلى الحرف التالي بعد الحرف الذي تم إرجاعه.

## انظر أيضًا

* الفئة [String](../../string/)
* الفئة [Uri](../)
* مساحة الاسم [System](../../)
* المكتبة [Aspose.Slides](../../../)