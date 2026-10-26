---
title: AddClone()
second_title: Aspose.Slides C++ API-referencia
description: Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez.
type: docs
weight: 1
url: /hu/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metódus

Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozandó. |

### Visszatérési érték

Hozzáadott dia.

## Megjegyzések

1) Az új elrendezés a szülő mester diával lesz összekapcsolva ennél az elrendezési dia-gyűjteménynél. Ez tehát a PowerPointban a \"Use Destination Theme\" opcióval történő másolás/beillesztés analógiája. 2) Ennek a metódusnak az analógiája a [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) metódus, amely a [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) tulajdonsággal érhető el. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [MasterLayoutSlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)