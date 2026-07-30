---
title: Reorder()
second_title: Aspose.Slides pro C++ API Reference
description: Přesune snímek ze sbírky na určenou pozici.
type: docs
weight: 157
url: /cs/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) metoda

Přesune snímek ze sbírky na určenou pozici.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Cílový index. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) k přesunutí. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) metoda

Přesune snímky ze sbírky na určenou pozici. [Slides](../../) bude umístěn počínaje indexem v pořadí, v jakém se objevují v seznamu.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Cílový index. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) k přesunutí. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [ISlide](../../islide/)
* Třída [SlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)