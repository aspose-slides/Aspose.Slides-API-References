---
title: set_Position()
second_title: Aspose.Slides C++ API referencia
description: Az adatcímke pozícióját jelöli. Írja be a LegendDataLabelPosition.
type: docs
weight: 79
url: /hu/aspose.slides.charts/idatalabelformat/set_position/
---
## IDataLabelFormat::set_Position(LegendDataLabelPosition) metódus

A adatcímke pozícióját jelöli. Írja [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Position(LegendDataLabelPosition value)=0
```
## Megjegyzések

Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a Position tulajdonság alapértelmezett értékét az új adatcímkékre a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. A [DataLabel](../../datalabel/) objektumok pozícióját jelöli. A tulajdonság értékének beállítása ugyanakkor ezt az értéket a Position tulajdonságra is beállítja az összes adatcímkére a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (pl. \"DataLabels.DefaultDataLabelFormat.Position = val;\", ami azt eredményezi, hogy minden DataLabels[i].Position értéke megegyezik a val-el).

## Lásd még

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)