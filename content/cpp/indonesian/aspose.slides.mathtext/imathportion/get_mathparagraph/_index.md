---
title: get_MathParagraph()
second_title: Aspose.Slides untuk Referensi API C++
description: Paragraf Matematika
type: docs
weight: 1
url: /id/aspose.slides.mathtext/imathportion/get_mathparagraph/
---
## IMathPortion::get_MathParagraph() metode

Paragraf Matematika

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathPortion::get_MathParagraph()=0
```

## Catatan

Contoh:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathParagraph](../../imathparagraph/)
* Kelas [IMathPortion](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)