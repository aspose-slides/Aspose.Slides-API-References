---
title: IChartTitle
second_title: Aspose.Slides para la referencia API de Java
description: Representa las propiedades del título del gráfico.
type: docs
url: /es/com.aspose.slides/icharttitle/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Representa las propiedades del título del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina si se permitirá que otros elementos del gráfico se superpongan al título. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina si se permitirá que otros elementos del gráfico se superpongan al título. |
| [getFormat()](#getFormat--) | Devuelve los estilos de relleno, línea y efecto de un título. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina si se permite que otros elementos del gráfico se superpongan al título. Lectura/escritura boolean.

**Devuelve:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina si se permite que otros elementos del gráfico se superpongan al título. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Devuelve los estilos de relleno, línea y efecto de un título. Solo lectura [IFormat](../../com.aspose.slides/iformat).

**Devuelve:**
[IFormat](../../com.aspose.slides/iformat)