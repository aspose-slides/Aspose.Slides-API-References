---
title: Insert()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بإدراج MathElement في المجموعة عند الفهرس المحدد.
type: docs
weight: 157
url: /ar/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) طريقة

يقوم بإدراج MathElement في المجموعة عند الفهرس المستند إلى الصفر.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس المستند إلى الصفر الذي يجب إدراج MathElement عنده. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | MathElement المراد إدراجه. |
## ملاحظات

مثال: ```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBlock](../)
* نطاق [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)