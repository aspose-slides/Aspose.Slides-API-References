---
title: set_NumberFormat()
second_title: Aspose.Slides pro C++ API Reference
description: "Zastupuje formátovací řetězec pro objekt DataLabels. Zapište System::String."
type: docs
weight: 40
url: /cs/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metoda


Zastupuje formátovací řetězec pro objekt DataLabels. Zapište [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Poznámky



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Pokud je rodič tohoto objektu [DataLabelFormat](../) kolekcí [DataLabelCollection](../../datalabelcollection/) datových popisků, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové datové popisky v kolekci [DataLabelCollection](../../datalabelcollection/). Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat pro všechny datové popisky v kolekci [DataLabelCollection](../../datalabelcollection/) (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" způsobí, že všechny DataLabels[i].NumberFormat budou mít hodnotu val).

## Viz také

* Třída [String](../../../system/string/)
* Třída [DataLabelFormat](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)