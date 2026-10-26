---
title: AddMathShape()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقوم بإنشاء شكل تلقائي مستطلي جديد لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال.
type: docs
weight: 365
url: /ar/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) طريقة

ينشئ شكلًا مستطيليًا تلقائيًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | إحداثي x لإطار الشكل\\u2019، بالنقاط. |
| y | **float** | إحداثي y لإطار الشكل\\u2019، بالنقاط. |
| width | **float** | عرض إطار الشكل\\u2019، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل\\u2019، بالنقاط. |

### قيمة الإرجاع

[IAutoShape](../../iautoshape/) الذي تم إنشاؤه حديثًا.

## ملاحظات

يوضح المثال التالي كيفية إضافة معادلة رياضية في PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IAutoShape](../../iautoshape/)
* فئة [ShapeCollection](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)