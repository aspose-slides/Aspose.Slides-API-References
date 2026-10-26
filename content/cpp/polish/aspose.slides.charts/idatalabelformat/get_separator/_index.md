---
title: get_Separator()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Zobacz System::String."
type: docs
weight: 326
url: /pl/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() method

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Zobacz [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Uwagi

Jeśli rodzicem tego obiektu [DataLabelFormat](../../datalabelformat/) jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Ustawienie tej właściwości na wartość powoduje także ustawienie tej samej wartości w właściwości Separator dla wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. "DataLabels.DefaultDataLabelFormat.Separator = val;" powoduje, że wszystkie DataLabels[i].Separator są równe val). 

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)