---
title: DataLabel
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/datalabel/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Representa rótulos de série.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Cria uma nova instância da classe DataLabel. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são false). |
| [hide()](#hide--) | Torna o rótulo de dados oculto definindo todas as flags Show*- (ShowValue, ...) como false. |
| [getActualLabelText()](#getActualLabelText--) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding com o texto no parâmetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Pode conter um texto formatado rich. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato do texto. |
| [getX()](#getX--) | Retorna ou define a coordenada x de um título como fração da largura do gráfico. |
| [setX(float value)](#setX-float-) | Retorna ou define a coordenada x de um título como fração da largura do gráfico. |
| [getY()](#getY--) | Retorna ou define a coordenada y de um título como fração da altura do gráfico. |
| [setY(float value)](#setY-float-) | Retorna ou define a coordenada y de um título como fração da altura do gráfico. |
| [getWidth()](#getWidth--) | Retorna ou define a largura de um título como fração da largura do gráfico. |
| [setWidth(float value)](#setWidth-float-) | Retorna ou define a largura de um título como fração da largura do gráfico. |
| [getHeight()](#getHeight--) | Retorna ou define a altura de um título como fração da altura do gráfico. |
| [setHeight(float value)](#setHeight-float-) | Retorna ou define a altura de um título como fração da altura do gráfico. |
| [getRight()](#getRight--) | Direita. |
| [getBottom()](#getBottom--) | Inferior. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retorna o formato do rótulo de dados. |
| [getValueFromCell()](#getValueFromCell--) | Obtém ou define a célula de dados da pasta de trabalho. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtém ou define a célula de dados da pasta de trabalho. |
| [getActualX()](#getActualX--) | Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento do gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento do gráfico. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Cria uma nova instância da classe DataLabel.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint pai. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False significa que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são false). Somente leitura boolean.

--------------------

Se o rótulo de dados estiver visível, você pode ocultá-lo com o método Hide(). Mas se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as flags Show*- (ShowValue, ...) como true.

**Retorna:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Torna o rótulo de dados oculto definindo todas as flags Show*- (ShowValue, ...) como false. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível (IsVisible é false) você pode torná-lo visível definindo as flags Show*- (ShowValue, ...) como true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text.

**Retorna:**
java.lang.String - O objeto java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializa TextFrameForOverriding com o texto no parâmetro "text". Se TextFrameForOverriding já estiver inicializado, simplesmente altera seu texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto para um novo TextFrameForOverriding. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Pode conter um texto formatado rich. Se esta propriedade não for nula, então este valor de texto formatado substitui o texto gerado automaticamente do rótulo de dados. O texto gerado automaticamente do rótulo de dados significa o texto gerenciado pelas propriedades ShowSeriesName, ShowValue, ... e formatado com a propriedade TextFormatManager.TextFormat. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retorna o formato do texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

Retorna ou define a coordenada x de um título como fração da largura do gráfico. Leitura/gravação float.

**Retorna:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Retorna ou define a coordenada x de um título como fração da largura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Retorna ou define a coordenada y de um título como fração da altura do gráfico. Leitura/gravação float.

**Retorna:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Retorna ou define a coordenada y de um título como fração da altura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retorna ou define a largura de um título como fração da largura do gráfico. Leitura/gravação float.

**Retorna:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Retorna ou define a largura de um título como fração da largura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retorna ou define a altura de um título como fração da altura do gráfico. Leitura/gravação float.

**Retorna:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Retorna ou define a altura de um título como fração da altura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Direita. Somente leitura float.

**Retorna:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Inferior. Somente leitura float.

**Retorna:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Retorna o formato do rótulo de dados. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorna:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um FillFormat. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um FillFormat. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)