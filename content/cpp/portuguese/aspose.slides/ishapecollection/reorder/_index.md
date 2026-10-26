---
title: Reorder()
second_title: Referência da API Aspose.Slides para C++
description: Move a forma especificada para uma nova posição dentro da coleção de formas.
type: docs
weight: 300
url: /pt/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) método


Move a forma especificada para uma nova posição dentro da coleção de formas.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice de destino baseado em zero onde a forma será colocada. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) para mover dentro da coleção. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) método


Move as formas especificadas dentro da coleção de formas, colocando-as a partir do índice fornecido.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice de destino baseado em zero onde a primeira forma especificada será colocada; as formas subsequentes seguem na ordem fornecida. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Uma ou mais instâncias de [IShape](../../ishape/) para mover dentro da coleção. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)