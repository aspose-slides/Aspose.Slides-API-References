---
title: get_Column()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'indice a base zero della colonna nel foglio di lavoro in cui si trova la cella. Sola lettura int32_t.
type: docs
weight: 40
url: /it/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metodo


Restituisce l'indice a base zero della colonna nel foglio di lavoro in cui si trova la cella. Sola lettura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Vedi anche

* Classe [IExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)