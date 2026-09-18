---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection osztály

A prezentációban az összes elrendezési diát tartalmazó gyűjteményt képviseli.  
Kiterjeszti a LayoutSlideCollection osztályt a módszerekkel, amelyek lehetővé teszik elrendezési diák hozzáadását/klónozását a mesterelrendezési diák egyedi gyűjteményeinek egyesítése során.

**Inheritance:**[`GlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/hu/aspose.slides/layoutslidecollection)

A GlobalLayoutSlideCollection típus a következő tagokkal rendelkezik:

## Indexelő

| Név | Leírás |
| :- | :- |
| [`[index]`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Hozzáad egy másolatot a megadott elrendezési diáról a prezentációhoz. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Hozzáad egy másolatot a megadott elrendezési diáról a prezentációhoz. |
| [`get_by_type(self, type)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Visszaadja az első megadott típusú elrendezési diát.<br/> Az elrendezési dia típusa, amelyet keres.[`LayoutSlide`](/slides/python-net/hu/aspose.slides/layoutslide) a megadott típussal vagy None, ha nem található elrendezés. |
| [`remove(self, value)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Eltávolít egy elrendezést a gyűjteményből. |
| [`remove_unused(self)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/remove_unused/#) | Eltávolítja a nem használt elrendezési diákat (azok a diák, amelyeknél a HasDependingSlides hamis). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Hozzáad egy új elrendezési diát a prezentációhoz. |

### Lásd még
* osztály [`GlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection)
* osztály [`LayoutSlideCollection`](/slides/python-net/hu/aspose.slides/layoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)