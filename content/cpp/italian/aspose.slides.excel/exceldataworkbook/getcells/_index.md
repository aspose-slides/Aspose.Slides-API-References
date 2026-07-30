---
title: GetCells()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera una raccolta di celle dalla cartella di lavoro che corrispondono alla formula specificata.
type: docs
weight: 14
url: /it/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) metodo

Recupera una raccolta di celle dalla cartella di lavoro che corrispondono alla formula specificata.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Una formula o un'espressione di intervallo (ad es., "Sheet1!A1:B3") usata per identificare le celle di destinazione. |
| skipHiddenCells | **bool** | Se **true**, le celle nascoste (ad es., in righe o colonne nascoste) verranno escluse dal risultato. |

### Valore restituito

Un elenco di sola lettura di celle che corrispondono alla formula specificata.
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
* Classe [ExcelDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)