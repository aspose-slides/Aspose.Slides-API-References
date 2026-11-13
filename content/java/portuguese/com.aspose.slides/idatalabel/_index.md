---
title: IDataLabel
second_title: Referência da API Aspose.Slides para Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representa rótulos de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível (e, portanto, todas as Show*-flags (ShowValue, ...) são false). |
| [hide()](#hide--) | Torna o rótulo de dados oculto definindo todas as Show*-flags (ShowValue, ...) para o estado false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retorna o formato do rótulo de dados. |
| [getValueFromCell()](#getValueFromCell--) | Obtém ou define a célula de dados da planilha. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtém ou define a célula de dados da planilha. |
| [getActualLabelText()](#getActualLabelText--) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtém ou define o tipo de forma do rótulo de dados. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtém ou define o tipo de forma do rótulo de dados. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que o rótulo de dados não está visível (e, portanto, todas as Show*-flags (ShowValue, ...) são false). Somente leitura boolean.

--------------------

Se o rótulo de dados estiver visível, você pode ocultá-lo com o método Hide(). Mas se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as Show*-flags (ShowValue, ...) para o estado true.

**Retorna:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Torna o rótulo de dados oculto definindo todas as Show*-flags (ShowValue, ...) para o estado false. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as Show*-flags (ShowValue, ...) para o estado true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Retorna o formato do rótulo de dados. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorna:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtém ou define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtém ou define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text.

**Retorna:**
java.lang.String - Texto real do rótulo
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Obtém ou define o tipo de forma do rótulo de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma for definida.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Defina o tipo de forma do primeiro rótulo de dados como Elipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Obtém ou define o tipo de forma do rótulo de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma for definida.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Defina o tipo de forma do primeiro rótulo de dados como Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |