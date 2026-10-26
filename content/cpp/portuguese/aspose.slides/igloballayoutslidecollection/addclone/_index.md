---
title: AddClone()
second_title: Referência da API Aspose.Slides for C++
description: Adiciona uma cópia de um slide de layout especificado à apresentação.
type: docs
weight: 1
url: /pt/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) método

Adiciona uma cópia de um slide de layout especificado à apresentação.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide adicionado.

## Observações

Ao clonar um layout entre apresentações diferentes, o mestre do layout também pode ser clonado para manter a formatação de origem. Um registro interno é usado para rastrear mestres clonados automaticamente, a fim de impedir a criação de múltiplas cópias do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. 

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) método

Adiciona uma cópia de um slide de layout especificado à apresentação.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo layout. |

### Valor de Retorno

Slide adicionado.

## Observações

O novo layout será vinculado ao mestre definido na apresentação de destino. Portanto, isso é análogo a copiar/colar com a opção "Use Destination Theme" no PowerPoint. 

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IGlobalLayoutSlideCollection](../)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)