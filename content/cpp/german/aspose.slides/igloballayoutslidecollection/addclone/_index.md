---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt der Präsentation eine Kopie einer angegebenen Layout-Folie hinzu.
type: docs
weight: 1
url: /de/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) Methode

Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Hinzugefügte Folie.

## Hinweise

Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann der Master des Layouts ebenfalls geklont werden, um die Quellformatierung beizubehalten. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Slides zu verhindern. Das manuelle Klonen von Master-Slides wird weder verhindert noch registriert.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) Methode

Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) zum Klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Slide für ein neues Layout. |

### Rückgabewert

Hinzugefügte Folie.

## Hinweise

Das neue Layout wird mit dem im Ziel-Präsentation definierten Master verknüpft. Das entspricht der Kopieren/Einfügen-Funktion mit der Option „Zieldesign verwenden“ in PowerPoint.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IGlobalLayoutSlideCollection](../)
* Klasse [IMasterSlide](../../imasterslide/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)