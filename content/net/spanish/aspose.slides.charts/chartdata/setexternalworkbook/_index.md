---
title: SetExternalWorkbook
second_title: Referencia de API de Aspose.Slides para .NET
description: Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino.
type: docs
weight: 110
url: /es/aspose.slides.charts/chartdata/setexternalworkbook/
---

## SetExternalWorkbook(string) {#setexternalworkbook}

Establece el libro de trabajo externo como fuente de datos para el gráfico. Los datos del gráfico se actualizarán desde el libro de trabajo de destino.

```csharp
public void SetExternalWorkbook(string workbookPath)
```

| Parámetro     | Tipo    | Descripción                         |
| -------------- | ------- | ----------------------------------- |
| workbookPath   | String  | Ruta al libro de trabajo de destino |

### Excepciones

| excepción                  | condición                                          |
| -------------------------- | -------------------------------------------------- |
| InvalidOperationException   | El libro de trabajo externo no está disponible o no se puede cargar. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())

   IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 50, 50, 400, 600, true);
   IChartData chartData = chart.ChartData;
   (chartData as ChartData).SetExternalWorkbook("../../workbook.xlsx");

```

### Ver También

* clase [ChartData](../../chartdata)
* namespace [Aspose.Slides.Charts](../../chartdata)
* assembly [Aspose.Slides](../../../)

---

## SetExternalWorkbook(string, bool) {#setexternalworkbook_1}

Establece el libro de trabajo externo como fuente de datos para el gráfico.

```csharp
public void SetExternalWorkbook(string workbookPath, bool updateChartData)
```

| Parámetro     | Tipo    | Descripción                                                                                                                                  |
| -------------- | ------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| workbookPath   | String  | Ruta al libro de trabajo de destino                                                                                                          |
| updateChartData| Boolean | Si el valor es falso, solo se actualizará la ruta del libro de trabajo. Los datos del gráfico no se cargarán ni se actualizarán desde el libro de trabajo de destino. Se puede utilizar cuando el libro de trabajo de destino no existe o no está disponible. Si el valor es verdadero, los datos del gráfico se actualizarán desde el libro de trabajo de destino. |

### Excepciones

| excepción                  | condición                                          |
| -------------------------- | -------------------------------------------------- |
| InvalidOperationException   | El libro de trabajo externo no está disponible o no se puede cargar. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())

   IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 50, 50, 400, 600, true);
   IChartData chartData = chart.ChartData;

   (chartData as ChartData).SetExternalWorkbook("http://path/doesnt/exists", false);

```

### Ver También

* clase [ChartData](../../chartdata)
* namespace [Aspose.Slides.Charts](../../chartdata)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->