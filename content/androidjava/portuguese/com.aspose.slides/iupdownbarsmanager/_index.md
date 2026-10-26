---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /pt/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Fornece acesso às barras de alta/baixa de gráficos de Linha ou de Ações.
## Métodos

| Método | Descrição |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Retorna o formato das barras de alta. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Retorna o formato das barras de baixa. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se o gráfico possui barras de alta/baixa. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Determina se o gráfico possui barras de alta/baixa. |
| [getGapWidth()](#getGapWidth--) | Retorna ou define a largura do espaçamento. |
| [setGapWidth(int value)](#setGapWidth-int-) | Retorna ou define a largura do espaçamento. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


Retorna o formato das barras de alta. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


Retorna o formato das barras de baixa. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


Determina se o gráfico possui barras de alta/baixa. Leitura/gravação boolean.

**Retorna:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


Determina se o gráfico possui barras de alta/baixa. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


Retorna ou define a largura do espaçamento. Leitura/gravação int.

**Retorna:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


Retorna ou define a largura do espaçamento. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |