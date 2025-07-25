---
title: AddMathShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection.
type: docs
weight: 365
url: /aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) method


Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | The x-coordinate of the shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the shape\\u2019s frame, in points. |
| width | **float** | The width of the shape\\u2019s frame, in points. |
| height | **float** | The height of the shape\\u2019s frame, in points. |

### Return Value

The newly created [IAutoShape](../../iautoshape/).
## Remarks



The following example shows how to add Mathematical Equation in PowerPoint [Presentation](../../presentation/). 
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
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)