---
title: AddMathShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw rechthoekig autoshape aan om wiskundige inhoud te hosten en voegt het toe aan het einde van de shape-collectie.
type: docs
weight: 365
url: /nl/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) methode


Maakt een nieuw rechthoekig autoshape aan om wiskundige inhoud te hosten en voegt het toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van het frame van de shape, in punten. |
| y | **float** | De y-coördinaat van het frame van de shape, in punten. |
| width | **float** | De breedte van het frame van de shape, in punten. |
| height | **float** | De hoogte van het frame van de shape, in punten. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).
## Opmerkingen



Het volgende voorbeeld toont hoe je een wiskundige vergelijking toevoegt in PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)