---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung/>
type: docs
weight: 105
url: /de/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) Methode

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Das Objekt, das aus der Sammlung entfernt werden soll. |

### Rückgabewert

true, wenn *mathBlock* erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn *mathBlock* im ursprünglichen Sammlung nicht gefunden wird/>.

## Anmerkungen

```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)