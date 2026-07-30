---
title: get_PieSplitBy()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu koláč-v-koláči nebo pruh-v-koláči. Jedná se o vlastnost nejen této řady, ale o všechny řady rodičovské skupiny řad - jde o projekci odpovídající vlastnosti skupiny. Tato vlastnost je tedy pouze pro čtení. Pro přístup k rodičovské skupině řad použijte vlastnost ParentSeriesGroup. K změně hodnoty použijte vlastnost get_ParentSeriesGroup()->get(set)_PieSplitBy() pro čtení/zápis. Pouze pro čtení PieSplitType.
type: docs
weight: 729
url: /cs/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metoda

Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu typu koláč-v-koláči nebo pruh-v-koláči. Jedná se o vlastnost nejen této řady, ale o všechny řady rodičovské skupiny řad – jde o projekci odpovídající vlastnosti skupiny. Proto je tato vlastnost pouze pro čtení. Pro přístup k rodičovské skupině řad použijte vlastnost ParentSeriesGroup. Použijte [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() vlastnost pro čtení/zápis pro změnu hodnoty. Pouze pro čtení [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Poznámky

1) Jedná se o projekci vlastnosti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Pokud je hodnota vlastnosti [PieSplitType::Custom](../../piesplittype/), můžete definovat vlastní rozdělení pomocí vlastnosti [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Viz také

* Enum [PieSplitType](../../piesplittype/)
* Třída [IChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)