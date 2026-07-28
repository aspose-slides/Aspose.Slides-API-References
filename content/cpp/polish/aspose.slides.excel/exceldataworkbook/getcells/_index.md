---
title: GetCells()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Pobiera kolekcję komórek z skoroszytu, które pasują do określonej formuły.
type: docs
weight: 14
url: /pl/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) metoda


Pobiera kolekcję komórek z skoroszytu, które pasują do określonej formuły.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Formuła lub wyrażenie zakresu (np. \"Sheet1!A1:B3\") używane do zidentyfikowania docelowych komórek. |
| skipHiddenCells | **bool** | Jeśli **true**, ukryte komórki (np. w ukrytych wierszach lub kolumnach) zostaną wykluczone z wyniku. |

### Wartość zwracana

Lista komórek tylko do odczytu, które pasują do określonej formuły.
## Uwagi



Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Klasa [IExcelDataCell](../../iexceldatacell/)
* Klasa [String](../../../system/string/)
* Klasa [ExcelDataWorkbook](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)