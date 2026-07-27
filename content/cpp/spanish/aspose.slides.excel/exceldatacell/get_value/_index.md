---
title: get_Value()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el valor contenido en la celda de Excel.
type: docs
weight: 1
url: /es/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() método


Obtiene el valor contenido en la celda [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [ExcelDataCell](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)