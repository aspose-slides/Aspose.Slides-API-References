---
title: get_Column()
second_title: Aspose.Slides C++ API Referencia
description: Visszaadja a cella helyét meghatározó munkalapon az oszlop nullaalapú indexét. Csak olvasható int32_t.
type: docs
weight: 40
url: /hu/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metódus


Visszaadja a cella helyét meghatározó munkalapon az oszlop nullaalapú indexét. Csak olvasható **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Lásd még

* Osztály [ExcelDataCell](../)
* Névtér [Aspose::Slides::Excel](../../)
* Könyvtár [Aspose.Slides](../../../)