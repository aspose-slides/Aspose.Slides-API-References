---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection osztály

A meghatározott master slide összes layout slide gyűjteményét képviseli.
            Kiterjeszti a LayoutSlideCollection osztályt olyan módszerekkel, amelyek a master elrendezési diák egyedi gyűjteményei kontextusában lehetővé teszik a layout slides hozzáadását/beszúrását/eltávolítását/másolását/újrarendezését.

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/hu/aspose.slides/layoutslidecollection)

A MasterLayoutSlideCollection típus a következő tagokat teszi elérhetővé:

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Visszaadja a megadott típusú első layout slide-ot.<br/>            A keresendő layout slide típusa.[`LayoutSlide`](/slides/python-net/hu/aspose.slides/layoutslide) megadott típussal, vagy None, ha nem található layout. |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Eltávolít egy layout-ot a gyűjteményből. |
| [`remove_unused(self)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Eltávolítja a nem használt layout slide-okat (azok a layout slide-ok, amelyeknél a HasDependingSlides hamis). |
| [`add_clone(self, source_layout)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | A megadott layout slide egy másolatát a gyűjtemény végéhez adja hozzá. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | A megadott layout slide egy másolatát a gyűjtemény megadott pozíciójába szúrja be. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Új layout slide-ot ad a gyűjtemény végéhez. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Új layout slide-ot szúr be a gyűtemény megadott pozíciójába. |
| [`remove_at(self, index)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Áthelyezi a layout slide-ot a gyűjteményből a megadott pozícióba. |

### Lásd még
* osztály [`LayoutSlideCollection`](/slides/python-net/hu/aspose.slides/layoutslidecollection)
* osztály [`MasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)