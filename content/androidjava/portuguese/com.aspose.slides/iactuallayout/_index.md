---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /pt/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Especifica a posição real de um elemento de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getActualX()](#getActualX--) | Especifica a posição x real (esquerda) do elemento de gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica a parte superior real do elemento de gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento de gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento de gráfico. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Especifica a posição x real (esquerda) do elemento de gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Lê float.

**Retorna:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Especifica a parte superior real do elemento de gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Lê float.

**Retorna:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Especifica a largura real do elemento de gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Lê float.

**Retorna:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Especifica a altura real do elemento de gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Lê float.

**Retorna:**
float