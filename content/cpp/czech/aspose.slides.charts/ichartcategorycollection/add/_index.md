---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z IChartDataCell a přidá ji do kolekce.
type: docs
weight: 53
url: /cs/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metoda

Pokud kategorie v kolekci existuje, vrátí ji. Jinak vytvoří novou kategorii grafu z [IChartDataCell](../../ichartdatacell/) a přidá ji do kolekce.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) použitá pro vytvoření kategorie grafu. |

### Návratová hodnota

Přidaná nebo existující kategorie.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metoda

Vytvoří nový [IChartCategory](../../ichartcategory/) z hodnoty a přidá jej do kolekce.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Hodnota. |

### Návratová hodnota

Přidaný [IChartCategory](../../ichartcategory/).

## Poznámky

Tato metoda přidá list s názvem AUTO_DATA a přidá do něj všechny hodnoty. Pokud používáte [IChartDataWorkbook](../../ichartdataworkbook/) k přidávání nebo úpravě hodnot buněk, ujistěte se, že tento list nepoužíváte. Maximální počet hodnot přidaných pomocí této metody nesmí překročit 16711680

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartCategory](../../ichartcategory/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [IChartCategoryCollection](../)
* Třída [Object](../../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)