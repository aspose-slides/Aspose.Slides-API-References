---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una copia di una diapositiva layout specificata nella posizione specificata della collezione.
type: docs
weight: 14
url: /it/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) method


Inserisce una copia di una diapositiva layout specificata nella posizione specificata della collezione.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Valore di ritorno

Diapositiva inserita.
## Osservazioni



Il nuovo layout sarà collegato alla diapositiva master principale per questa raccolta di layout diapositive. Quindi è l'analogo di copia/incolla con l'opzione \"Use Destination Theme\" in PowerPoint. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterLayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)