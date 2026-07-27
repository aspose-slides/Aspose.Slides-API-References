---
title: get_Name()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el nombre de la celda de datos del gráfico. Solo lectura System::String."
type: docs
weight: 14
url: /es/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() método


Obtiene el nombre de la celda de datos del gráfico. Solo lectura [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
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
* Clase [IExcelDataCell](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)