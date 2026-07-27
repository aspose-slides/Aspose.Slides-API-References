---
title: Reorder()
second_title: Referência da API Aspose.Slides para C++
description: Move o slide da coleção para a posição especificada.
type: docs
weight: 157
url: /pt/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) método

Move slide from the collection to the specified position.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de destino. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para mover. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) método

Move slides from the collection to the specified position. [Slides](../../) será colocado a partir do índice na ordem em que aparecem na lista.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de destino. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) para mover. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ISlide](../../islide/)
* Classe [SlideCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)