---
title: Contains()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si la colección contiene un valor específico.
type: docs
weight: 118
url: /es/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) método


Determina si la colección contiene un valor específico.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | El objeto a localizar en la colección. |

### Valor de retorno

true si *mathBlock*  se encuentra en la colección; de lo contrario, false.
## Observaciones



Ejemplo: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBlock](../../imathblock/)
* Clase [MathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)