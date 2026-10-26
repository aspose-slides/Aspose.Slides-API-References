---
title: set_NumberFormat()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje ciąg formatowania dla obiektu DataLabels. Zapisz System::String."
type: docs
weight: 40
url: /pl/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metoda


Represents the format string for the DataLabels object. Write [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Uwagi



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Jeśli rodzicem tego [DataLabelFormat](../../datalabelformat/) obiektu jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Gdy ta właściwość zostanie ustawiona na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" powoduje, że wszystkie DataLabels[i].NumberFormat mają wartość równą val). 

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)