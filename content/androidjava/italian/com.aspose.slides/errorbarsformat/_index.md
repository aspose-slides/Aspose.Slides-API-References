---
title: ErrorBarsFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le barre di errore delle serie di grafico.
type: docs
url: /it/com.aspose.slides/errorbarsformat/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Rappresenta le barre di errore delle serie di grafico. I valori personalizzati di ErrorBars sono in IChartDataPointCollection (nella proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene o imposta il tipo delle barre di errore. |
| [setType(int value)](#setType-int-) | Ottiene o imposta il tipo delle barre di errore. |
| [getValueType()](#getValueType--) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. |
| [setValueType(int value)](#setValueType-int-) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. |
| [hasEndCap()](#hasEndCap--) | Specifica che una capocchia finale non è disegnata sulle barre di errore. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifica che una capocchia finale non è disegnata sulle barre di errore. |
| [getValue()](#getValue--) | Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. |
| [setValue(float value)](#setValue-float-) | Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. |
| [getFormat()](#getFormat--) | Rappresenta il formato delle barre di errore. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta il formato delle barre di errore. |
| [getChart()](#getChart--) | Restituisce il chart genitore. |
| [isVisible()](#isVisible--) | Ottiene o imposta la visibilità delle barre di errore. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta la visibilità delle barre di errore. |
| [getSlide()](#getSlide--) | Restituisce la slide genitore di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Ottiene o imposta il tipo delle barre di errore. Lettura/scrittura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Restituisce:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Ottiene o imposta il tipo delle barre di errore. Lettura/scrittura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. In caso di tipo di valore personalizzato per specificare il valore usare la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) del punto dati specifico nella raccolta DataPoints della serie. In caso di tipo di valore Fixed, Percentage o StandardDeviation usare la proprietà Value per specificare il valore. Lettura/scrittura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Restituisce:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. In caso di tipo di valore personalizzato per specificare il valore usare la proprietà ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) del punto dati specifico nella raccolta DataPoints della serie. In caso di tipo di valore Fixed, Percentage o StandardDeviation usare la proprietà Value per specificare il valore. Lettura/scrittura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Specifica che una capocchia finale non è disegnata sulle barre di errore. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Specifica che una capocchia finale non è disegnata sulle barre di errore. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. In qualsiasi altro caso restituisce NaN. Lettura/scrittura float.

**Restituisce:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Ottiene o imposta il valore utilizzato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. In qualsiasi altro caso restituisce NaN. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Rappresenta il formato delle barre di errore. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Rappresenta il formato delle barre di errore. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il chart genitore. Sola lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Ottiene o imposta la visibilità delle barre di errore. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Ottiene o imposta la visibilità delle barre di errore. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la slide genitore di un FillFormat. Sola lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di un FillFormat. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)