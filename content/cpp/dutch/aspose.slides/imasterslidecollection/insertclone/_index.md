---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven masterslide in op een opgegeven positie in de collectie. Gelinkte layoutslides worden ook gekopieerd.
type: docs
weight: 66
url: /nl/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) methode

Voegt een kopie van een opgegeven masterslide in op een opgegeven positie in de collectie. Gelinkte layoutslides worden ook gekopieerd.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) te klonen. |

### Retourwaarde

Ingevoegde masterslide.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [IMasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)