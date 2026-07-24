---
title: AddClone()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu.
type: docs
weight: 1
url: /de/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) Methode

Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Hinzugefügte Folie.

## Hinweise



Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann auch das Master-Layout geklont werden, um die Quellformatierung beizubehalten. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Slides zu verhindern. Manuelles Klonen von Master-Slides wird weder verhindert noch registriert. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) Methode

Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Slide für ein neues Layout. |

### Rückgabewert

Hinzugefügte Folie.

## Hinweise



1) Das neue Layout wird mit dem definierten Master in der Zielpräsentation verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Ziel-Design verwenden“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/), auf die über die Eigenschaft [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) zugegriffen wird. 
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [GlobalLayoutSlideCollection](../)
* Klasse [IMasterSlide](../../imasterslide/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)