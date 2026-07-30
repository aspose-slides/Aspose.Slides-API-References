---
title: Add()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá IMathBlock na konec kolekce.
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) metoda

Přidá [IMathBlock](../../imathblock/) na konec kolekce.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Matematický blok, který bude přidán na konec kolekce |
## Poznámky



Příklad: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathBlock](../../imathblock/)
* Třída [MathParagraph](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)