---
title: IChartCategory class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartcategory/
---
## IChartCategory klasse

Geeft grafiekcategorieën weer.

Het type IChartCategory bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`use_cell`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/use_cell/) | Als true dan is de AsCell-eigenschap actueel. Met andere woorden, werkblad wordt gebruikt voor <br/>            het opslaan van de categorie (dit geval ondersteunt een meerlagige categorie).<br/>            Als false dan is de AsLiteral-eigenschap actueel. Met andere woorden, werkblad wordt NIET gebruikt <br/>            voor het opslaan van de categorie (en dit geval ondersteunt geen meerlagige categorieën).<br/>            Alleen-lezen **bool**. |
| [`as_cell`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/as_cell/) | Geeft een IChartDataCell-object terug of stelt het in.<br/>            Als de categorie meerlagig is, wordt het IChartDataCell-object gebruikt voor niveau "0".<br/>            Lezen/schrijven [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/as_literal/) | Geeft AsLiteral terug of stelt het in als UseCell false is.<br/>            Lezen/schrijven **any**. |
| [`value`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/value/) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap.<br/>            Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap.<br/>            Lezen/schrijven **any**. |
| [`grouping_levels`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/grouping_levels/) | Beheerde container van de waarden van de groeperingsniveaus van de grafiekcategorie.<br/>            Een meerlagige categorie bevat meer dan één groeperingsniveau.<br/>            Indexering van groeperingsniveaus begint bij nul.<br/>            Alleen-lezen [`IChartCategoryLevelsManager`](/slides/python-net/nl/aspose.slides.charts/ichartcategorylevelsmanager). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/ichartcategory/remove/#) | Verwijdert de categorie uit de grafiek. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)