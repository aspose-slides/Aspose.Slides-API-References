---
title: ChartCategory class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartcategory/
---
## ChartCategory klasse

Stelt grafiekcategorieën voor.

Het type ChartCategory exposeert de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`use_cell`](/slides/python-net/nl/aspose.slides.charts/chartcategory/use_cell/) | Als true is de AsCell eigenschap actueel. Met andere woorden, werkblad wordt gebruikt voor <br/>            het opslaan van een categorie (dit geval ondersteunt een meerlagige categorie).<br/>            Als false is de AsLiteral eigenschap actueel. Met andere woorden, werkblad wordt NIET gebruikt <br/>            voor het opslaan van een categorie (en dit geval ondersteunt geen meerlagige categorieën).<br/>            Alleen-lezen **bool**. |
| [`as_cell`](/slides/python-net/nl/aspose.slides.charts/chartcategory/as_cell/) | Geeft een IChartDataCell object terug of stelt het in.<br/>            Als de categorie meerlagig is, dan wordt het IChartDataCell object gebruikt voor niveau "0".<br/>            Lezen/Schrijven [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/nl/aspose.slides.charts/chartcategory/as_literal/) | Geeft een AsLiteral object terug of stelt het in.<br/>            Lezen/Schrijven **any**. |
| [`value`](/slides/python-net/nl/aspose.slides.charts/chartcategory/value/) | Als UseCell true is, dan vertegenwoordigt deze eigenschap de AsCell.Value eigenschap.<br/>            Als UseCell false is, dan vertegenwoordigt deze eigenschap de AsLiteral eigenschap.<br/>            Lezen/Schrijven **any**. |
| [`grouping_levels`](/slides/python-net/nl/aspose.slides.charts/chartcategory/grouping_levels/) | Beheerde container van de waarden van de groeperingsniveaus van de grafiekcategorie.<br/>            Een meerlagige categorie bevat meer dan één groeperingsniveau.<br/>            Indexering van groeperingsniveaus begint bij nul.<br/>            Alleen-lezen [`IChartCategoryLevelsManager`](/slides/python-net/nl/aspose.slides.charts/ichartcategorylevelsmanager). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/chartcategory/remove/#) | Verwijdert de categorie uit de grafiek. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)