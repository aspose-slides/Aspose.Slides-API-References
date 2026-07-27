---
title: Reorder()
second_title: Referência da API Aspose.Slides para C++
description: Move o slide da coleção para a posição especificada.
type: docs
weight: 105
url: /pt/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) método

Move o slide da coleção para a posição especificada.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de destino. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para mover. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) método

Move os slides da coleção para a posição especificada. [Slides](../../) será colocado a partir do índice na ordem em que aparecem na lista.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de destino. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) para mover. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)