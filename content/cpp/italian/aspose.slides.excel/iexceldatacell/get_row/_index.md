---
title: get_Row()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Sola lettura int32_t.
type: docs
weight: 27
url: /it/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() metodo

Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Solo lettura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Osservazioni

Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Vedi anche

* Classe [IExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)