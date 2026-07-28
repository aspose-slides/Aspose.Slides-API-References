---
title: set_Separator()
second_title: Aspose.Slides dla C++ Referencja API
description: "Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Zapisz System::String."
type: docs
weight: 339
url: /pl/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) metoda

Ustawia lub zwraca Variant reprezentujący separator używany dla etykiet danych na wykresie. Zapisz [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Uwagi

Jeśli rodzicem tego obiektu [DataLabelFormat](../../datalabelformat/) jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości Separator dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Ustawienie tej właściwości na wartość ustawia również tę wartość w właściwości Separator dla wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. "DataLabels.DefaultDataLabelFormat.Separator = val;" powoduje, że wszystkie DataLabels[i].Separator są równe val).

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)