---
title: Reorder()
second_title: Aspose.Slides pro C++ - API reference
description: Přesune snímek ze sbírky na zadanou pozici.
type: docs
weight: 105
url: /cs/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) metoda

Přesune snímek ze sbírky do zadané pozice.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Cílový index. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) k přesunu. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) metoda

Přesune snímky ze sbírky do zadané pozice. [Slides](../../) bude umístěn od indexu v pořadí, v jakém se objeví v seznamu.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Cílový index. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) k přesunu. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ISlide](../../islide/)
* Třída [ISlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)