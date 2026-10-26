---
title: get_NumberFormat()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Zastupuje řetězec formátu pro objekt DataLabels. Přečtěte si System::String."
type: docs
weight: 27
url: /cs/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metoda

Zastupuje řetězec formátu pro objekt DataLabels. Přečtěte si [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Poznámky

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Pokud je rodičem tohoto [DataLabelFormat](../../datalabelformat/) objektu [DataLabelCollection](../../datalabelcollection/) kolekce datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové datové popisky v kolekci [DataLabelCollection](../../datalabelcollection/). Když je tato vlastnost nastavena na určitou hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat u všech datových popisků v kolekci [DataLabelCollection](../../datalabelcollection/) (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" způsobí, že všechny DataLabels[i].NumberFormat budou mít hodnotu val).

## Viz také

* Třída [String](../../../system/string/)
* Třída [IDataLabelFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)