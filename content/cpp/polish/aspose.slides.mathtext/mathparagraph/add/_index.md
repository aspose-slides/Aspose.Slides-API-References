---
title: Add()
second_title: Referencja API Aspose.Slides for C++
description: Dodaje IMathBlock na koniec kolekcji.
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) metoda


Dodaje [IMathBlock](../../imathblock/) na koniec kolekcji.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Blok matematyczny, który zostanie dodany na koniec kolekcji |
## Uwagi



Przykład: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [MathParagraph](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)