---
title: get_Row()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Sola lettura int32_t.
type: docs
weight: 27
url: /it/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metodo

Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Sola lettura **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Osservazioni

Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Vedi anche

* Classe [ExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)