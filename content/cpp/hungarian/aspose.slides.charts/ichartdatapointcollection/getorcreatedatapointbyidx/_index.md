---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides for C++ API Referencia
description: "Ha a gyűjtemény már tartalmaz adatpontot a index index indexeléssel, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot a index index ==N (amikor a gyűjteményben lévő adatpontok száma kisebb vagy egyenlő N-nél), akkor hozzáadja a hiányzó adatpontokat, és visszaadja az utolsót (amely a kért indexű). Például a gyűjtemény indexei {0, 1, 2}, és a kért index 5. Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5-ös indexű adatpontot."
type: docs
weight: 131
url: /hu/aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx/
---
## IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metódus


Ha a gyűjtemény már tartalmaz adatpontot a *index* indexűvel, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot a *index* ==N indexűvel (amikor a gyűjteményben lévő adatpontok száma kisebb vagy egyenlő N-nél), akkor hozzáadja a hiányzó adatpontokat, és visszaadja az utolsót (amely a kért indexű). Például a gyűjtemény indexei {0, 1, 2}, és a kért index 5. Ebben az esetben a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5-ös indexű adatpontot.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Visszatérési érték

Visszaadja a kért indexű adatpontot.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataPoint](../../ichartdatapoint/)
* Osztály [IChartDataPointCollection](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)