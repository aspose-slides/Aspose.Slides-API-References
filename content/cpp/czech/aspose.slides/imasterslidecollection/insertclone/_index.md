---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. Propojené snímky rozvržení budou také zkopírovány.
type: docs
weight: 66
url: /cs/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metoda

Vloží kopii určeného hlavního snímku na určenou pozici v kolekci. Propojené snímky rozvržení budou také zkopírovány.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) pro klonování. |

### Návratová hodnota

Vložený hlavní snímek.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMasterSlide](../../imasterslide/)
* Třída [IMasterSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)