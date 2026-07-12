---
title: IDataLabel
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una serie de etiquetas.
type: docs
url: /es/com.aspose.slides/idatalabel/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representa una serie de etiquetas.
## Métodos

| Método | Descripción |
| --- | --- |
| [isVisible()](#isVisible--) | False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son false). |
| [hide()](#hide--) | Ocultar la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) al estado false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Devuelve el formato de la etiqueta de datos. |
| [getValueFromCell()](#getValueFromCell--) | Obtiene o establece la celda de datos del libro de trabajo. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtiene o establece la celda de datos del libro de trabajo. |
| [getActualLabelText()](#getActualLabelText--) | Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o en el valor TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que la etiqueta de datos no es visible (y por lo tanto todas las banderas Show*-flags (ShowValue, ...) son false). Boolean de solo lectura.

--------------------

Si la etiqueta de datos es visible, puedes ocultarla con el método Hide(). Pero si la etiqueta de datos no es visible (IsVisible es false), puedes hacerla visible configurando las banderas Show*-flags (ShowValue, ...) al estado true.

**Devuelve:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Ocultar la etiqueta de datos estableciendo todas las banderas Show*-flags (ShowValue, ...) al estado false. IsVisible será false después de esto.

--------------------

Si la etiqueta de datos no es visible (IsVisible es false), puedes hacerla visible configurando las banderas Show*-flags (ShowValue, ...) al estado true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Devuelve el formato de la etiqueta de datos. Solo lectura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Devuelve:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtiene o establece la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Devuelve:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtiene o establece la celda de datos del libro de trabajo. Se aplica si la propiedad IDataLabelFormat.ShowLabelValueFromCell es true.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Devuelve el texto real de la etiqueta basado en la configuración de DataLabelFormat o en el valor TextFrameForOverriding.Text.

**Devuelve:**
java.lang.String - Texto real de la etiqueta String