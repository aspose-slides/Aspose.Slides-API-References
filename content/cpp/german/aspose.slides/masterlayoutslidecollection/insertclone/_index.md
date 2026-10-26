---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer angegebenen Layoutfolie an der angegebenen Position der Sammlung ein.
type: docs
weight: 14
url: /de/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) Methode


Fügt eine Kopie einer angegebenen Layoutfolie an der angegebenen Position der Sammlung ein.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Eingefügte Folie.

## Hinweise



Neue Layout wird mit der übergeordneten Masterfolie für diese Layout-Folien-Sammlung verknüpft. Das entspricht dem Kopieren/Einfügen mit der Option "Use Destination Theme" in PowerPoint. 

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)