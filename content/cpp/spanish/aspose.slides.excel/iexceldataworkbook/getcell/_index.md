---
title: GetCell()
second_title: Aspose.Slides para C++ Referencia de API
description: Recupera una celda de la hoja de cálculo especificada mediante su índice y las coordenadas de la celda.
type: docs
weight: 14
url: /es/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) método

Recupera una celda de la hoja de cálculo especificada mediante su índice y las coordenadas de la celda.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Índice basado en cero de la hoja de cálculo. |
| row | **int32_t** | Índice basado en cero de la fila de la celda. |
| column | **int32_t** | Índice basado en cero de la columna de la celda. |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) método

Recupera una celda de la hoja de cálculo especificada mediante su nombre y las coordenadas de la celda.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo. |
| row | **int32_t** | Índice basado en cero de la fila de la celda. |
| column | **int32_t** | Índice basado en cero de la columna de la celda. |

### Valor devuelto

La celda en la ubicación especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## IExcelDataWorkbook::GetCell(int32_t, System::String) método

Recupera una celda de la hoja de cálculo especificada mediante su índice y el nombre de celda al estilo Excel (p. ej., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
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

## IExcelDataWorkbook::GetCell(System::String, System::String) método

Recupera una celda de la hoja de cálculo especificada mediante el nombre de celda al estilo Excel (p. ej., "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
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

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IExcelDataCell](../../iexceldatacell/)
* Class [IExcelDataWorkbook](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)