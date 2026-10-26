---
title: idx_get()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على العنصر في الفهرس المحدد. للقراءة فقط IMathElement.
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) طريقة


يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر المراد الحصول عليه |
## ملاحظات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## انظر أيضاً

* النوع المعرف [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathElementCollection](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)