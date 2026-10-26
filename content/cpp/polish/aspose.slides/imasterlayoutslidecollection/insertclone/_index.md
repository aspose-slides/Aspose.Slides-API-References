---
title: InsertClone()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstawia kopię określonego slajdu układu w określone miejsce kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metoda


Wstawia kopię określonego slajdu układu w określone miejsce kolekcji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Wstawiony slajd.

## Uwagi

Nowy układ zostanie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Jest to więc odpowiednik kopiuj/wklej z opcją \"Use Destination Theme\" w programie PowerPoint. 

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)