---
title: get_Value()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el valor contenido en la celda de Excel. Solo lectura System::Object."
type: docs
weight: 1
url: /es/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() método


Obtiene el valor contenido en la celda [Excel](../../). Solo lectura [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [IExcelDataCell](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)