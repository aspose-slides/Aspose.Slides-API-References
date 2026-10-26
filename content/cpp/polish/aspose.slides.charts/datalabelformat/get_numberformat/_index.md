---
title: get_NumberFormat()
second_title: Aspose.Slides dla referencji API C++
description: "Reprezentuje ciąg formatu dla obiektu DataLabels. Przeczytaj System::String."
type: docs
weight: 27
url: /pl/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metoda

Reprezentuje ciąg formatu dla obiektu DataLabels. Przeczytaj [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Uwagi

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Jeśli rodzicem tego [DataLabelFormat](../) obiektu jest [DataLabelCollection](../../datalabelcollection/) kolekcja etykiet danych, to ta własność pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w [DataLabelCollection](../../datalabelcollection/) kolekcji. Gdy ta własność jest ustawiana na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat dla wszystkich etykiet danych w [DataLabelCollection](../../datalabelcollection/) kolekcji (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" powoduje, że wszystkie DataLabels[i].NumberFormat są równe val).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [DataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)