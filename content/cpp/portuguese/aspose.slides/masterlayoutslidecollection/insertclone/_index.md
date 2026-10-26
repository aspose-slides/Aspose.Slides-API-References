---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Insere uma cópia de um slide de layout especificado na posição especificada da coleção.
type: docs
weight: 14
url: /pt/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) método


Insere uma cópia de um slide de layout especificado na posição especificada da coleção.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) a ser clonado. |

### Valor de retorno

Slide inserido.

## Observações



Novo layout será vinculado ao slide mestre pai para esta coleção de slides de layout. Portanto, isto é análogo a copiar/colar com a opção “Use Destination Theme” no PowerPoint. 

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)