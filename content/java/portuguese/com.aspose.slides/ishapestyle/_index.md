---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: Representa a referência de estilo da forma.
type: docs
url: /pt/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Representa a referência de estilo da forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLineColor()](#getLineColor--) | Retorna a cor de contorno de uma forma. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Retorna ou define o índice da coluna da linha em uma matriz de estilo. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Retorna ou define o índice da coluna da linha em uma matriz de estilo. |
| [getFillColor()](#getFillColor--) | Retorna a cor de preenchimento de uma forma. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Retorna ou define o índice da coluna de preenchimento da forma em matrizes de estilo. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Retorna ou define o índice da coluna de preenchimento da forma em matrizes de estilo. |
| [getEffectColor()](#getEffectColor--) | Retorna a cor de efeito de uma forma. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Retorna ou define o índice da coluna de efeito da forma em uma matriz de estilo. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Retorna ou define o índice da coluna de efeito da forma em uma matriz de estilo. |
| [getFontColor()](#getFontColor--) | Retorna a cor da fonte da forma. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Retorna ou define o índice da fonte da forma em uma coleção de fontes. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Retorna ou define o índice da fonte da forma em uma coleção de fontes. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Retorna a cor de contorno de uma forma. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Retorna ou define o índice da coluna da linha em uma matriz de estilo. Leitura/Gravação int.

**Retorna:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Retorna ou define o índice da coluna da linha em uma matriz de estilo. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Retorna a cor de preenchimento de uma forma. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Retorna ou define o índice da coluna de preenchimento da forma em matrizes de estilo. 0 significa sem preenchimento, valor positivo — índice nos estilos de preenchimento do tema, valor negativo — índice nos estilos de fundo do tema. Leitura/Gravação short.

**Retorna:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Retorna ou define o índice da coluna de preenchimento da forma em matrizes de estilo. 0 significa sem preenchimento, valor positivo — índice nos estilos de preenchimento do tema, valor negativo — índice nos estilos de fundo do tema. Leitura/Gravação short.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Retorna a cor de efeito de uma forma. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Retorna ou define o índice da coluna de efeito da forma em uma matriz de estilo. Leitura/Gravação long.

**Retorna:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Retorna ou define o índice da coluna de efeito da forma em uma matriz de estilo. Leitura/Gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Retorna a cor da fonte da forma. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Retorna ou define o índice da fonte da forma em uma coleção de fontes. Leitura/Gravação [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Retorna:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Retorna ou define o índice da fonte da forma em uma coleção de fontes. Leitura/Gravação [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |