---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou sérii grafu a přidá ji do kolekce.
type: docs
weight: 14
url: /cs/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) metoda


Vytvoří novou sérii grafu a přidá ji do kolekce.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ řady |

### Návratová hodnota

Nová série grafu.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metoda


Vytvoří novou sérii grafu z [IChartDataCell](../../ichartdatacell/) a přidá ji do kolekce.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) který obsahuje název řady. |
| type | [ChartType](../../charttype/) | Nastavený typ řady |

### Návratová hodnota

Přidaná série grafu nebo řada, která již je v kolekci.

## Poznámky


Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index.



## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metoda


Vytvoří novou sérii grafu z [IChartCellCollection](../../ichartcellcollection/) a přidá ji do kolekce.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Buňky, které obsahují název řady. |
| type | [ChartType](../../charttype/) | Nastavený typ řady |

### Návratová hodnota

Přidaná série grafu nebo řada, která již je v kolekci.

## Poznámky


Pokud je série grafu vytvořena ze stejné buňky, která již v kolekci existuje, metoda nic nepřidá a vrátí její index.



## IChartSeriesCollection::Add(System::String, ChartType) metoda


Vytvoří novou sérii grafu z hodnoty a přidá ji do kolekce.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Název řady. |
| type | [ChartType](../../charttype/) | Nastavený typ řady |

### Návratová hodnota

Přidaná série grafu.



## Viz také

* Výčet [ChartType](../../charttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IChartSeries](../../ichartseries/)
* Třída [IChartSeriesCollection](../)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [IChartCellCollection](../../ichartcellcollection/)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)