---
title: RemoveAt()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirtilen dizinindeki bir öğeyi kaldırır.
type: docs
weight: 157
url: /tr/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metodu

Koleksiyonun belirtilen dizinindeki bir öğeyi kaldırır.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Kaldırılacak öğenin sıfır tabanlı indeksi. |
## Açıklamalar

Örnek:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Ayrıca Bakınız

* Sınıf [MathParagraph](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)