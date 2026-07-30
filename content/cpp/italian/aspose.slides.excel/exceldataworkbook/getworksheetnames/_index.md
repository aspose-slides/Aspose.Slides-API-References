---
title: GetWorksheetNames()
second_title: Aspose.Slides per C++ Riferimento API
description: Recupera i nomi di tutti i fogli di lavoro contenuti nella cartella di lavoro Excel.
type: docs
weight: 53
url: /it/aspose.slides.excel/exceldataworkbook/getworksheetnames/
---
## ExcelDataWorkbook::GetWorksheetNames() metodo


Recupera i nomi di tutti i fogli di lavoro contenuti nella cartella di lavoro [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetWorksheetNames() override
```


### Valore restituito

Un elenco di nomi di fogli di lavoro
## Osservazioni



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
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [String](../../../system/string/)
* Classe [ExcelDataWorkbook](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)