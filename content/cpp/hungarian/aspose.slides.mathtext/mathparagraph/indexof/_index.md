---
title: IndexOf()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza egy adott IMathBlock indexét a gyűjteményben.
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) metódus


Meghatározza egy adott [IMathBlock](../../imathblock/) indexét a gyűjteményben.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A gyűjteményben keresendő elem. |

### Visszatérési érték

A *mathBlock* indexe, ha megtalálható a gyűjteményben; egyébként -1.
## Megjegyzések



Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [MathParagraph](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)