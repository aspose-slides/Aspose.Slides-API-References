---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Proporciona acceso a las barras ascendentes/descendentes de un gráfico de líneas o de cotizaciones.
type: docs
url: /es/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Proporciona acceso a las barras ascendentes/descendentes de un gráfico de líneas o de cotizaciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Devuelve el formato de las barras ascendentes. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Devuelve el formato de las barras descendentes. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina si el gráfico tiene barras ascendentes/descendentes. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Determina si el gráfico tiene barras ascendentes/descendentes. |
| [getGapWidth()](#getGapWidth--) | Devuelve o establece el ancho del espacio. |
| [setGapWidth(int value)](#setGapWidth-int-) | Devuelve o establece el ancho del espacio. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Devuelve el formato de las barras ascendentes. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Devuelve el formato de las barras descendentes. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Determina si el gráfico tiene barras ascendentes/descendentes. Lectura/escritura boolean.

**Devuelve:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Determina si el gráfico tiene barras ascendentes/descendentes. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Devuelve o establece el ancho del espacio. Lectura/escritura int.

**Devuelve:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Devuelve o establece el ancho del espacio. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |