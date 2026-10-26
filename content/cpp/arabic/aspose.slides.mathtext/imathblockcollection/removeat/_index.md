---
title: RemoveAt()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يزيل عنصرًا في الفهرس المحدد من المجموعة.
type: docs
weight: 53
url: /ar/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) طريقة


يزيل عنصرًا في الفهرس المحدد من المجموعة.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | المؤشر الصفري للعنصر المراد إزالته. |
## الملاحظات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## انظر أيضًا

* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)