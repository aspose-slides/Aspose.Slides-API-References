---
title: set_ShowLegendKey()
second_title: Aspose.Slides C++ API referenciája
description: Egy meghatározott diagram adatcímkéjének jelmagyarázat-rajzoló kulcs megjelenítési viselkedését reprezentálja. Igaz, ha az adatcímke jelmagyarázat-rajzoló kulcsa látható. Írja bool.
type: docs
weight: 105
url: /hu/aspose.slides.charts/idatalabelformat/set_showlegendkey/
---
## IDataLabelFormat::set_ShowLegendKey(bool) metódus


Egy meghatározott diagram adatcímkéjének jelmagyarázat-rajzoló kulcs megjelenítési viselkedését reprezentálja. Igaz, ha az adatcímke jelmagyarázat-rajzoló kulcsa látható. Írja **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLegendKey(bool value)=0
```

## Megjegyzések


Ha ennek a [DataLabelFormat](../../datalabelformat/) objektumnak a szülője egy [DataLabelCollection](../../datalabelcollection/) adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkék számára a [DataLabelCollection](../../datalabelcollection/) gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása szintén beállítja ezt az értéket a ShowLegendKey tulajdonságra az összes adatcímke esetében a [DataLabelCollection](../../datalabelcollection/) gyűjteményben (azaz "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" eredményezi, hogy minden DataLabels[i].ShowLegendKey egyenlő legyen a val értékkel). 



## Lásd még

* Osztály [IDataLabelFormat](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)