---
title: idx_get()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera element o określonym indeksie. Tylko do odczytu IMathBlock.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) method

Pobiera element o określonym indeksie. Tylko do odczytu [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy elementu, który ma zostać pobrany |

### Wartość zwracana

Blok tekstu matematycznego.

## Uwagi



Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)