---
title: ToArray()
second_title: Referência da API Aspose.Slides para C++
description: Cria e retorna um array que contém todas as formas.
type: docs
weight: 326
url: /pt/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() método

Cria e retorna um array que contém todas as formas.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Valor de Retorno

Um array de objetos [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) método

Cria e retorna um array que contém todas as formas no intervalo especificado.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | **int32_t** | O índice da primeira forma a ser retornada. |
| count | **int32_t** | O número de formas a serem retornadas. |

### Valor de Retorno

Um array de objetos [IShape](../../ishape/).

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)