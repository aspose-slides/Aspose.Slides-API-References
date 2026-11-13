---
title: DataLabel
second_title: Referência da API Aspose.Slides para Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Representa rótulos de série.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Creates a new instance of DataLabel class. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [isVisible()](#isVisible--) | Falso significa que o rótulo de dados não está visível (e, portanto, todas as bandeiras Show\*-flags (ShowValue, ...) são falsas). |
| [hide()](#hide--) | Oculta o rótulo de dados definindo todas as bandeiras Show\*-flags (ShowValue, ...) para o estado falso. |
| [getActualLabelText()](#getActualLabelText--) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor de TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding com o texto no parâmetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Pode conter um texto formatado rico. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato de texto. |
| [getX()](#getX--) | Retorna ou define a coordenada x de um título como uma fração da largura do gráfico. |
| [setX(float value)](#setX-float-) | Retorna ou define a coordenada x de um título como uma fração da largura do gráfico. |
| [getY()](#getY--) | Retorna ou define a coordenada y de um título como uma fração da altura do gráfico. |
| [setY(float value)](#setY-float-) | Retorna ou define a coordenada y de um título como uma fração da altura do gráfico. |
| [getWidth()](#getWidth--) | Retorna ou define a largura de um título como uma fração da largura do gráfico. |
| [setWidth(float value)](#setWidth-float-) | Retorna ou define a largura de um título como uma fração da largura do gráfico. |
| [getHeight()](#getHeight--) | Retorna ou define a altura de um título como uma fração da altura do gráfico. |
| [setHeight(float value)](#setHeight-float-) | Retorna ou define a altura de um título como uma fração da altura do gráfico. |
| [getRight()](#getRight--) | Direita. |
| [getBottom()](#getBottom--) | Inferior. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retorna o formato do rótulo de dados. |
| [getValueFromCell()](#getValueFromCell--) | Obtém ou define a célula de dados da pasta de trabalho. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtém ou define a célula de dados da pasta de trabalho. |
| [getLabelShapeType()](#getLabelShapeType--) | Obtém ou define o tipo de forma do rótulo de dados. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Obtém ou define o tipo de forma do rótulo de dados. |
| [getActualX()](#getActualX--) | Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento do gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento do gráfico. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Cria uma nova instância da classe DataLabel.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint pai. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Returns:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Falso significa que o rótulo de dados não está visível (e, portanto, todas as bandeiras Show*-flags (ShowValue, ...) são falsas). Somente leitura  boolean .

--------------------

Se o rótulo de dados estiver visível, você pode ocultá-lo com o método Hide(). Mas se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as bandeiras Show*-flags (ShowValue, ...) para o estado verdadeiro.

**Returns:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Oculta o rótulo de dados definindo todas as bandeiras Show*-flags (ShowValue, ...) para o estado falso. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as bandeiras Show*-flags (ShowValue, ...) para o estado verdadeiro.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor de TextFrameForOverriding.Text.

**Returns:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializa TextFrameForOverriding com o texto no parâmetro "text". Se TextFrameForOverriding já estiver inicializado, simplesmente altera seu texto.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto para um novo TextFrameForOverriding. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Pode conter um texto formatado rico. Se esta propriedade não for nula, então este valor de texto formatado substitui o texto gerado automaticamente do rótulo de dados. Texto gerado automaticamente do rótulo de dados significa texto que é gerenciado pelas propriedades ShowSeriesName, ShowValue, ... e é formatado com a propriedade TextFormatManager.TextFormat. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retorna o formato de texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Returns:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Retorna ou define a coordenada x de um título como uma fração da largura do gráfico. Leitura/gravação  float .

**Returns:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Retorna ou define a coordenada x de um título como uma fração da largura do gráfico. Leitura/gravação  float .

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Retorna ou define a coordenada y de um título como uma fração da altura do gráfico. Leitura/gravação  float .

**Returns:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Retorna ou define a coordenada y de um título como uma fração da altura do gráfico. Leitura/gravação  float .

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retorna ou define a largura de um título como uma fração da largura do gráfico. Leitura/gravação  float .

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Retorna ou define a largura de um título como uma fração da largura do gráfico. Leitura/gravação  float .

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retorna ou define a altura de um título como uma fração da altura do gráfico. Leitura/gravação  float .

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Retorna ou define a altura de um título como uma fração da altura do gráfico. Leitura/gravação  float .

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Direita. Somente leitura  float .

**Returns:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Inferior. Somente leitura  float .

**Returns:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Retorna o formato do rótulo de dados. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Obtém ou define o tipo de forma do rótulo de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma estiver definida.

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Define o tipo de forma do primeiro rótulo de dados como Elipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Obtém ou define o tipo de forma do rótulo de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma estiver definida.

--------------------

> ``` 
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Define o tipo de forma do primeiro rótulo de dados como Elipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura float.

**Returns:**
float
### getActualY() {#getActualY--}
``` 
public final float getActualY()
```

Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter os valores reais. Leitura float.

**Returns:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um FillFormat. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um FillFormat. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)