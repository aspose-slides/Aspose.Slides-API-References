---
title: Remove()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja a megadott objektum első előfordulását a gyűjteményből/>
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) metódus

Eltávolítja a megadott objektum első előfordulását a gyűjteményből/>

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Az objektum, amelyet el kell távolítani a gyűjteményből. |

### Visszatérési érték

igaz, ha a *mathBlock*  sikeresen el lett távolítva a gyűjteményből; egyébként hamis. Ez a metódus is hamisat ad vissza, ha a *mathBlock*  nem található az eredeti gyűjteményben/>

## Megjegyzések

Példa: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [MathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)