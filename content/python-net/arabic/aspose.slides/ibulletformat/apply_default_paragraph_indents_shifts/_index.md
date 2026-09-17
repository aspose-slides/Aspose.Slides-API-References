---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
يضبط التحولات غير الصفرية الافتراضية للـ Indent و MarginLeft الفعّالين عندما يتم تمكين القوائم النقطية (كما يفعل PowerPoint إذا تم تمكين القوائم النقطية/التعداد في الفقرة). إذا تم تعطيل القوائم النقطية فإنها تعيد تعيين Indent و MarginLeft للفقرة (كما يفعل PowerPoint إذا تم تعطيل القوائم النقطية/التعداد في الفقرة). تُطبق تحولات المسافات بالنسبة لسياق الرصاصة الحالي - IBulletFormat.Type و .NumberedBulletStyle و FontHeight للجزء الأول. تُطبق التحولات غير الصفرية على Indent و MarginLeft الفعّالين للفقرة الحالية (لتصبح القيم الناتجة قيمًا محلية).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | استدعاء هذه الطريقة لا يهم ويُطلق **System.InvalidOperationException** في الحالات التالية:<br/>            إذا كان الكائن المُنسَّق الأب ليس فقرة (على سبيل المثال استدعاء ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() سيسبب استثناء);<br/>            أو إذا لم تُضاف الفقرة إلى أي مجموعة ITextFrame.Paragraphs (قم بإضافتها أولاً); |

### انظر أيضًا
* الفئة [`IBulletFormat`](/slides/python-net/ar/aspose.slides/ibulletformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)