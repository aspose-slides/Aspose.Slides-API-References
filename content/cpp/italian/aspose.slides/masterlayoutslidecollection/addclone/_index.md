---
title: AddClone()
second_title: Aspose.Slides per C++ Riferimento API
description: Aggiunge una copia di una diapositiva layout specificata alla fine della raccolta.
type: docs
weight: 1
url: /it/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Aggiunge una copia di una diapositiva layout specificata alla fine della raccolta.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) da clonare. |

### Return Value

Diapositiva aggiunta.
## Remarks



1) Il nuovo layout sarà collegato alla diapositiva master padre per questa raccolta di diapositive layout. Quindi è analogo a copia/incolla con l'opzione \"Use Destination Theme\" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) accessibile tramite la proprietà [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)