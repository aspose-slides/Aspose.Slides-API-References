---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um slide de layout especificado à apresentação.
type: docs
weight: 1
url: /pt/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Adiciona uma cópia de um slide de layout especificado à apresentação.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) a clonar. |

### Valor de Retorno

Slide adicionado.

## Observações

Ao clonar um layout entre apresentações diferentes, o mestre do layout também pode ser clonado para manter a formatação de origem. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplas cópias do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. 

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Adiciona uma cópia de um slide de layout especificado à apresentação.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) a clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo layout. |

### Valor de Retorno

Slide adicionado.

## Observações

1) O novo layout será vinculado ao mestre definido na apresentação de destino. Portanto, isto equivale à cópia/colagem com a opção \"Use Destination Theme\" no PowerPoint. 2) Análogo deste método é o método [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) acessado com a propriedade [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [GlobalLayoutSlideCollection](../)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)