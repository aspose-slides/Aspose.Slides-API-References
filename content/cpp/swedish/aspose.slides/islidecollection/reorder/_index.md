---
title: Reorder()
second_title: Aspose.Slides för C++ API-referens
description: Flyttar bilden från samlingen till den angivna positionen.
type: docs
weight: 105
url: /sv/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) metod

Flyttar bilden från samlingen till den angivna positionen.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Målindex. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att flytta. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) metod

Flyttar bilder från samlingen till den angivna positionen. [Slides](../../) kommer att placeras med start från index i den ordning de förekommer i listan.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Målindex. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) att flytta. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ISlide](../../islide/)
* Klass [ISlideCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)