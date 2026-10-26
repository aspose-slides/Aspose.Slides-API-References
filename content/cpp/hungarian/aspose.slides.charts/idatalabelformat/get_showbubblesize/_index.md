---
title: get_ShowBubbleSize()
second_title: Aspose.Slides C++ API referencia
description: Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését reprezentálja. A True megjeleníti a buborékméret értékét. A False elrejti. Olvasás bool.
type: docs
weight: 222
url: /hu/aspose.slides.charts/idatalabelformat/get_showbubblesize/
---
## IDataLabelFormat::get_ShowBubbleSize() metódus


Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését jelenti. A True megjeleníti a buborékméret értékét. A False elrejti. Olvasás **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowBubbleSize()=0
```

## Megjegyzések


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowBubbleSize tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ezzel a tulajdonsággal értéket megadva ez az érték beállítódik a ShowBubbleSize tulajdonságra az összes adatcímke esetén a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz \"DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;\" miatt az összes DataLabels[i].ShowBubbleSize értéke megegyezik a val értékkel).

## Lásd még

* Osztály [IDataLabelFormat](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)