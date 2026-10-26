---
title: GetCells()
second_title: Aspose.Slides para C++ Referencia de API
description: Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada.
type: docs
weight: 14
url: /es/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) método

Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Una fórmula o expresión de rango (p. ej., "Sheet1!A1:B3") utilizada para identificar las celdas objetivo. |
| skipHiddenCells | **bool** | Si **true**, las celdas ocultas (p. ej., en filas o columnas ocultas) serán excluidas del resultado. |

### Valor de retorno

Una lista de solo lectura de celdas que coinciden con la fórmula especificada.
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Clase [IExcelDataCell](../../iexceldatacell/)
* Clase [String](../../../system/string/)
* Clase [ExcelDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)