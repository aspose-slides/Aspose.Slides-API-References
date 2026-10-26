---
title: AddClone()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje kopię określonego slajdu układu na koniec kolekcji.
type: docs
weight: 1
url: /pl/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda

Dodaje kopię określonego slajdu układu na koniec kolekcji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Nowy układ będzie połączony z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Tak więc jest to odpowiednik kopiowania/wklejania z opcją "Use Destination Theme" w programie PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) dostępna przez własność [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [MasterLayoutSlideCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)