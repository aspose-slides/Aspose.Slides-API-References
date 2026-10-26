---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.
type: docs
weight: 66
url: /pt/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) método

Insere uma cópia de um slide mestre especificado na posição especificada da coleção. Slides de layout vinculados também serão copiados.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index do novo slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide mestre inserido.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [IMasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)