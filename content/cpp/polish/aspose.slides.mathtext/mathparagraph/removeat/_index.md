---
title: RemoveAt()
second_title: Odwołanie do API Aspose.Slides for C++
description: Usuwa element o podanym indeksie w kolekcji.
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metoda

Usuwa element o podanym indeksie w kolekcji.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy elementu do usunięcia. |
## Uwagi



Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Zobacz także

* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)