---
title: RemoveAt()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل العنصر عند الفهرس المحدد في المجموعة.
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) الطريقة


يزيل العنصر عند الفهرس المحدد في المجموعة.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس صفر-الأساس للعنصر المراد إزالته. |
## ملاحظات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## انظر أيضًا

* فئة [IMathElementCollection](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)