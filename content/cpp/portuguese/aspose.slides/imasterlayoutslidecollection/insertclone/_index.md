---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Insere uma cópia de um slide de layout especificado na posição especificada da coleção.
type: docs
weight: 14
url: /pt/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) method

Insere uma cópia de um slide de layout especificado na posição especificada da coleção.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) a ser clonado. |

### Valor de Retorno

Slide inserido.
## Observações

O novo layout será vinculado ao slide mestre pai desta coleção de slides de layout. Portanto, isso equivale a copiar/colar com a opção "Use Destination Theme" no PowerPoint. 

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)