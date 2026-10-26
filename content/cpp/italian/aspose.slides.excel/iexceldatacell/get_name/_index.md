---
title: get_Name()
second_title: Riferimento API Aspose.Slides per C++
description: "Ottiene il nome della cella dei dati del grafico. Solo lettura System::String."
type: docs
weight: 14
url: /it/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metodo


Ottiene il nome della cella dei dati del grafico. Solo lettura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Classe [IExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)