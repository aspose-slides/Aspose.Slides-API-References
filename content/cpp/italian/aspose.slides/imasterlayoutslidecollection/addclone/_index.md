---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di una diapositiva di layout specificata alla fine della raccolta.
type: docs
weight: 1
url: /it/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metodo

Aggiunge una copia di una diapositiva di layout specificata alla fine della raccolta.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Diapositiva aggiunta.

## Osservazioni

1) Il nuovo layout verrà collegato alla diapositiva master padre per questa raccolta di layout diapositive. Quindi è analogo a copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) accessibile tramite la proprietà [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)