---
title: IndexOf()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Określa indeks konkretnego IMathBlock w kolekcji.
type: docs
weight: 131
url: /pl/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) metoda

Określa indeks konkretnego [IMathBlock](../../imathblock/) w kolekcji.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Element do zlokalizowania w kolekcji. |

### Wartość zwracana

Indeks *mathBlock* jeśli zostanie znaleziony w kolekcji; w przeciwnym razie -1.

## Uwagi



Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)