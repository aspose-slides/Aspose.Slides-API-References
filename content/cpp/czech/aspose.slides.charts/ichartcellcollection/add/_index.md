---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá novou buňku do kolekce.
type: docs
weight: 53
url: /cs/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda


Přidá novou buňku do kolekce.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nová buňka k přidání. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metoda


Vytvoří [IChartDataCell](../../ichartdatacell/) ze zadané hodnoty a přidá jej do kolekce.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |
## Poznámky



Tato metoda přidá list s názvem AUTO_DATA a vloží do něj všechny hodnoty. Pokud používáte [IChartDataWorkbook](../../ichartdataworkbook/) k přidání nebo úpravě hodnot [Cell](../../../aspose.slides/cell/), ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných touto metodou nesmí překročit 16711680



## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [IChartCellCollection](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)