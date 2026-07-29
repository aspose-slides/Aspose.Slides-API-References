---
title: AddMathShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny rektangulär autoshape för att hålla matematiskt innehåll och lägger till den i slutet av shape-samlingen.
type: docs
weight: 365
url: /sv/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) method


Skapar en ny rektangulär autoshape för att innehålla matematiskt innehåll och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | x-koordinaten för shape-ramen, i punkter. |
| y | **float** | y-koordinaten för shape-ramen, i punkter. |
| width | **float** | Bredden på shape-ramen, i punkter. |
| height | **float** | Höjden på shape-ramen, i punkter. |

### Return Value

Det nyskapade [IAutoShape](../../iautoshape/).

## Remarks



Följande exempel visar hur man lägger till en matematisk ekvation i PowerPoint [Presentation](../../presentation/). 
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
* Klass [IAutoShape](../../iautoshape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)