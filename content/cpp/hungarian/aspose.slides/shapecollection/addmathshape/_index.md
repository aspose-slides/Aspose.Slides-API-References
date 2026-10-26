---
title: AddMathShape()
second_title: Aspose.Slides C++ API-referenciája
description: Létrehoz egy új téglalap automatikus alakzatot a matematikai tartalom számára, és az alakzatgyűjtemény végéhez adja hozzá.
type: docs
weight: 365
url: /hu/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) metódus

Új téglalap automatikus alakzatot hoz létre a matematikai tartalom számára, és a shape collection végéhez adja hozzá.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A shape\u2019s keret x-koordinátája, pontban. |
| y | **float** | A shape\u2019s keret y-koordinátája, pontban. |
| width | **float** | A shape\u2019s keret szélessége, pontban. |
| height | **float** | A shape\u2019s keret magassága, pontban. |

### Visszatérési érték

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## Megjegyzések

A következő példa azt mutatja, hogyan lehet Matematikai Egyenletet hozzáadni a PowerPoint [Presentation](../../presentation/)-ban. 
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

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)