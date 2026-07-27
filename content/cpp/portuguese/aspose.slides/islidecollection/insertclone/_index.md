---
title: InsertClone()
second_title: Aspose.Slides para C++ Referência da API
description: Insere uma cópia de um slide especificado na posição especificada da coleção.
type: docs
weight: 27
url: /pt/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method

Insere uma cópia de um slide especificado na posição especificada da coleção.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |

### Valor de Retorno

Slide inserido.

## Observações

Ao clonar um slide entre apresentações diferentes, o mestre do slide também pode ser clonado. Um registro interno é usado para rastrear mestres clonados automaticamente e impedir a criação de múltiplos clones do mesmo slide mestre. A clonagem manual de slides mestres não será impedida nem registrada. Se precisar de mais controle sobre o processo de clonagem, use [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) ou [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) para clonar slides e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) para clonar mestres. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

Insere uma cópia de um slide especificado na posição especificada da coleção.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide de layout para um novo slide. |

### Valor de Retorno

Slide inserido.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

Insere uma cópia de um slide de origem especificado na posição especificada da coleção. O layout apropriado será selecionado automaticamente a partir do mestre especificado (o layout apropriado é o layout com o mesmo Type ou Name do layout do slide de origem). Se não houver um layout apropriado, o layout do slide de origem será clonado (se allowCloneMissingLayout é true) ou PptxEditException será lançado (se allowCloneMissingLayout é false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice do novo slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) para clonar. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide mestre para um novo slide. |
| allowCloneMissingLayout | **bool** | Se não houver um layout apropriado no mestre especificado, o layout do slide de origem será clonado (se allowCloneMissingLayout é true) ou PptxEditException será lançado (se allowCloneMissingLayout é false). |

### Valor de Retorno

Slide inserido.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)