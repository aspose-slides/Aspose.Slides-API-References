---
title: LegendEntryProperties
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa las propiedades de la leyenda de un gráfico.
type: docs
url: /es/com.aspose.slides/legendentryproperties/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

Representa las propiedades de la leyenda de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | Returns text format. |
| [getHide()](#getHide--) | Determines whether the legend entry is hide. |
| [setHide(boolean value)](#setHide-boolean-) | Determines whether the legend entry is hide. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Returns the parent chart. |
| [getSlide()](#getSlide--) | Returns the parent slide of a FillFormat. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a FillFormat. |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Devuelve el formato de texto. Solo lectura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Devuelve:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getHide() {#getHide--}
```
public final boolean getHide()
```


Determina si la entrada de la leyenda está oculta. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```


Determina si la entrada de la leyenda está oculta. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Devuelve el gráfico padre. Solo lectura [IChart](../../com.aspose.slides/ichart).

**Devuelve:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Devuelve la diapositiva principal de un FillFormat. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Devuelve la presentación principal de un FillFormat. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)