---
title: get_PieSplitBy()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Specifikuje, jak určit, které datové body jsou ve druhém výseku nebo pruhu v grafu typu výseč-ve-výseči nebo pruh-ve-výseči. Jedná se o vlastnost nejen této řady, ale všech řad nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte get_ParentSeriesGroup()->get(set)_PieSplitBy() vlastnost čtení/zápisu pro změnu hodnoty. Pouze pro čtení PieSplitType.
type: docs
weight: 755
url: /cs/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metoda

Specifikuje, jak určit, které datové body jsou ve druhém výseku nebo pruhu v grafu typu výseč-ve-výseči nebo pruh-ve-výseči. Toto je vlastnost nejen této řady, ale všech řad nadřazené skupiny řad – jedná se o projekci odpovídající vlastnosti skupiny. A tak je tato vlastnost pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině řad. Použijte [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() vlastnost čtení/zápisu pro změnu hodnoty. Pouze pro čtení [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Poznámky

1) Toto je projekce vlastnosti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Pokud je hodnota vlastnosti [PieSplitType::Custom](../../piesplittype/), můžete definovat vlastní informace o rozdělení pomocí vlastnosti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Viz také

* Výčtový typ [PieSplitType](../../piesplittype/)
* Třída [ChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)