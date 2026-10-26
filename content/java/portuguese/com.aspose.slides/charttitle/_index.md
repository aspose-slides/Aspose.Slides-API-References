---
title: ChartTitle
second_title: Referência da API Aspose.Slides para Java
description: Representa as propriedades do título do gráfico.
type: docs
url: /pt/com.aspose.slides/charttitle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartTitle](../../com.aspose.slides/icharttitle), com.aspose.slides.IDOMObject
```
public class ChartTitle implements IChartTitle, IDOMObject
```

Represents chart title properties.
## Métodos

| Método | Descrição |
| --- | --- |
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
| [getOverlay()](#getOverlay--) | Determina se outros elementos do gráfico podem se sobrepor ao título. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se outros elementos do gráfico podem se sobrepor ao título. |
| [getFormat()](#getFormat--) | Retorna os estilos de preenchimento, linha e efeito de um título. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding com o texto no parâmetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Pode conter um texto formatado rico. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato de texto. |
| [getActualX()](#getActualX--) | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento do gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento do gráfico. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Retorna ou define a coordenada x de um título como fração da largura do gráfico. Leitura/Gravação float.

**Retorna:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Retorna ou define a coordenada x de um título como fração da largura do gráfico. Leitura/Gravação float.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Retorna ou define a coordenada y de um título como fração da altura do gráfico. Leitura/Gravação float.

**Retorna:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Retorna ou define a coordenada y de um título como fração da altura do gráfico. Leitura/Gravação float.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Retorna ou define a largura de um título como fração da largura do gráfico. Leitura/Gravação float.

**Retorna:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Retorna ou define a largura de um título como fração da largura do gráfico. Leitura/Gravação float.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Retorna ou define a altura de um título como fração da altura do gráfico. Leitura/Gravação float.

**Retorna:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Retorna ou define a altura de um título como fração da altura do gráfico. Leitura/Gravação float.

**Parâmetros:**
| Parameter | Type | Description |
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
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```


Determina se outros elementos do gráfico podem se sobrepor ao título. Leitura/Gravação boolean.

**Retorna:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Determina se outros elementos do gráfico podem se sobrepor ao título. Leitura/Gravação boolean.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Retorna os estilos de preenchimento, linha e efeito de um título. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


Inicializa TextFrameForOverriding com o texto no parâmetro "text". Se TextFrameForOverriding já estiver inicializado, altera simplesmente seu texto.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texto para um novo TextFrameForOverriding. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


Pode conter um texto formatado rico. Se esta propriedade não for nula, então este valor de texto formatado substitui o texto gerado automaticamente. O texto gerado automaticamente é uma propriedade implícita do rótulo de dados, do rótulo da unidade de exibição do eixo de valores, do título do eixo, do título do gráfico, do rótulo da linha de tendência. O texto gerado automaticamente é formatado com a propriedade IFormattedTextContainer.TextFormat. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Retorna o formato de texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Especifica a parte superior real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Especifica a largura real do elemento do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Especifica a altura real do elemento do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)
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