---
title: RemoveAt()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina un elemento en el índice especificado de la colección.
type: docs
weight: 157
url: /es/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) método

Elimina un elemento en el índice especificado de la colección.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero del elemento a eliminar. |
## Observaciones

Ejemplo:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Ver también

* Clase [MathParagraph](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)