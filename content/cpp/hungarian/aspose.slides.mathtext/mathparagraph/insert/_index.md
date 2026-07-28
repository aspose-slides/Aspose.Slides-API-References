---
title: Insert()
second_title: Aspose.Slides for C++ API-referencia
description: Beszúrja az IMathBlock elemet a gyűjteménybe a megadott indexnél.
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathparagraph/insert/
---
## MathParagraph::Insert(int32_t, System::SharedPtr\<IMathBlock\>) metódus

Beszúrja a(z) [IMathBlock](../../imathblock/) elemet a gyűjteménybe a megadott indexnél.

```cpp
void Aspose::Slides::MathText::MathParagraph::Insert(int32_t index, System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullaalapú index, amelynél be kell szúrni egy elemet. |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | A beszúrandó [IMathBlock](../../imathblock/). |
## Megjegyzések

Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Insert(0, block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [MathParagraph](../)
* Névtere [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)