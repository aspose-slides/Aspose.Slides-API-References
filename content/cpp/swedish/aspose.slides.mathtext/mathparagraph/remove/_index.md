---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort den första förekomsten av ett specifikt objekt från samlingen/>
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) metod

Tar bort den första förekomsten av ett specifikt objekt från samlingen/>. 

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objektet som ska tas bort från samlingen. |

### Returvärde

Sant om *mathBlock* togs bort från samlingen; annars falskt. Denna metod returnerar också falskt om *mathBlock* inte finns i den ursprungliga samlingen/>.

## Anmärkningar



Exempel: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBlock](../../imathblock/)
* Klass [MathParagraph](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)