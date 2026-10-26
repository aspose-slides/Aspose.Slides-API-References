---
title: get_HandleRepeatedSpaces()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحدد كيفية التعامل مع أحرف المسافة العادية المتكررة أثناء تصدير Markdown.
type: docs
weight: 235
url: /ar/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const طريقة

يحدد كيفية معالجة الأحرف المتكررة للمسافة العادية أثناء تصدير Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## ملاحظات

تحدد هذه الخاصية ما إذا كانت المسافات المتتالية هي:
* محفوظة كأحرف مسافة عادية،
* يتم التبديل بينها كمسافات عادية وكيانات غير قابلة للكسر (**&nbsp;**)،
* أو تُستبدَل بالكامل (بعد الأولى) بـ **&nbsp;** للحفاظ على المحاذاة البصرية في ناتج Markdown.

القيمة الافتراضية هي [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## انظر أيضًا

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* فئة [MarkdownSaveOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)