---
title: Clear()
second_title: Aspose.Slides untuk C++ Referensi API
description: Menghapus semua elemen dari koleksi.
type: docs
weight: 79
url: /id/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() metode


Menghapus semua elemen dari koleksi.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Catatan


Contoh: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Lihat Juga

* Kelas [MathParagraph](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)