---
title: AddClone()
second_title: Aspose.Slides C++ API referenciája
description: Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez.
type: docs
weight: 1
url: /hu/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metódus


Hozzáad egy másolatot a megadott elrendezési diáról a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

Hozzáadott dia.
## Megjegyzések



1) Az új elrendezés a szülő mesterdiával lesz összekapcsolva ebben az elrendezési diák gyűjteményben. Így ez a PowerPointban a \"Use Destination Theme\" opcióval végzett másolás/beillesztés analógiája. 2) Ennek a metódusnak az analógiája a [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) metódus, amely a [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) tulajdonnal érhető el. 
## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IMasterLayoutSlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)