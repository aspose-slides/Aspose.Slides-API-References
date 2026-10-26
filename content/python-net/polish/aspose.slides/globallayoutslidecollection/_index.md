---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection klasa

Reprezentuje kolekcję wszystkich slajdów układu w prezentacji.  
Rozszerza klasę LayoutSlideCollection o metody dodawania/klonowania slajdów układu w kontekście łączenia poszczególnych kolekcji slajdów układu nadrzędnego.

**Dziedziczenie:**[`GlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/pl/aspose.slides/layoutslidecollection)

Typ GlobalLayoutSlideCollection udostępnia następujące elementy:

## Indexer

| Nazwa | Opis |
| :- | :- |
| [`[index]`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [`get_by_type(self, type)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Zwraca pierwszy slajd układu określonego typu.<br/>            Typ slajdu układu do znalezienia.[`LayoutSlide`](/slides/python-net/pl/aspose.slides/layoutslide) o określonym typie lub None, jeśli nie znaleziono żadnych układów. |
| [`remove(self, value)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Usuwa układ z kolekcji. |
| [`remove_unused(self)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/remove_unused/#) | Usuwa nieużywane slajdy układu (slajdy układu, których HasDependingSlides jest false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Dodaje nowy slajd układu do prezentacji. |

### Zobacz także
* klasa [`GlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection)
* klasa [`LayoutSlideCollection`](/slides/python-net/pl/aspose.slides/layoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)