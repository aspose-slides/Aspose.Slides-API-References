---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en specificerad layoutbild på en angiven position i samlingen.
type: docs
weight: 14
url: /sv/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metod


Infogar en kopia av en angiven layoutbild på en specificerad position i samlingen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad bild.
## Anmärkningar



Den nya layouten kommer att länkas till den överordnade masterbilden för den här layoutbildssamlingen. Detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)