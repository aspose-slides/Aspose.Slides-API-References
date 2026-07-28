---
title: get_NumberFormat()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje ciąg formatu dla obiektu DataLabels. Przeczytaj System::String."
type: docs
weight: 27
url: /pl/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() metoda

Reprezentuje ciąg formatu dla obiektu DataLabels. Zobacz [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Uwagi

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Jeśli nadrzędny element tego [DataLabelFormat](../../datalabelformat/) obiektu jest [DataLabelCollection](../../datalabelcollection/) kolekcją etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Gdy ta właściwość jest ustawiana na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" powoduje, że wszystkie DataLabels[i].NumberFormat mają wartość val).

## Zobacz również

* Klasa [String](../../../system/string/)
* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)