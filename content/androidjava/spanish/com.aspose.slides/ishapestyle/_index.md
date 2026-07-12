---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Representa la referencia del estilo de la forma.
type: docs
url: /es/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Representa la referencia del estilo de la forma.
## Métodos

| Método | Descripción |
| --- | --- |
| [getLineColor()](#getLineColor--) | Devuelve el color del contorno de la forma. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Devuelve o establece el índice de columna de la línea en una matriz de estilo. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Devuelve o establece el índice de columna de la línea en una matriz de estilo. |
| [getFillColor()](#getFillColor--) | Devuelve el color de relleno de la forma. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Devuelve o establece el índice de columna de relleno de la forma en matrices de estilo. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Devuelve o establece el índice de columna de relleno de la forma en matrices de estilo. |
| [getEffectColor()](#getEffectColor--) | Devuelve el color del efecto de la forma. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Devuelve o establece el índice de columna del efecto de la forma en una matriz de estilo. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Devuelve o establece el índice de columna del efecto de la forma en una matriz de estilo. |
| [getFontColor()](#getFontColor--) | Devuelve el color de fuente de la forma. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Devuelve o establece el índice de fuente de la forma en una colección de fuentes. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Devuelve o establece el índice de fuente de la forma en una colección de fuentes. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Devuelve el color del contorno de la forma. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Devuelve o establece el índice de columna de la línea en una matriz de estilo. Lectura/escritura int.

**Devuelve:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Devuelve o establece el índice de columna de la línea en una matriz de estilo. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Devuelve el color de relleno de la forma. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Devuelve o establece el índice de columna de relleno de la forma en matrices de estilo. 0 significa sin relleno, valor positivo - índice en los estilos de relleno del tema, valor negativo - índice en los estilos de fondo del tema. Lectura/escritura short.

**Devuelve:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Devuelve o establece el índice de columna de relleno de la forma en matrices de estilo. 0 significa sin relleno, valor positivo - índice en los estilos de relleno del tema, valor negativo - índice en los estilos de fondo del tema. Lectura/escritura short.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Devuelve el color del efecto de la forma. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Devuelve o establece el índice de columna del efecto de la forma en una matriz de estilo. Lectura/escritura long.

**Devuelve:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Devuelve o establece el índice de columna del efecto de la forma en una matriz de estilo. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Devuelve el color de fuente de la forma. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Devuelve o establece el índice de fuente de la forma en una colección de fuentes. Lectura/escritura [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Devuelve:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Devuelve o establece el índice de fuente de la forma en una colección de fuentes. Lectura/escritura [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |