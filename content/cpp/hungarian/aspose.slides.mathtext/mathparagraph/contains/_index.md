---
title: Contains()
second_title: Aspose.Slides for C++ API-referencia
description: Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket.
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) metódus

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Az objektum, amelyet a gyűjteményben keresni kell. |

### Visszatérési érték

true, ha a *mathBlock* megtalálható a gyűjteményben; egyébként false.

## Megjegyzések



Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [MathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)