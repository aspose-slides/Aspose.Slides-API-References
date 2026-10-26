---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt ein Element aus der Sammlung.
type: docs
weight: 79
url: /de/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) Methode

Entfernt ein Element aus der Sammlung.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Zu entfernender Datenpunkt. |

### Rückgabewert

true, wenn das Element erfolgreich entfernt wurde; sonst false. Diese Methode gibt ebenfalls false zurück, wenn das Element im [System::Collections::Generic::List](../../../system.collections.generic/list/){T} nicht gefunden wurde.

## PieSplitCustomPointCollection::Remove(int32_t) Methode

Entfernt ein Element aus der Sammlung anhand seines Indexes in der übergeordneten Serien-Punktesammlung.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Index des Datenpunkts in der übergeordneten Serien-Punktesammlung. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataPoint](../../ichartdatapoint/)
* Klasse [PieSplitCustomPointCollection](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)