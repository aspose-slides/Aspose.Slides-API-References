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
| [`use_cell`](/slides/python-net/nl/aspose.slides.charts/chartcategory/use_cell/) | Als true dan is de AsCell-eigenschap actueel. Met andere woorden, worksheet wordt gebruikt voor <br/> het opslaan van categorie (dit geval ondersteunt een meerlagige categorie).<br/> Als false dan is de AsLiteral-eigenschap actueel. Met andere woorden, worksheet wordt NIET gebruikt <br/> voor het opslaan van categorie (en dit geval ondersteunt geen meerlagige categorieën).<br/> Alleen-lezen **bool**. |
| [`as_cell`](/slides/python-net/nl/aspose.slides.charts/chartcategory/as_cell/) | Retourneert of stelt IChartDataCell-object in.<br/>            Als categorie meerlagig is, wordt het IChartDataCell-object gebruikt voor niveau "0".<br/>            Lezen/schrijven [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/nl/aspose.slides.charts/chartcategory/as_literal/) | Retourneert of stelt AsLiteral-object in.<br/>            Lezen/schrijven **any**. |
| [`value`](/slides/python-net/nl/aspose.slides.charts/chartcategory/value/) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap.<br/>            Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap.<br/>            Lezen/schrijven **any**. |
| [`grouping_levels`](/slides/python-net/nl/aspose.slides.charts/chartcategory/grouping_levels/) | Beheerde container van de waarden van de groeperingsniveaus van de grafiekcategorie.<br/>            Een meerlagige categorie bevat meer dan één groeperingsniveau.<br/>            Indexering van groeperingsniveaus is nulgebaseerd.<br/>            Alleen-lezen [`IChartCategoryLevelsManager`](/slides/python-net/nl/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/nl/aspose.slides.charts/chartcategory/cached_value/) | Haalt de gecachte waarde van een grafiekcategorie op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/chartcategory/remove/#) | Verwijdert categorie uit grafiek. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)