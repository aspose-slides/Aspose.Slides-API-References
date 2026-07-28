---
title: get_Column()
second_title: Aspose.Slides for C++ API-referencia
description: A cella helyét tartó munkalapon az oszlop nulla-alapú indexét adja vissza. Csak olvasható int32_t.
type: docs
weight: 40
url: /hu/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metódus

A cella helyét tartó munkalapon az oszlop nulla-alapú indexét adja vissza. Csak olvasható **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Megjegyzések

Példa:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Lásd még

* Osztály [IExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)