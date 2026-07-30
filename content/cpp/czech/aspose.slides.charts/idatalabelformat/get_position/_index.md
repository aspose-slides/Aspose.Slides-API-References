---
title: get_Position()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Representuje pozici datového popisku. Přečtěte si LegendDataLabelPosition.
type: docs
weight: 66
url: /cs/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() metoda

Representuje pozici datového popisku. Přečtěte si [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## Poznámky

Pokud je rodič tohoto [DataLabelFormat](../../datalabelformat/) objektu [DataLabelCollection](../../datalabelcollection/) kolekce datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové datové popisky v kolekci [DataLabelCollection](../../datalabelcollection/). Representuje pozici pro objekty [DataLabel](../../datalabel/). Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu do vlastnosti Position pro všechny datové popisky v kolekci [DataLabelCollection](../../datalabelcollection/) (tj. \"DataLabels.DefaultDataLabelFormat.Position = val;\" způsobí, že všechny DataLabels[i].Position jsou rovny val).

## Viz také

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Třída [IDataLabelFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)