---
title: AddChart
second_title: Aspose.Sildes para .NET Referencia de API
description: Crea un nuevo gráfico, lo inicializa con datos de serie de ejemplo y configuraciones, y lo añade al final de la colección.
type: docs
weight: 100
url: /es/aspose.slides/shapecollection/addchart/
---

## AddChart(ChartType, float, float, float, float) {#addchart}

Crea un nuevo gráfico, lo inicializa con datos de serie de ejemplo y configuraciones, y lo añade al final de la colección.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | ChartType | Tipo de gráfico. |
| x | Single | Coordenada X de un nuevo gráfico. |
| y | Single | Coordenada Y de un nuevo gráfico. |
| width | Single | Ancho del gráfico. |
| height | Single | Altura del gráfico. |

### Valor de Retorno

Gráfico creado.

### Ejemplos

El siguiente ejemplo muestra cómo crear un gráfico en una presentación de PowerPoint.

```csharp
[C#]
// Instancia la clase Presentation que representa un archivo PPTX
using(Presentation pres = new Presentation()) {
  // Accede a la primera diapositiva
  ISlide sld = pres.Slides[0];
  // Añade un gráfico con sus datos predeterminados
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Establece el título del gráfico
  chart.ChartTitle.AddTextFrameForOverriding("Título de Ejemplo");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Establece la primera serie para mostrar valores
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Establece el índice para la hoja de datos del gráfico
  int defaultWorksheetIndex = 0;
  // Obtiene la hoja de datos del gráfico
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Elimina las series y categorías generadas por defecto
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Añade nuevas series
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Serie 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Serie 2"), chart.Type);
  // Añade nuevas categorías
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Categoría 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Categoría 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Categoría 3"));
  // Toma la primera serie del gráfico
  IChartSeries series = chart.ChartData.Series[0];
  // Población de los datos de la serie
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Establece el color de relleno para la serie
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Toma la segunda serie del gráfico
  series = chart.ChartData.Series[1];
  // Población de los datos de la serie
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Establece el color de relleno para la serie
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Establece la primera etiqueta para mostrar el nombre de la Categoría
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Establece la serie para mostrar el valor de la tercera etiqueta
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Guarda el archivo PPTX en el disco
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Crea un nuevo gráfico y lo añade al final de la colección.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | ChartType | Tipo de gráfico. |
| x | Single | Coordenada X de un nuevo gráfico. |
| y | Single | Coordenada Y de un nuevo gráfico. |
| width | Single | Ancho del gráfico. |
| height | Single | Altura del gráfico. |
| initWithSample | Boolean | Si es verdadero, el nuevo gráfico se inicializará con datos de serie de ejemplo y configuraciones. Si es falso, el nuevo gráfico no tendrá series y tendrá configuraciones mínimas. En este caso, la creación del gráfico será más rápida. |

### Valor de Retorno

Gráfico creado.

### Ver También

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->