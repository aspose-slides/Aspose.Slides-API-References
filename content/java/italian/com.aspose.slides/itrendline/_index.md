---
title: ITrendline
second_title: Riferimento API Aspose.Slides per Java
description: La classe rappresenta la linea di tendenza della serie del diagramma
type: docs
url: /it/com.aspose.slides/itrendline/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

La classe rappresenta la linea di tendenza della serie del diagramma
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Ottiene o imposta il nome della linea di tendenza. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Ottiene o imposta il nome della linea di tendenza. |
| [getTrendlineType()](#getTrendlineType--) | Ottiene o imposta il tipo di linea di tendenza. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Ottiene o imposta il tipo di linea di tendenza. |
| [getFormat()](#getFormat--) | Rappresenta il formato della linea di tendenza. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta il formato della linea di tendenza. |
| [getBackward()](#getBackward--) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie che viene analizzata. |
| [setBackward(double value)](#setBackward-double-) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie che viene analizzata. |
| [getForward()](#getForward--) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie che viene analizzata. |
| [setForward(double value)](#setForward-double-) | Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie che viene analizzata. |
| [getIntercept()](#getIntercept--) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. |
| [setIntercept(double value)](#setIntercept-double-) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. |
| [getDisplayEquation()](#getDisplayEquation--) | Specifica che l'equazione della linea di tendenza viene visualizzata nel diagramma (nella stessa etichetta del valore Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specifica che l'equazione della linea di tendenza viene visualizzata nel diagramma (nella stessa etichetta del valore Rsquared). |
| [getOrder()](#getOrder--) | Specifica l'ordine della linea di tendenza polinomiale. |
| [setOrder(byte value)](#setOrder-byte-) | Specifica l'ordine della linea di tendenza polinomiale. |
| [getPeriod()](#getPeriod--) | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specifica il periodo della linea di tendenza per una linea di tendenza a media mobile. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specifica che il valore R-quadrato della linea di tendenza viene visualizzato nel diagramma (nella stessa etichetta dell'equazione). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specifica che il valore R-quadrato della linea di tendenza viene visualizzato nel diagramma (nella stessa etichetta dell'equazione). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Rappresenta la voce di leggenda correlata a questa linea di tendenza Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Returns:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Ottiene o imposta il tipo di linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Returns:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Ottiene o imposta il tipo di linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie che viene analizzata. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Returns:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie che viene analizzata. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie che viene analizzata. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Returns:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Specifica il numero di categorie (o unità su un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie che viene analizzata. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Returns:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Specifică che l'equazione della linea di tendenza viene visualizzata nel diagramma (nella stessa etichetta del valore Rsquared). Lettura/scrittura boolean.

**Returns:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Specifică che l'equazione della linea di tendenza viene visualizzata nel diagramma (nella stessa etichetta del valore Rsquared). Lettura/scrittura boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Specifică l'ordine della linea di tendenza polinomiale. È ignorato per altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Lettura/scrittura byte.

**Returns:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Specifică l'ordine della linea di tendenza polinomiale. È ignorato per altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Lettura/scrittura byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Specifică il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Lettura/scrittura byte.

**Returns:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Specifică il periodo della linea di tendenza per una linea di tendenza a media mobile. È ignorato per altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Lettura/scrittura byte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Specifica che il valore R-quadrato della linea di tendenza viene visualizzato nel diagramma (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Returns:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Specifica che il valore R-quadrato della linea di tendenza viene visualizzato nel diagramma (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Rappresenta la voce di leggenda correlata a questa linea di tendenza Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Returns:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)