---
title: InsertTable()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową tabelę i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 443
url: /pl/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metoda

Tworzy nową tabelę i wstawia ją do kolekcji kształtów w określonym indeksie.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym należy wstawić tabelę. |
| x | **float** | Współrzędna x tabeli, w punktach. |
| y | **float** | Współrzędna y tabeli, w punktach. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb typu double reprezentująca szerokości kolumn tabeli, w punktach. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb typu double reprezentująca wysokości wierszy tabeli, w punktach. |

### Wartość zwracana

Nowo utworzony [ITable](../../itable/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ITable](../../itable/)
* Klasa [IShapeCollection](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)