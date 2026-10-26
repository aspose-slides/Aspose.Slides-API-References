---
title: GetChartsFromWorksheet()
second_title: Referencia de API de Aspose.Slides para C++
description: Recupera un diccionario que contiene los índices y nombres de todos los gráficos en la hoja de cálculo especificada de un libro de trabajo de Excel.
type: docs
weight: 27
url: /es/aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet/
---
## IExcelDataWorkbook::GetChartsFromWorksheet(System::String) method

Recupera un diccionario que contiene los índices y nombres de todos los gráficos en la hoja de cálculo especificada de un libro de trabajo [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<int32_t, System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetChartsFromWorksheet(System::String worksheetName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | El nombre de la hoja de cálculo en la que buscar gráficos. |

### Valor devuelto

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
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [IExcelDataWorkbook](../)
* Namespace [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)