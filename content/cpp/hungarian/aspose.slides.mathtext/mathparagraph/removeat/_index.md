---
title: RemoveAt()
second_title: Aspose.Slides for C++ API referencia
description: Eltávolít egy elemet a gyűjtemény megadott indexén.
type: docs
weight: 157
url: /hu/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metódus


Eltávolít egy elemet a gyűjtemény megadott indexén.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az eltávolítandó elem nulláralapú indexe. |
## Megjegyzések



Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Lásd még

* Osztály [MathParagraph](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)