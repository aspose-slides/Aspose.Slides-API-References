---
title: ChartCategoryCollection class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection klasse

Vertegenwoordigt een collectie van [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory)

The ChartCategoryCollection type exposes the following members:

## Eigenschappen

| Eigenschap | Omschrijving |
| :- | :- |
| [`use_cells`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/use_cells/) | Als waar dan wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meerlagige categorieën).<br/>            Als onwaar dan wordt het werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen <br/>            meerlagige categorieën).<br/>            Lezen/schrijven **bool**. |
| [`grouping_level_count`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Geeft het aantal gebruikte categoriegroeperingsniveaus terug.<br/>            Is meer dan één voor meervoudige categorieën.<br/>            Alleen-lezen **int**. |

Gets the element at the specified index.

## Indexer

| Naam | Omschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Methoden

| Methode | Omschrijving |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Als de categorie bestaat in de collectie, retourneer deze. Anders wordt een nieuwe grafiekcategorie gemaakt van <br/>            [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) en toegevoegd aan de collectie. |
| [`add(self, value)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/add/#any) | Maakt een nieuwe [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory) van de waarde en voegt deze toe aan de collectie. |
| [`index_of(self, value)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Zoekt naar de opgegeven [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory) en geeft de nulgebaseerde index van de eerste vondst binnen de volledige collectie terug. |
| [`remove(self, value)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Verwijdert de opgegeven waarde. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Verwijdert het element op de opgegeven index. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection/clear/#) | Verwijdert alle elementen uit de collectie. |


### Zie ook
* klasse [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)