---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides للغة Python عبر .NET API Reference
description: 
type: docs
url: /ar/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
يضبط التحويلات الافتراضية غير الصفرية لتحديد الإزاحة الفعلية للفقرة Indent و MarginLeft عندما تكون العلامات النقطية مفعلة (كما يفعل PowerPoint إذا تم تمكين العلامات النقطية/الترقيم للفقرة). إذا تم تعطيل العلامات النقطية يتم فقط إعادة ضبط Indent و MarginLeft للفقرة (كما يفعل PowerPoint إذا تم تعطيل العلامات النقطية/الترقيم للفقرة). يتم تطبيق إزاحات المسافات فيما يتعلق بسياق العلامة النقطية الحالي - IBulletFormat.Type، .NumberedBulletStyle و FontHeight للجزء الأول. يتم تطبيق إزاحات المسافات غير الصفرية على Indent و MarginLeft الفعليين للفقرة الحالية (لجعل القيم الناتجة قيمًا محلية).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | استدعاء هذه الطريقة لا يهم ويرمي **System.InvalidOperationException** في الحالات التالية:<br/>            إذا كان الكائن المنسق الأب ليس فقرة (على سبيل المثال استدعاء ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() سيؤدي إلى رمي استثناء);<br/>            أو إذا لم تُضاف الفقرة إلى أي مجموعة ITextFrame.Paragraphs (أضفها أولاً); |



### انظر أيضًا
* الصنف [`BulletFormat`](/slides/python-net/ar/aspose.slides/bulletformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)