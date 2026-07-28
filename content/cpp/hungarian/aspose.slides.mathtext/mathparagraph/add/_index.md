---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: Az IMathBlock-ot a gyűjtemény végére adja hozzá.
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) metódus

Hozzáadja a(z) [IMathBlock](../../imathblock/)-t a gyűjtemény végéhez.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Egy matematikai blokk, amely a gyűjtemény végéhez lesz hozzáadva |
## Megjegyzések



Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [MathParagraph](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)