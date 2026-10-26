---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides dla Pythona poprzez .NET Referencję API
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection klasa

Reprezentuje kolekcję wszystkich slajdów układu zdefiniowanego slajdu master.  
Rozszerza klasę LayoutSlideCollection metodami do dodawania/wstawiania/usuwania/klonowania/zmiany kolejności slajdów układu w kontekście poszczególnych kolekcji slajdów układu mastera.

**Dziedziczenie:**[`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/pl/aspose.slides/layoutslidecollection)

Typ MasterLayoutSlideCollection udostępnia następujące elementy:

## Indexer

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Zwraca pierwszy slajd układu określonego typu.<br/>            Typ slajdu układu do znalezienia.[`LayoutSlide`](/slides/python-net/pl/aspose.slides/layoutslide) z określonym typem lub None, jeśli nie znaleziono układów. |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Usuwa układ z kolekcji. |
| [`remove_unused(self)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Usuwa nieużywane slajdy układu (slajdy układu, których HasDependingSlides ma wartość false). |
| [`add_clone(self, source_layout)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Dodaje kopię określonego slajdu układu na koniec kolekcji. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Wstawia kopię określonego slajdu układu na określoną pozycję w kolekcji. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Dodaje nowy slajd układu na koniec kolekcji. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Wstawia nowy slajd układu na określoną pozycję w kolekcji. |
| [`remove_at(self, index)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Usuwa element pod określonym indeksem w kolekcji. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Przenosi slajd układu z kolekcji na określoną pozycję. |


### Zobacz także
* klasa [`LayoutSlideCollection`](/slides/python-net/pl/aspose.slides/layoutslidecollection)
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)