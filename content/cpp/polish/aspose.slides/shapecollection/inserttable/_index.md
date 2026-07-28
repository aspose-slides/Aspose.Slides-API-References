---
title: InsertTable()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową tabelę i wstawia ją do kolekcji kształtów w określonym indeksie.
type: docs
weight: 482
url: /pl/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Utworzy nową tabelę i wstawi ją do kolekcji kształtów w określonym indeksie.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym ma zostać wstawiona tabela. |
| x | **float** | Współrzędna x tabeli, w punktach. |
| y | **float** | Współrzędna y tabeli, w punktach. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych podwójnej precyzji określająca szerokości kolumn tabeli, w punktach. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablica liczb zmiennoprzecinkowych podwójnej precyzji określająca wysokości wierszy tabeli, w punktach. |

### Wartość zwracana

Nowo utworzony [ITable](../../itable/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)