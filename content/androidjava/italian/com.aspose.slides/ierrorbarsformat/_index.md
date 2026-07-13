---
title: IErrorBarsFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le barre di errore delle serie di diagrammi.
type: docs
url: /it/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Rappresenta le barre di errore delle serie di diagrammi. I valori personalizzati di ErrorBars sono in IChartDataPointCollection (nella proprietà [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene o imposta il tipo delle barre di errore. |
| [setType(int value)](#setType-int-) | Ottiene o imposta il tipo delle barre di errore. |
| [getValueType()](#getValueType--) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. |
| [setValueType(int value)](#setValueType-int-) | Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. |
| [hasEndCap()](#hasEndCap--) | Specifica che un cappuccio finale non è disegnato sulle barre di errore. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifica che un cappuccio finale non è disegnato sulle barre di errore. |
| [getValue()](#getValue--) | Ottiene o imposta il valore usato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. |
| [setValue(float value)](#setValue-float-) | Ottiene o imposta il valore usato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. |
| [getFormat()](#getFormat--) | Rappresenta il formato delle barre di errore. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta il formato delle barre di errore. |
| [isVisible()](#isVisible--) | Ottiene o imposta la visibilità delle barre di errore. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ottiene o imposta la visibilità delle barre di errore. |
### getType() {#getType--}
```
public abstract int getType()
```

Ottiene o imposta il tipo delle barre di errore. Lettura/scrittura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Restituisce:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Ottiene o imposta il tipo delle barre di errore. Lettura/scrittura [ErrorBarType](../../com.aspose.slides/errorbartype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. Nel caso di tipo di valore personalizzato, per specificare il valore utilizzare la proprietà [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto dati specifico nella collezione DataPoints della serie. Lettura/scrittura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Restituisce:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Rappresenta i possibili modi per determinare la lunghezza delle barre di errore. Nel caso di tipo di valore personalizzato, per specificare il valore utilizzare la proprietà [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) del punto dati specifico nella collezione DataPoints della serie. Lettura/scrittura [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Specifica che un cappuccio finale non è disegnato sulle barre di errore. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Specifica che un cappuccio finale non è disegnato sulle barre di errore. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

Ottiene o imposta il valore usato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. Lettura/scrittura float.

**Restituisce:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Ottiene o imposta il valore usato con i tipi di valore Fixed, Percentage e StandardDeviation per determinare la lunghezza delle barre di errore. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Rappresenta il formato delle barre di errore. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Rappresenta il formato delle barre di errore. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Ottiene o imposta la visibilità delle barre di errore. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Ottiene o imposta la visibilità delle barre di errore. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |