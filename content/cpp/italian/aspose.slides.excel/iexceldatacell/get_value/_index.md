---
title: get_Value()
second_title: Riferimento API di Aspose.Slides per C++
description: "Ottiene il valore contenuto nella cella Excel. Solo lettura System::Object."
type: docs
weight: 1
url: /it/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() metodo


Ottiene il valore contenuto nella cella [Excel](../../). Solo lettura [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
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
* Classe [IExcelDataCell](../)
* Spazio dei nomi [Aspose::Slides::Excel](../../)
* Libreria [Aspose.Slides](../../../)