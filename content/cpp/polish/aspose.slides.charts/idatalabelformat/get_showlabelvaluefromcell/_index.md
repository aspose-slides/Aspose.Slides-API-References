---
title: get_ShowLabelValueFromCell()
second_title: Aspose.Slides dla C++ Referencja API
description: Reprezentuje określone zachowanie wyświetlania wartości komórki etykiety danych wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt bool.
type: docs
weight: 300
url: /pl/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() metoda

Reprezentuje określone zachowanie wyświetlania wartości komórki etykiety danych wykresu. True wyświetla wartość komórki. False ukrywa. Odczyt **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Uwagi

Jeśli rodzicem tego [DataLabelFormat](../../datalabelformat/) obiektu jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, wówczas ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowLabelValueFromCell dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Ustawienie tej właściwości na określoną wartość powoduje także ustawienie tej samej wartości w właściwości ShowLabelValueFromCell dla wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" powoduje, że wszystkie DataLabels[i].ShowLabelValueFromCell są równe val).

## Zobacz także

* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)