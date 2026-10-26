---
title: IChartTitle
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le proprietà del titolo del grafico.
type: docs
url: /it/com.aspose.slides/icharttitle/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Rappresenta le proprietà del titolo del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina se altri elementi del grafico possono sovrapporsi al titolo. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se altri elementi del grafico possono sovrapporsi al titolo. |
| [getFormat()](#getFormat--) | Restituisce gli stili di riempimento, linea ed effetto di un titolo. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Determina se altri elementi del grafico possono sovrapporsi al titolo. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Determina se altri elementi del grafico possono sovrapporsi al titolo. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Restituisce gli stili di riempimento, linea ed effetto di un titolo. Sola lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)