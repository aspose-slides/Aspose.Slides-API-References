---
title: get_NumberFormat()
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje řetězec formátu pro objekt DataLabels. Přečtěte si System::String."
type: docs
weight: 27
url: /cs/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metoda

Representuje řetězec formátu pro objekt DataLabels. Přečtěte si [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Poznámky

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Pokud je nadřazený objekt tohoto [DataLabelFormat](../) objektu [DataLabelCollection](../../datalabelcollection/) kolekcí DataLabels, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové DataLabels v kolekci [DataLabelCollection](../../datalabelcollection/). Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat pro všechny DataLabels v kolekci [DataLabelCollection](../../datalabelcollection/) (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" způsobí, že všechny DataLabels[i].NumberFormat budou rovny val).

## Viz také

* Třída [String](../../../system/string/)
* Třída [DataLabelFormat](../)
* Prostor názvů [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)