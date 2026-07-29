---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en specificerad layoutbild i slutet av samlingen.
type: docs
weight: 1
url: /sv/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metod

Lägger till en kopia av en specificerad layoutbild i slutet av samlingen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Tillagd bild.

## Anmärkningar

1) Den nya layouten kommer att länkas till den överordnade masterbilden för den här layoutbilder-samlingen. Så detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 2) Motsvarigheten till denna metod är metoden [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) som nås via egenskapen [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterLayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)