---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una copia di una diapositiva layout specificata nella posizione specificata della collezione.
type: docs
weight: 14
url: /it/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metodo

Inserisce una copia di una diapositiva layout specificata nella posizione specificata della collezione.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Valore di ritorno

Diapositiva inserita.
## Note

Il nuovo layout sarà collegato alla diapositiva master principale per questa collezione di diapositive layout. Quindi è analogo a copia/incolla con l'opzione \"Use Destination Theme\" in PowerPoint. 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)