---
title: RemoveAt()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina el elemento en el índice especificado de la colección.
type: docs
weight: 170
url: /es/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) método

Elimina el elemento en el índice especificado de la colección.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero del elemento a eliminar. |

## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Ver también

* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)