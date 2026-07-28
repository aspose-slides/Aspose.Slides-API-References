---
title: get_Row()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a munkalapon, ahol a cella található, a sor nulla alapú indexét. Csak olvasható int32_t.
type: docs
weight: 27
url: /hu/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() metódus


Visszaadja a munkalapon, ahol a cella található, a sor nulla alapú indexét. Csak olvasható **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Lásd még

* Osztály [IExcelDataCell](../)
* Névtere [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)