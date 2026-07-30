---
title: GetCells()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera una raccolta di celle dal workbook che corrispondono alla formula specificata.
type: docs
weight: 1
url: /it/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) metodo


Recupera una raccolta di celle dal workbook che corrispondono alla formula specificata.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Una formula o espressione di intervallo (ad es., \"Sheet1!A1:B3\") usata per identificare le celle di destinazione. |
| skipHiddenCells | **bool** | Se **true**, le celle nascoste (ad es., in righe o colonne nascoste) saranno escluse dal risultato. |

### Valore di ritorno

Una lista di sola lettura di celle che corrispondono alla formula specificata.
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Classe [IExcelDataCell](../../iexceldatacell/)
* Classe [String](../../../system/string/)
* Classe [IExcelDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)