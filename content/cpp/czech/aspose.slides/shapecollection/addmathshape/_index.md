---
title: AddMathShape()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří nový obdélníkový automatický tvar pro hostování matematického obsahu a přidá jej na konec kolekce tvarů.
type: docs
weight: 365
url: /cs/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) metoda

Vytvoří nový obdélníkový automatický tvar pro hostování matematického obsahu a přidá jej na konec kolekce tvarů.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | X-souřadnice rámce tvaru v bodech. |
| y | **float** | Y-souřadnice rámce tvaru v bodech. |
| width | **float** | Šířka rámce tvaru v bodech. |
| height | **float** | Výška rámce tvaru v bodech. |

### Return Value

Nově vytvořený [IAutoShape](../../iautoshape/).

## Remarks

Následující příklad ukazuje, jak přidat matematickou rovnici v PowerPointu [Presentation](../../presentation/). 
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IAutoShape](../../iautoshape/)
* Třída [ShapeCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)