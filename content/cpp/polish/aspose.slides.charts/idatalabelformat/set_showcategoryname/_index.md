---
title: set_ShowCategoryName()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych w określonym wykresie. true, aby wyświetlić nazwę kategorii dla etykiet danych na wykresie. false, aby ukryć. Zapisz bool.
type: docs
weight: 157
url: /pl/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) metoda

Reprezentuje zachowanie wyświetlania nazwy kategorii etykiety danych w określonym wykresie. true, aby wyświetlić nazwę kategorii dla etykiet danych na wykresie. false, aby ukryć. Zapisz **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Uwagi

Jeśli rodzic tego obiektu [DataLabelFormat](../../datalabelformat/) jest [DataLabelCollection](../../datalabelcollection/) kolekcją etykiet danych, wtedy ta właściwość pobiera lub ustawia domyślną wartość właściwości ShowCategoryName dla nowych etykiet danych w [DataLabelCollection](../../datalabelcollection/) kolekcji. Ustawienie tej właściwości na określoną wartość ustawia również tę wartość w właściwości ShowCategoryName dla wszystkich etykiet danych w [DataLabelCollection](../../datalabelcollection/) kolekcji (np. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" powoduje, że wszystkie DataLabels[i].ShowCategoryName są równe val).

## Zobacz także

* Klasa [IDataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)