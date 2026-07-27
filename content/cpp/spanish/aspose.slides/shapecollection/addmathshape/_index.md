---
title: AddMathShape()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una nueva forma automática de rectángulo para alojar contenido matemático y la añade al final de la colección de formas.
type: docs
weight: 365
url: /es/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) método


Crea una nueva forma automática de rectángulo para alojar contenido matemático y la añade al final de la colección de formas.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |

### Valor de retorno

El [IAutoShape](../../iautoshape/) recién creado.
## Observaciones



El siguiente ejemplo muestra cómo agregar una ecuación matemática en PowerPoint [Presentation](../../presentation/). 
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAutoShape](../../iautoshape/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)