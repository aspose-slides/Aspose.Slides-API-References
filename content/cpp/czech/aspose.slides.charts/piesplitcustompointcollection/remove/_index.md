---
title: Remove()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje položku ze sbírky.
type: docs
weight: 79
url: /cs/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metoda

Odstraní položku ze sbírky.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Data point remove to. |

### Návratová hodnota

true pokud byl prvek úspěšně odstraněn; jinak false. Tato metoda také vrací false, pokud prvek nebyl nalezen v [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metoda

Odstraní položku ze sbírky podle jejího indexu v kolekci bodů nadřazené řady.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Index of data point in parent series points collection. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)