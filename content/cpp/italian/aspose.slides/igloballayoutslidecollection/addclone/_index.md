---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di una slide di layout specificata alla presentazione.
type: docs
weight: 1
url: /it/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Aggiunge una copia di una slide di layout specificata alla presentazione.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Slide aggiunta.

## Osservazioni

Durante la clonazione di un layout tra presentazioni diverse, il master del layout può essere clonato anche per mantenere la formattazione di origine. Un registro interno viene utilizzato per tracciare i master clonati automaticamente e per impedire la creazione di più cloni dello stesso master slide. Il cloning manuale dei master slide non verrà né impedito né registrato. 

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Aggiunge una copia di una slide di layout specificata alla presentazione.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide per un nuovo layout. |

### Valore restituito

Slide aggiunta.

## Osservazioni

Il nuovo layout verrà collegato al master definito nella presentazione di destinazione. Pertanto è analogo a copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IGlobalLayoutSlideCollection](../)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)