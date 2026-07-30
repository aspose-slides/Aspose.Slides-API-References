---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z IChartDataCell a přidá ji do kolekce.
type: docs
weight: 92
url: /cs/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda


Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z [IChartDataCell](../../ichartdatacell/) a přidá ji do kolekce.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) používaný k vytvoření kategorie grafu. |

### Návratová hodnota

Přidaná nebo existující kategorie.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metoda


Vytvoří nový [ChartCategory](../../chartcategory/) z hodnoty a přidá jej do kolekce.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

Přidáno [IChartCategory](../../ichartcategory/).
## Poznámky



Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [ChartDataWorkbook](../../chartdataworkbook/) k přidávání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680



## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartCategory](../../ichartcategory/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [ChartCategoryCollection](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)