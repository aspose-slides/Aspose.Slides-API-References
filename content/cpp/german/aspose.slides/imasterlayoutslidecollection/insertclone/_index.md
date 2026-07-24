---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position der Sammlung ein.
type: docs
weight: 14
url: /de/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) Methode

Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position der Sammlung ein.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Eingefügte Folie.

## Hinweise

Das neue Layout wird mit der übergeordneten Master-Folie für diese Layout-Folien-Sammlung verknüpft. Das entspricht dem Kopieren/Einfügen mit \"Use Destination Theme\"-Option in PowerPoint.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterLayoutSlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)