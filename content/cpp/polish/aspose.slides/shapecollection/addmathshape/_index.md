---
title: AddMathShape()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy prostokątny kształt auto, który hostuje zawartość matematyczną i dodaje go na koniec kolekcji kształtów.
type: docs
weight: 365
url: /pl/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) metoda

Tworzy nowy prostokątny kształt auto, który hostuje zawartość matematyczną i dodaje go na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x ramki kształtu, w punktach. |
| y | **float** | Współrzędna y ramki kształtu, w punktach. |
| width | **float** | Szerokość ramki kształtu, w punktach. |
| height | **float** | Wysokość ramki kształtu, w punktach. |

### Wartość zwracana

Nowo utworzony [IAutoShape](../../iautoshape/).
## Uwagi

Poniższy przykład pokazuje, jak dodać równanie matematyczne w programie PowerPoint [Presentation](../../presentation/).
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

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)