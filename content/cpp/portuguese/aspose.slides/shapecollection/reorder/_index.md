---
title: Reorder()
second_title: Referência da API Aspose.Slides para C++
description: Move a forma especificada para uma nova posição dentro da coleção de formas.
type: docs
weight: 339
url: /pt/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) método

Move a forma especificada para uma nova posição dentro da coleção de formas.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice de destino baseado em zero onde a forma será colocada. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser movido dentro da coleção. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) método

Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice de destino baseado em zero onde a primeira forma especificada será colocada; as formas subsequentes seguem na ordem fornecida. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Uma ou mais instâncias de [IShape](../../ishape/) a serem movidas dentro da coleção. |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)