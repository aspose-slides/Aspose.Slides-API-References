---
title: MathPortion()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi instance baru dari kelas MathPortion.
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() konstruktor


Menginisialisasi instance baru dari kelas [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Catatan


Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Lihat Juga

* Kelas [MathPortion](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)