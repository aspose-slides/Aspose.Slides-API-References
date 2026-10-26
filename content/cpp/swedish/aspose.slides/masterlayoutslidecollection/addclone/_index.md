---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en specificerad layout-bild i slutet av samlingen.
type: docs
weight: 1
url: /sv/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metod


Lägger till en kopia av en specificerad layout-bild i slutet av samlingen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Tillagd bild.

## Anmärkningar



1) Ny layout kommer att länkas till föräldra-master-bilden för den här layout-bilder-samlingen. Så detta är motsvarigheten till kopiera/klistra med \"Use Destination Theme\"-alternativet i PowerPoint. 2) Motsvarigheten till denna metod är metoden [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) som nås via egenskapen [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [MasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)