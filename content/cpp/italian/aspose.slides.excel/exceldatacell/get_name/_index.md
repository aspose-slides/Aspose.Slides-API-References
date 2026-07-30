---
title: get_Name()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il nome della cella dati del grafico.
type: docs
weight: 14
url: /it/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metodo


Restituisce il nome della cella dati del grafico.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)