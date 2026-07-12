---
title: IChartPlotArea
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa las propiedades del título del gráfico.
type: docs
url: /es/com.aspose.slides/ichartplotarea/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Representa las propiedades del título del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat()](#getFormat--) | Devuelve el formato de un área de trazado. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Si la disposición del área de trazado se define manualmente, esta propiedad especifica si la disposición del área de trazado se realiza por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Si la disposición del área de trazado se define manualmente, esta propiedad especifica si la disposición del área de trazado se realiza por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Devuelve el formato de un área de trazado. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```

Si la disposición del área de trazado se define manualmente, esta propiedad especifica si la disposición del área de trazado se realiza por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). Lectura/escritura [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Devuelve:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```

Si la disposición del área de trazado se define manualmente, esta propiedad especifica si la disposición del área de trazado se realiza por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). Lectura/escritura [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |