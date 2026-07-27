---
title: get_Row()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el índice basado en cero de la fila en la hoja de cálculo donde se encuentra la celda. Solo lectura int32_t.
type: docs
weight: 27
url: /es/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() método


Obtiene el índice basado en cero de la fila en la hoja de cálculo donde se encuentra la celda. Solo lectura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Ver también

* Clase [IExcelDataCell](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)