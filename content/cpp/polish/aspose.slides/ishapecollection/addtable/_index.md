---
title: AddTable()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 430
url: /pl/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Creates a new table and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna x tabeli, w punktach. |
| y | **float** | Współrzędna y tabeli, w punktach. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych określająca szerokości kolumn tabeli, w punktach. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych określająca wysokości wierszy tabeli, w punktach. |

### Wartość zwracana

Nowo utworzony [ITable](../../itable/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ITable](../../itable/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)