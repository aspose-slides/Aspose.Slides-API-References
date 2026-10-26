---
title: ILegend
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa as propriedades da legenda dos gráficos.
type: docs
url: /pt/com.aspose.slides/ilegend/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Representa as propriedades da legenda do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina se outros elementos do gráfico podem se sobrepor à legenda. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se outros elementos do gráfico podem se sobrepor à legenda. |
| [getPosition()](#getPosition--) | Especifica a posição da legenda em um gráfico. |
| [setPosition(int value)](#setPosition-int-) | Especifica a posição da legenda em um gráfico. |
| [getFormat()](#getFormat--) | Retorna o formato de uma legenda. |
| [getEntries()](#getEntries--) | Obtém as entradas da legenda. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina se outros elementos do gráfico podem se sobrepor à legenda. Leitura e escrita boolean.

**Retorna:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina se outros elementos do gráfico podem se sobrepor à legenda. Leitura e escrita boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Especifica a posição da legenda em um gráfico. Valores não NaN das propriedades X, Y, Width, Height substituem o efeito desta propriedade. Leitura e escrita [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Retorna:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Especifica a posição da legenda em um gráfico. Valores não NaN das propriedades X, Y, Width, Height substituem o efeito desta propriedade. Leitura e escrita [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retorna o formato de uma legenda. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Obtém as entradas da legenda. Somente leitura [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Retorna:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)