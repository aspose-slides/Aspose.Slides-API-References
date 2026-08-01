---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert de eerste instantie van een specifiek object uit de collectie/>
type: docs
weight: 105
url: /nl/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) methode

Verwijdert de eerste voorkomen van een specifiek object uit de collectie/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Het object dat uit de collectie moet worden verwijderd. |

### Retourwaarde

true als *mathBlock* succesvol uit de collectie is verwijderd; anders false. Deze methode retourneert ook false als *mathBlock* niet in de oorspronkelijke collectie wordt gevonden/>.

## Opmerkingen



Voorbeeld: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [MathParagraph](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)