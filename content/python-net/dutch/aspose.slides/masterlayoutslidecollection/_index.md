---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection klasse

Stelt een collectie van alle layout-dia's van de gedefinieerde masterslide voor.  
Breidt de LayoutSlideCollection klasse uit met methoden voor het toevoegen/invoegen/verwijderen/klonen/herordenen van layout-dia's in de context van de afzonderlijke collecties van layout-dia's van de master.

**Erfenis:**[`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/nl/aspose.slides/layoutslidecollection)

Het type MasterLayoutSlideCollection biedt de volgende leden weer:

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Retourneert de eerste layout-dia van het opgegeven type.<br/>            Een type layout-dia om te vinden.[`LayoutSlide`](/slides/python-net/nl/aspose.slides/layoutslide) met opgegeven type of None als er geen lay-outs zijn gevonden. |
| [`remove(self, value)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Verwijdert een layout uit de collectie. |
| [`remove_unused(self)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Verwijdert ongebruikte layout-dia's (layout-dia's waarvan HasDependingSlides onwaar is). |
| [`add_clone(self, source_layout)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Voegt een kopie van een opgegeven layout-dia in op een gespecificeerde positie in de collectie. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Voegt een nieuwe layout-dia toe aan het einde van de collectie. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Voegt een nieuwe layout-dia in op een gespecificeerde positie in de collectie. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Verwijdert het element op het gespecificeerde index in de collectie. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Verplaatst een layout-dia van de collectie naar de gespecificeerde positie. |

### Zie ook
* klasse [`LayoutSlideCollection`](/slides/python-net/nl/aspose.slides/layoutslidecollection)
* klasse [`MasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/masterlayoutslidecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)