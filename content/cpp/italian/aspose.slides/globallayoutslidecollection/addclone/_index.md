---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di una diapositiva layout specificata alla presentazione.
type: docs
weight: 1
url: /it/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metodo

Aggiunge una copia di una diapositiva layout specificata alla presentazione.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Diapositiva aggiunta.
## Osservazioni

Durante la clonazione di un layout tra presentazioni diverse, il master del layout può essere clonato anch'esso per mantenere la formattazione di origine. Viene utilizzato un registro interno per tenere traccia dei master clonati automaticamente, al fine di impedire la creazione di più cloni della stessa diapositiva master. La clonazione manuale delle diapositive master non sarà né impedita né registrata.
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metodo

Aggiunge una copia di una diapositiva layout specificata alla presentazione.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva master per un nuovo layout. |

### Valore restituito

Diapositiva aggiunta.
## Osservazioni

1) Il nuovo layout sarà collegato al master definito nella presentazione di destinazione. Pertanto si tratta dell'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) accessibile tramite la proprietà [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)