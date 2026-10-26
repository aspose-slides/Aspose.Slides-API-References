---
title: IChartPlotArea
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades do título do gráfico.
type: docs
url: /pt/com.aspose.slides/ichartplotarea/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartPlotArea extends ILayoutable, IActualLayout
```

Representa as propriedades do título do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFormat()](#getFormat--) | Retorna o formato de uma área de plotagem. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (excluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (excluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retorna o formato de uma área de plotagem. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### getLayoutTargetType() {#getLayoutTargetType--}
```
public abstract int getLayoutTargetType()
```


Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (excluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). Leitura/Gravação [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Retorna:**
int
### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public abstract void setLayoutTargetType(int value)
```


Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (excluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). Leitura/Gravação [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |