---
title: GetChartsFromWorksheet()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera un diccionario que contiene los índices y los nombres de todos los gráficos en la hoja de cálculo especificada de un libro de trabajo de Excel.
type: docs
weight: 40
url: /es/aspose.slides.excel/exceldataworkbook/getchartsfromworksheet/
---
## ExcelDataWorkbook::GetChartsFromWorksheet(System::String) método

Recupera un diccionario que contiene los índices y los nombres de todos los gráficos en la hoja de cálculo especificada de un libro de trabajo [Excel](../../).

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::ExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo en la que buscar los gráficos. |

### Valor de retorno

Un diccionario donde la clave es el índice del gráfico y el valor es el nombre del gráfico.

## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetCharts = wb->GetChartsFromWorksheet(u"worksheetName");
for (auto&& chart : sheetCharts)
{
    System::Console::WriteLine(System::Convert::ToString(chart.get_Key()) + u" : " + chart.get_Value());
}
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IDictionary](../../../system.collections.generic/idictionary/)
* Clase [String](../../../system/string/)
* Clase [ExcelDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)