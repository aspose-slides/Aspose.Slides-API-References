---
title: GetCell()
second_title: Referencia de la API de Aspose.Slides para C++
description: Recupera una celda de la hoja de cálculo especificada utilizando su índice y las coordenadas de la celda.
type: docs
weight: 27
url: /es/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) método


Recupera una celda de la hoja de cálculo especificada utilizando su índice y las coordenadas de la celda.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice basado en cero de la hoja de cálculo. |
| row | **int32_t** | Índice de fila basado en cero de la celda. |
| column | **int32_t** | Índice de columna basado en cero de la celda. |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) método


Recupera una celda de la hoja de cálculo especificada utilizando su nombre y las coordenadas de la celda.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo. |
| row | **int32_t** | Índice de fila basado en cero de la celda. |
| column | **int32_t** | Índice de columna basado en cero de la celda. |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) método


Recupera una celda de la hoja de cálculo especificada utilizando su índice y el nombre de celda al estilo Excel (p. ej., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice basado en cero de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | La referencia de celda al estilo Excel (p. ej., "A1", "C5"). |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) método


Recupera una celda de la hoja de cálculo especificada utilizando el nombre de celda al estilo Excel (p. ej., "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo. |
| cellName | [System::String](../../../system/string/) | La referencia de celda al estilo Excel (p. ej., "A1", "C5"). |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IExcelDataCell](../../iexceldatacell/)
* Clase [ExcelDataWorkbook](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)