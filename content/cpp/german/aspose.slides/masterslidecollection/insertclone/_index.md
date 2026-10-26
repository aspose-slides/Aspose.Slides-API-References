---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt eine Kopie einer angegebenen Masterfolie an der angegebenen Position der Sammlung ein. Verknüpfte Layoutfolien werden ebenfalls kopiert.
type: docs
weight: 105
url: /de/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) Methode

Fügt eine Kopie einer angegebenen Masterfolie an der angegebenen Position der Sammlung ein. Verknüpfte Layoutfolien werden ebenfalls kopiert.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Eingefügte Masterfolie.

## Bemerkungen

Das folgende Beispiel zeigt, wie man eine Masterfolie in einer anderen PowerPoint [Presentation](../../presentation/) klont.
```cpp
// Instanziieren der Presentation-Klasse, um die Quelldatei der Präsentation zu laden
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instanziieren der Presentation-Klasse für die Zielpräsentation (in die Folie geklont werden soll)
auto destPres = System::MakeObject<Presentation>();

// Instanziieren von ISlide aus der Folienmenge in der Quellpräsentation zusammen mit
// Masterfolie
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Masterfolien der Zielpräsentation abrufen
auto masters = destPres->get_Masters();
// Klonen der gewünschten Masterfolie von der Quellpräsentation in die Master-Menge der
// Zielpräsentation
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Menge der Folien in der Zielpräsentation
auto slides = destPres->get_Slides();
// Quellfolie in die Ziel-Folienmenge klonen.
slides->AddClone(sourceSlide, iSlide, true);
// Speichern der Zielpräsentation auf die Festplatte
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)