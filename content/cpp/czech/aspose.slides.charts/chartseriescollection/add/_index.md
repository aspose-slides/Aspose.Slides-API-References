---
title: Add()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou řadu grafu a přidá ji do kolekce.
type: docs
weight: 53
url: /cs/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) metoda

Vytvoří novou řadu grafu a přidá ji do kolekce.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | Typ řady |

### Návratová hodnota

Nová řada grafu.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) metoda

Vytvoří novou řadu grafu z [ChartDataCell](../../chartdatacell/) a přidá ji do kolekce.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) který obsahuje název řady. |
| type | [ChartType](../../charttype/) | Typ nastavený pro řadu. |

### Návratová hodnota

Přidaná řada grafu nebo řada, která již je v kolekci.

## Poznámky

Pokud je řada grafu vytvořena ze stejné buňky, která již je v kolekci, metoda nic nepřidá a vrátí její index.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) metoda

Vytvoří novou řadu grafu z [ChartCellCollection](../../chartcellcollection/) a přidá ji do kolekce.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | Buňky, které obsahují název řady. |
| type | [ChartType](../../charttype/) | Typ nastavený pro řadu. |

### Návratová hodnota

Přidaná řada grafu nebo řada, která již je v kolekci.

## Poznámky

Pokud je řada grafu vytvořena ze stejné buňky, která již je v kolekci, metoda nic nepřidá a vrátí její index.

## ChartSeriesCollection::Add(System::String, ChartType) metoda

Vytvoří novou řadu grafu z hodnoty a přidá ji do kolekce.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | Název řady. |
| type | [ChartType](../../charttype/) | Typ nastavený pro řadu. |

### Návratová hodnota

Přidaná řada grafu.

## Viz také

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartSeries](../../ichartseries/)
* Třída [ChartSeriesCollection](../)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [IChartCellCollection](../../ichartcellcollection/)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)