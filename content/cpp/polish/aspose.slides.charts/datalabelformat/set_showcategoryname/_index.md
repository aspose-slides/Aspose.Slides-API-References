---
title: set_ShowCategoryName()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych określonego wykresu. True wyświetla nazwę kategorii na etykietach danych wykresu. False ukrywa ją. Zapisz bool.
type: docs
weight: 157
url: /pl/aspose.slides.charts/datalabelformat/set_showcategoryname/
---
## DataLabelFormat::set_ShowCategoryName(bool) metoda

Represents a specified chart's data label category name display behavior. True to display the category name for the data labels on a chart. False to hide. Write **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowCategoryName(bool value) override
```

## Uwagi

Jeśli rodzicem tego obiektu [DataLabelFormat](../) jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, to ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Ustawienie tej właściwości na określoną wartość powoduje również ustawienie tej wartości w właściwości ShowCategoryName dla wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (np. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" powoduje, że wszystkie DataLabels[i].ShowCategoryName są równe val).

## Zobacz także

* Klasa [DataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)