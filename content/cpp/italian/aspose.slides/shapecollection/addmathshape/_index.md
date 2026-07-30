---
title: AddMathShape()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova forma automatica rettangolare per ospitare contenuti matematici e la aggiunge alla fine della collezione di forme.
type: docs
weight: 365
url: /it/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) metodo

Crea una nuova forma rettangolare automatica per ospitare contenuti matematici e la aggiunge alla fine della collezione di forme.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |

### Valore restituito

Il [IAutoShape](../../iautoshape/) appena creato.
## Osservazioni

Il seguente esempio mostra come aggiungere un'Equazione Matematica in PowerPoint [Presentation](../../presentation/). 
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

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ShapeCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)