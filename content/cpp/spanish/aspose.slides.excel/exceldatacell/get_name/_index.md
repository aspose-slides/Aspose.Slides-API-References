---
title: get_Name()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el nombre de la celda de datos del gráfico.
type: docs
weight: 14
url: /es/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() método


Obtiene el nombre de la celda de datos del gráfico.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Observaciones


Ejemplo:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Ver también

* Clase [String](../../../system/string/)
* Clase [ExcelDataCell](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)