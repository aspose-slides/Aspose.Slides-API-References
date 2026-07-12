---
title: ILegend
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa las propiedades de la leyenda de los gráficos.
type: docs
url: /es/com.aspose.slides/ilegend/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Representa las propiedades de la leyenda del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. |
| [getPosition()](#getPosition--) | Especifica la posición de la leyenda en un gráfico. |
| [setPosition(int value)](#setPosition-int-) | Especifica la posición de la leyenda en un gráfico. |
| [getFormat()](#getFormat--) | Devuelve el formato de una leyenda. |
| [getEntries()](#getEntries--) | Obtiene las entradas de la leyenda. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. Lectura/escritura boolean.

**Devuelve:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina si se permite que otros elementos del gráfico se superpongan a la leyenda. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Especifica la posición de la leyenda en un gráfico. Los valores no NaN de las propiedades X, Y, Width, Heigt anulan el efecto de esta propiedad. Lectura/escritura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Especifica la posición de la leyenda en un gráfico. Los valores no NaN de las propiedades X, Y, Width, Heigt anulan el efecto de esta propiedad. Lectura/escritura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Devuelve el formato de una leyenda. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Obtiene las entradas de la leyenda. Solo lectura [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Devuelve:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)