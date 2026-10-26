---
title: GetWorksheetNames()
second_title: Riferimento API Aspose.Slides per C++
description: Recupera i nomi di tutti i fogli di lavoro contenuti nella cartella di lavoro Excel.
type: docs
weight: 40
url: /it/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() metodo

Recupera i nomi di tutti i fogli di lavoro contenuti nella cartella di lavoro [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```

### Valore di ritorno

Un elenco di nomi di fogli di lavoro
## Note

Esempio:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)