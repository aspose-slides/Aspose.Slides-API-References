---
title: GetOrCreateDataPointByIdx()
second_title: Aspose.Slides C++ API referenciája
description: "Ha a gyűjtemény már tartalmaz adatpontot a *index* indexen, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot a *index* ==N (amikor az adatpontok száma ebben a gyűjteményben kisebb vagy egyenlő N-nél) akkor hiányzó adatpontokat ad hozzá, és visszaadja az utolsót (amelynek a kért indexe van). Például a gyűjtemény indexei {0, 1, 2}, és a kért index 5. Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5 indexű adatpontot."
type: docs
weight: 170
url: /hu/aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx/
---
## ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t) metódus

Ha a gyűjtemény már tartalmaz adatpontot a *index* indexen, akkor visszaadja ezt az adatpontot. Ha a gyűjtemény nem tartalmaz adatpontot a *index* ==N indexen (amikor az adatpontok száma ebben a gyűjteményben kisebb vagy egyenlő N-nél), akkor hiányzó adatpontokat ad hozzá, és visszaadja az utolsót (amelynek a kért indexe van). Például a gyűjtemény indexei {0, 1, 2}, a kért index pedig 5. Ekkor a metódus hozzáadja a hiányzó adatpontokat: {0, 1, 2, 3, 4, 5}. És visszaadja az 5 indexű adatpontot.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::GetOrCreateDataPointByIdx(uint32_t index) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **uint32_t** | Index. |

### Visszatérési érték

Visszaadja a kért indexű adatpontot.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataPoint](../../ichartdatapoint/)
* Osztály [ChartDataPointCollection](../)
* Névtere [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)