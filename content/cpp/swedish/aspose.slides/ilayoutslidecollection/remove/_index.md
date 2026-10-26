---
title: Remove()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort en layout från samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metod


Tar bort en layout från samlingen.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutbilden som ska tas bort från samlingen. |
## Anmärkningar



1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap i förväg. 2) Du kan också använda [ILayoutSlide::Remove](../../ilayoutslide/remove/)-metod för att förenkla koden. 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [ILayoutSlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)