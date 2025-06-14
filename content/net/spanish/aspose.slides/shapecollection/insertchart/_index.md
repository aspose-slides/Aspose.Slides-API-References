---
title: InsertChart
second_title: Referencia de la API de Aspose.Slides para .NET
description: Crea un nuevo gráfico, lo inicializa con datos de series de muestra y configuraciones e inserta en la posición especificada en la colección.
type: docs
weight: 310
url: /es/aspose.slides/shapecollection/insertchart/
---

## InsertChart(ChartType, float, float, float, float, int) {#insertchart}

Crea un nuevo gráfico, lo inicializa con datos de series de muestra y configuraciones e inserta en la posición especificada en la colección.

```csharp
public IChart InsertChart(ChartType type, float x, float y, float width, float height, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | ChartType | Tipo de gráfico. |
| x | Single | Coordenada X de un nuevo gráfico. |
| y | Single | Coordenada Y de un nuevo gráfico. |
| width | Single | Ancho del gráfico. |
| height | Single | Alto del gráfico. |
| index | Int32 | Posición del gráfico en la colección. |

### Valor de Retorno

Gráfico creado.

### Véase También

* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblaje [Aspose.Slides](../../../)

---

## InsertChart(ChartType, float, float, float, float, int, bool) {#insertchart_1}

Crea un nuevo gráfico e inserta en la posición especificada en la colección.

```csharp
public IChart InsertChart(ChartType type, float x, float y, float width, float height, int index, 
    bool initWithSample)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | ChartType | Tipo de gráfico. |
| x | Single | Coordenada X de un nuevo gráfico. |
| y | Single | Coordenada Y de un nuevo gráfico. |
| width | Single | Ancho del gráfico. |
| height | Single | Alto del gráfico. |
| index | Int32 | Posición del gráfico en la colección. |
| initWithSample | Boolean | Si es verdadero, el nuevo gráfico se inicializará con datos de series de muestra y configuraciones. Si es falso, el nuevo gráfico no tendrá series y la configuración será mínima. En este caso, la creación del gráfico será más rápida. |

### Valor de Retorno

Gráfico creado.

### Véase También

* interfaz [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* clase [ShapeCollection](../../shapecollection)
* espacio de nombres [Aspose.Slides](../../shapecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->