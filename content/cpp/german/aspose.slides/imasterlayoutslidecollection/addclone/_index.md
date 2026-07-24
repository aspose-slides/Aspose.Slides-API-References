---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu.
type: docs
weight: 1
url: /de/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Hinzugefügte Folie.

## Hinweise

1) Das neue Layout wird mit der übergeordneten Master-Folien für diese Layout-Folien-Sammlung verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/), auf die über die Eigenschaft [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) zugegriffen wird. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)