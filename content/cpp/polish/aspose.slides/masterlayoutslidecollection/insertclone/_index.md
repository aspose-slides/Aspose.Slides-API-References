---
title: InsertClone()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wstawia kopię określonego slajdu układu w określonej pozycji kolekcji.
type: docs
weight: 14
url: /pl/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metoda

Wstawia kopię określonego slajdu układu w określonej pozycji w kolekcji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do klonowania. |

### Wartość zwracana

Wstawiony slajd.

## Uwagi

Nowy układ będzie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Dlatego jest to odpowiednik kopiuj/wklej z opcją "Use Destination Theme" w programie PowerPoint.

## Patrz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [MasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)