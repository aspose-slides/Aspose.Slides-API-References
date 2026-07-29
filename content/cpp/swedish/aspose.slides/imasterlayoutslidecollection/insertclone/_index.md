---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en angiven layoutbild på en specificerad position i samlingen.
type: docs
weight: 14
url: /sv/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metod

Infogar en kopia av en specificerad layoutbild på den angivna positionen i samlingen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad bild.
## Anmärkningar

Ny layout kommer att länkas med överordnad masterbild för denna layoutbildssamling. Så detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)