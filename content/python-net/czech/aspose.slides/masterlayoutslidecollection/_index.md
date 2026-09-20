---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection třída

Reprezentuje kolekci všech rozvržení snímků definovaného hlavního snímku.
            Rozšiřuje třídu LayoutSlideCollection o metody pro přidávání/vkládání/odstraňování/klonování/přeskupování rozvržení snímků v kontextu jednotlivých kolekcí rozvržení hlavního snímku.

**Dědičnost:**[`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/cs/aspose.slides/layoutslidecollection)

Typ MasterLayoutSlideCollection vystavuje následující členy:

## Indexér

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Vrací první rozvržení snímku zadaného typu.<br/>            Typ rozvržení snímku, který se má najít.[`LayoutSlide`](/slides/python-net/cs/aspose.slides/layoutslide) s určeným typem nebo None, pokud nebyly nalezeny žádné rozvržení. |
| [`remove(self, value)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Odstraňuje rozvržení z kolekce. |
| [`remove_unused(self)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Odstraňuje nepoužívané rozvržení snímků (rozvržení snímků, jejichž HasDependingSlides je false). |
| [`add_clone(self, source_layout)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Přidá kopii zadaného rozvržení snímku na konec kolekce. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Vloží kopii zadaného rozvržení snímku na určenou pozici v kolekci. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Přidá nový rozvržení snímku na konec kolekce. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Vloží nový rozvržení snímku na určenou pozici v kolekci. |
| [`remove_at(self, index)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Odstraňuje prvek na zadaném indexu v kolekci. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Přesune rozvržení snímku z kolekce na určenou pozici. |


### Viz také
* třída [`LayoutSlideCollection`](/slides/python-net/cs/aspose.slides/layoutslidecollection)
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)