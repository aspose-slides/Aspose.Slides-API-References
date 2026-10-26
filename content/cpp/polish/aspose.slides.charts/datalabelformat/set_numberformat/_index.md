---
title: set_NumberFormat()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Reprezentuje ciąg formatu dla obiektu DataLabels. Zapisz System::String."
type: docs
weight: 40
url: /pl/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metoda


Reprezentuje ciąg formatu dla obiektu DataLabels. Zapisz [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Uwagi



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Jeśli rodzicem tego obiektu [DataLabelFormat](../) jest kolekcja [DataLabelCollection](../../datalabelcollection/) etykiet danych, to ta własność pobiera lub ustawia domyślną wartość właściwości NumberFormat dla nowych etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/). Gdy ta własność jest ustawiona na wartość, ta wartość jest również ustawiana dla właściwości NumberFormat dla wszystkich etykiet danych w kolekcji [DataLabelCollection](../../datalabelcollection/) (tj. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" powoduje, że wszystkie DataLabels[i].NumberFormat są równe val). 



## Zobacz też

* Klasa [String](../../../system/string/)
* Klasa [DataLabelFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)