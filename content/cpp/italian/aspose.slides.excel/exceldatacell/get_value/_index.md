---
title: get_Value()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore contenuto nella cella Excel.
type: docs
weight: 1
url: /it/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() metodo

Ottiene il valore contenuto nella cella [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Osservazioni


Esempio: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ExcelDataCell](../)
* Namespace [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)