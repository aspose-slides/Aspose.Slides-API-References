---
title: GetCells()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Pobiera kolekcję komórek ze skoroszytu, które pasują do określonej formuły.
type: docs
weight: 1
url: /pl/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) method


Pobiera kolekcję komórek ze skoroszytu, które pasują do określonej formuły.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Formuła lub wyrażenie zakresu (np. \"Sheet1!A1:B3\") użyte do zidentyfikowania docelowych komórek. |
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
* Class [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)