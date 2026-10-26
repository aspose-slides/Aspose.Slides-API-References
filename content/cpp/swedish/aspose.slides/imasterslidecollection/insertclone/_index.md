---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en specificerad master-bild på en angiven position i samlingen. Länkade layout-bilder kopieras också.
type: docs
weight: 66
url: /sv/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metod

Infogar en kopia av en angiven master-bild på en angiven position i samlingen. Länkade layoutbilder kopieras också.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad master-bild.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMasterSlide](../../imasterslide/)
* Klass [IMasterSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)