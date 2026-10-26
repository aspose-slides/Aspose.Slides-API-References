---
title: DtdProcessing
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الخيارات لمعالجة DTDs. تُستخدم تعداد DtdProcessing بواسطة فئة XmlReaderSettings.
type: docs
weight: 638
url: /ar/system.xml/dtdprocessing/
---
## DtdProcessing تعداد

يحدد الخيارات لمعالجة DTDs. تُستخدم تعداد DtdProcessing بواسطة الفئة [XmlReaderSettings](../xmlreadersettings/).

```cpp
enum class DtdProcessing
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Prohibit | 0 | يحدد أنه عندما يتم مواجهة DTD، يتم طرح XmlException مع رسالة تشير إلى أن ملفات DTD محظورة. هذا هو السلوك الافتراضي. |
| Ignore | 1 | يتسبب في تجاهل عنصر DOCTYPE. لا يحدث أي معالجة لـ DTD، ويتم فقدان DTD/DOCTYPE في المخرجات. |
| Parse | 2 | يُستخدم لتحليل DTDs. |

## انظر أيضًا

* المجال [System::Xml](../)
* المكتبة [Aspose.Slides](../../)