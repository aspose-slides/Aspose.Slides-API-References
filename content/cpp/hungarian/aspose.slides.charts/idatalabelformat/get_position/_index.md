---
title: get_Position()
second_title: Aspose.Slides C++ API referencia
description: Adatajelző pozícióját jelöli. Olvassa el a LegendDataLabelPosition-t.
type: docs
weight: 66
url: /hu/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() metódus


Adatajelző pozícióját jelöli. Olvassa el a [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## Megjegyzés


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság a [DataLabelCollection](../../datalabelcollection/) gyűjteményben lévő új adatcímkék Position tulajdonságának alapértelmezett értékét adja vissza vagy állítja be. A [DataLabel](../../datalabel/) objektumok pozícióját jelöli. Ennek a tulajdonságnak az értékkel való beállítása szintén ezt az értéket a [DataLabelCollection](../../datalabelcollection/) gyűjteményben lévő összes adatcímke Position tulajdonságára állítja (pl. \"DataLabels.DefaultDataLabelFormat.Position = val;\", ami miatt minden DataLabels[i].Position egyenlő lesz a val értékkel). 


## Lásd még

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* osztály [IDataLabelFormat](../)
* névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)