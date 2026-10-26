---
title: AddClone()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje kopię określonego slajdu układu na koniec kolekcji.
type: docs
weight: 1
url: /pl/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda


Dodaje kopię określonego slajdu układu na koniec kolekcji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Dodany slajd.

## Uwagi


1) Nowy układ zostanie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Tak więc jest to odpowiednik kopiuj/wklej z opcją \"Use Destination Theme\" w programie PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) dostępna przez właściwość [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IMasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)