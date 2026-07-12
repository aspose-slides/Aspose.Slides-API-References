---
title: Legend
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades da legenda dos gráficos.
type: docs
url: /pt/com.aspose.slides/legend/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

Representa as propriedades da legenda do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getX()](#getX--) | Retorna ou define a coordenada x de uma legenda como uma fração da largura do gráfico. |
| [setX(float value)](#setX-float-) | Retorna ou define a coordenada x de uma legenda como uma fração da largura do gráfico. |
| [getY()](#getY--) | Retorna ou define a coordenada y de uma legenda como uma fração da altura do gráfico. |
| [setY(float value)](#setY-float-) | Retorna ou define a coordenada y de uma legenda como uma fração da altura do gráfico. |
| [getWidth()](#getWidth--) | Retorna ou define a largura de uma legenda como uma fração da largura do gráfico. |
| [setWidth(float value)](#setWidth-float-) | Retorna ou define a largura de uma legenda como uma fração da largura do gráfico. |
| [getHeight()](#getHeight--) | Retorna ou define a altura de uma legenda como uma fração da altura do gráfico. |
| [setHeight(float value)](#setHeight-float-) | Retorna ou define a altura de uma legenda como uma fração da altura do gráfico. |
| [getRight()](#getRight--) | Direita. |
| [getBottom()](#getBottom--) | Inferior. |
| [getOverlay()](#getOverlay--) | Determina se outros elementos do gráfico podem sobrepor a legenda. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se outros elementos do gráfico podem sobrepor a legenda. |
| [getTextFormat()](#getTextFormat--) | Formato de texto. |
| [getPosition()](#getPosition--) | Especifica a posição da legenda em um gráfico. |
| [setPosition(int value)](#setPosition-int-) | Especifica a posição da legenda em um gráfico. |
| [getFormat()](#getFormat--) | Retorna o formato de uma legenda. |
| [getChart()](#getChart--) | Retorna o gráfico. |
| [getEntries()](#getEntries--) | Obtém as entradas da legenda. |
| [getActualX()](#getActualX--) | Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento do gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento do gráfico. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |
### getX() {#getX--}
```
public final float getX()
```

Retorna ou define a coordenada x de uma legenda como uma fração da largura do gráfico. Leitura/gravação float.

**Retorna:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Retorna ou define a coordenada x de uma legenda como uma fração da largura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Retorna ou define a coordenada y de uma legenda como uma fração da altura do gráfico. Leitura/gravação float.

**Retorna:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Retorna ou define a coordenada y de uma legenda como uma fração da altura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Retorna ou define a largura de uma legenda como uma fração da largura do gráfico. Leitura/gravação float.

**Retorna:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Retorna ou define a largura de uma legenda como uma fração da largura do gráfico. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Retorna ou define a altura de uma legenda como uma fração da altura do gráfico. Leitura/gravação float.

**Retorna:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Retorna ou define a altura de uma legenda como uma fração da altura do gráfico. Leitura/gravação float.

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
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

Determina se outros elementos do gráfico podem sobrepor a legenda. Leitura/gravação boolean.

**Retorna:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

Determina se outros elementos do gráfico podem sobrepor a legenda. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Formato de texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Especifica a posição da legenda em um gráfico. Valores não-NaN das propriedades X, Y, Width, Height substituem o efeito desta propriedade. Leitura/gravação [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Retorna:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Especifica a posição da legenda em um gráfico. Valores não-NaN das propriedades X, Y, Width, Height substituem o efeito desta propriedade. Leitura/gravação [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Retorna o formato de uma legenda. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)
### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```

Obtém as entradas da legenda. Somente leitura [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Retorna:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Especifica a localização real x (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.validateChartLayout() antes para obter valores reais. Leitura float.

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