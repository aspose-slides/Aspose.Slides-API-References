---
title: Add()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضيف عنصرًا رياضيًا إلى نهاية المجموعة.
type: docs
weight: 27
url: /ar/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) طريقة


يضيف عنصرًا رياضيًا إلى نهاية المجموعة.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | الـ [IMathElement](../../imathelement/) الذي سيُضاف إلى نهاية المجموعة. |
## ملاحظات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathElementCollection](../)
* مساحة الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)