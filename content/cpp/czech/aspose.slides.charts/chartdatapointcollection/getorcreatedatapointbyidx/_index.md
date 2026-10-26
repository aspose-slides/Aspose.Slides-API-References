---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Pokud kolekce již obsahuje datový bod s indexem index, pak vrátí tento datový bod. Pokud kolekce neobsahuje datový bod s indexem index ==N (když je počet datových bodů v této kolekci menší nebo roven N), přidá chybějící datové body a vrátí poslední (který má požadovaný index). Například indexy kolekce jsou {0, 1, 2} a požadovaný index je 5. Pak metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5}. A vrátí datový bod s indexem 5."
type: docs
weight: 170
url: /cs/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metoda

Pokud kolekce již obsahuje datový bod s indexem *index*, vrátí tento datový bod. Pokud kolekce neobsahuje datový bod s indexem *index* ==N (když je počet datových bodů v této kolekci menší nebo roven N), přidá chybějící datové body a vrátí poslední (který má požadovaný index). Například indexy kolekce jsou {0, 1, 2} a požadovaný index je 5. Pak metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5}. A vrátí datový bod s indexem 5.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Návratová hodnota

Vrací datový bod s požadovaným indexem.

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataPoint](../../ichartdatapoint/)
* Třída [ChartDataPointCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)