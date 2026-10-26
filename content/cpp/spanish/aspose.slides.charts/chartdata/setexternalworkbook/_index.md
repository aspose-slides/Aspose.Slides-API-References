---
title: SetExternalWorkbook()
second_title: Aspose.Slides para C++ Referencia de API
description: Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino.
type: docs
weight: 183
url: /es/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) método

Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos [Chart](../../chart/) se actualizarán desde el libro de trabajo de destino.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Ruta al libro de trabajo de destino |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) método

Establece el libro de trabajo externo como fuente de datos para el gráfico.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Ruta al libro de trabajo de destino |
| updateChartData | **bool** | Si el valor es false, solo se actualizará la ruta del libro de trabajo. Los datos [Chart](../../chart/) no se cargarán ni se actualizarán desde el libro de trabajo de destino. Puede usarse cuando el libro de trabajo de destino no exista o no esté disponible. Si el valor es true, los datos del gráfico se actualizarán desde el libro de trabajo de destino. |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)