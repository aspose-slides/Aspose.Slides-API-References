---
title: Reorder()
second_title: Aspose.Slides C++ API referenciája
description: Áthelyezi a diát a gyűjteményből a megadott pozícióba.
type: docs
weight: 157
url: /hu/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) metódus


Áthelyezi a diát a gyűjteményből a megadott pozícióba.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Cél index. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | áthelyezendő [Slide](../../slide/). |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) metódus


Áthelyezi a diaképeket a gyűjteményből a megadott pozícióba. [Slides](../../) a megadott indextől kezdve kerül elhelyezésre a listában megjelenő sorrendben.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Cél index. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | áthelyezendő [Slides](../../). |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ISlide](../../islide/)
* Osztály [SlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)