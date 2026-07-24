---
title: AddMathShape()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein neues Rechteck-AutoShape, das mathematischen Inhalt hostet, und fügt es am Ende der Formensammlung hinzu.
type: docs
weight: 365
url: /de/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) Methode


Erstellt ein neues Rechteck-AutoShape, das mathematischen Inhalt hostet, und fügt es am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des Formrahmens, in Punkten. |
| y | **float** | Die y-Koordinate des Formrahmens, in Punkten. |
| width | **float** | Die Breite des Formrahmens, in Punkten. |
| height | **float** | Die Höhe des Formrahmens, in Punkten. |

### Rückgabewert

Das neu erstellte [IAutoShape](../../iautoshape/).
## Hinweise



Das folgende Beispiel zeigt, wie man eine mathematische Gleichung in PowerPoint [Presentation](../../presentation/) hinzufügt.
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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)