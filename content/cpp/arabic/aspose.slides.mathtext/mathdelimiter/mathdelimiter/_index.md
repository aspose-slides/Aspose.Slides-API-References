---
title: MathDelimiter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يهيئ MathDelimiter بالعنصر المحدد كمعامل أساسي واحد
type: docs
weight: 144
url: /ar/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) منشئ

يُهيّئ [MathDelimiter](../) بالعنصر المحدد كمعامل أساسي واحد

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | العنصر الأساسي الذي يُطبق عليه الفاصل. يمكن أن يكون null. |
## ملاحظات



مثال: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathDelimiter](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)