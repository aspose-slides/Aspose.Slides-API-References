---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort en layout från samlingen.
type: docs
weight: 66
url: /sv/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) method


Tar bort en layout från samlingen.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutbilden att ta bort från samlingen. |
## Anmärkningar



1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först. 2) Du kan också använda [ILayoutSlide::Remove](../../ilayoutslide/remove/)-metoden för att förenkla koden. 
## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [LayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)