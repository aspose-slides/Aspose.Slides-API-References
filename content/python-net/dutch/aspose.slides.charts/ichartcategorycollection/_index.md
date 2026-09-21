---
title: IChartCategoryCollection class
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection klasse

Stelt een collectie van [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory) voor

Het type IChartCategoryCollection biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`use_cells`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/use_cells/) | Als true dan wordt werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt een multi-level categories).<br/>            Als false dan wordt werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen <br/>            multi-level categories).<br/>            Lezen/Schrijven **bool**. |
| [`grouping_level_count`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Retourneert het aantal gebruikte groeperingsniveaus voor categorieën.<br/>            Is meer dan één voor multilevel categories.<br/>            Alleen-lezen **int**. |

Haalt het element op op de opgegeven index.

## Indexer

| Naam | Beschrijving |
| :- | :- |
| [`[index]`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Als de categorie bestaat in de collectie, retourneer deze. Anders wordt een nieuwe chart category gemaakt van <br/>            [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) en toegevoegd aan de collectie. |
| [`add(self, value)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/add/#any) | Maakt een nieuwe [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory) van de waarde en voegt deze toe aan de collectie. |
| [`index_of(self, value)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Zoekt naar de opgegeven [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory) en retourneert de nul-gebaseerde index van de eerste overeenkomst binnen de volledige Collection |
| [`remove(self, value)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Verwijdert de opgegeven waarde. |
| [`remove_at(self, index)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Verwijdert het element op de gegeven index. |
| [`clear(self)`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection/clear/#) | Verwijdert alle elementen uit de collectie. |

### Zie ook
* klasse [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)