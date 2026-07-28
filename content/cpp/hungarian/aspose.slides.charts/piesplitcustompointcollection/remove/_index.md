---
title: Remove()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja az elemet a gyűjteményből.
type: docs
weight: 79
url: /hu/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) metódus

Eltávolítja az elemet a gyűjteményből.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Az eltávolítandó adatpont. |

### Visszatérési érték

true, ha az elem sikeresen eltávolításra került; egyébként false. Ez a metódus szintén false-t ad vissza, ha az elem nem található a [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) metódus

Eltávolítja az elemet a gyűjteményből az indexével a szülő sorozat pontgyűjteményében.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Az adatpont indexe a szülő sorozat pontgyűjteményében. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataPoint](../../ichartdatapoint/)
* Osztály [PieSplitCustomPointCollection](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)