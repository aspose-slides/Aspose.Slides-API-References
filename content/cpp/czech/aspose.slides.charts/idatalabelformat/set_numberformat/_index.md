---
title: set_NumberFormat()
second_title: Aspose.Slides pro C++ API referenční příručka
description: "Representuje řetězec formátu pro objekt DataLabels. Zapište System::String."
type: docs
weight: 40
url: /cs/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metoda

Representuje řetězec formátu pro objekt DataLabels. Zapište [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Poznámky



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```




Pokud je nadřazeným prvkem tohoto [DataLabelFormat](../../datalabelformat/) objektu kolekce [DataLabelCollection](../../datalabelcollection/) popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci [DataLabelCollection](../../datalabelcollection/). Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat pro všechny popisky dat v kolekci [DataLabelCollection](../../datalabelcollection/) (tzn. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" způsobí, že všechny DataLabels[i].NumberFormat budou mít hodnotu val). 
## Viz také

* Třída [String](../../../system/string/)
* Třída [IDataLabelFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)