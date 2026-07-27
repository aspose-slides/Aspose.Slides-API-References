---
title: GetCells()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada.
type: docs
weight: 1
url: /es/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) método


Recupera una colección de celdas del libro de trabajo que coinciden con la fórmula especificada.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Una fórmula o expresión de rango (p. ej., "Sheet1!A1:B3") utilizada para identificar las celdas objetivo. |
| skipHiddenCells | **bool** | Si **true**, las celdas ocultas (p. ej., en filas u columnas ocultas) se excluirán del resultado. |

### Valor devuelto

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
* Clase [IExcelDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Biblioteca [Aspose.Slides](../../../)