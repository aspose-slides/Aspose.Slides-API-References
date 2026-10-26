---
title: Add()
second_title: Aspose.Slides pro referenci API v C++
description: Přidá novou buňku do kolekce.
type: docs
weight: 53
url: /cs/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method

Přidá novou buňku do kolekce.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nová buňka k přidání. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) method

Vytvoří [ChartDataCell](../../chartdatacell/) ze zadané hodnoty a přidá jej do kolekce.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |
## Poznámky

Tato metoda přidá list s názvem AUTO_DATA a vloží do něj všechny hodnoty. Pokud používáte [ChartDataWorkbook](../../chartdataworkbook/) k přidání nebo úpravě hodnot [Cell](../../../aspose.slides/cell/), ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [ChartCellCollection](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)