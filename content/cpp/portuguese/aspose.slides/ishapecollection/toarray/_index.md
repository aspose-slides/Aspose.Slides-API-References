---
title: ToArray()
second_title: Aspose.Slides para C++ Referência da API
description: Cria e devolve um array que contém todas as formas.
type: docs
weight: 287
url: /pt/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() método


Cria e devolve um array que contém todas as formas.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Valor de Retorno

Um array de objetos [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) método


Cria e devolve um array que contém todas as formas no intervalo especificado.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | O índice da primeira forma a ser devolvida. |
| count | **int32_t** | O número de formas a ser devolvido. |

### Valor de Retorno

Um array de objetos [IShape](../../ishape/).

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)