---
title: ITrendline
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Classe che rappresenta la linea di tendenza della serie del grafico
type: docs
url: /it/com.aspose.slides/itrendline/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Classe che rappresenta la linea di tendenza della serie del grafico
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Ottiene o imposta il nome della linea di tendenza. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Ottiene o imposta il nome della linea di tendenza. |
| [getTrendlineType()](#getTrendlineType--) | Ottiene o imposta il tipo della linea di tendenza. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Ottiene o imposta il tipo della linea di tendenza. |
| [getFormat()](#getFormat--) | Rappresenta il formato della linea di tendenza. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta il formato della linea di tendenza. |
| [getBackward()](#getBackward--) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie a cui è associata. |
| [setBackward(double value)](#setBackward-double-) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie a cui è associata. |
| [getForward()](#getForward--) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie a cui è associata. |
| [setForward(double value)](#setForward-double-) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie a cui è associata. |
| [getIntercept()](#getIntercept--) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. |
| [setIntercept(double value)](#setIntercept-double-) | Specifica il valore in cui la linea di tendenza deve attraversare l'asse y. |
| [getDisplayEquation()](#getDisplayEquation--) | Specifica che l'equazione della linea di tendenza è visualizzata nel grafico (nella stessa etichetta del valore R-squared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specifica che l'equazione della linea di tendenza è visualizzata nel grafico (nella stessa etichetta del valore R-squared). |
| [getOrder()](#getOrder--) | Specifica l'ordine della linea di tendenza polinomiale. |
| [setOrder(byte value)](#setOrder-byte-) | Specifica l'ordine della linea di tendenza polinomiale. |
| [getPeriod()](#getPeriod--) | Specifica il periodo della linea di tendenza per una media mobile. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specifica il periodo della linea di tendenza per una media mobile. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specifica che il valore R-squared della linea di tendenza è visualizzato nel grafico (nella stessa etichetta dell'equazione). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specifica che il valore R-squared della linea di tendenza è visualizzato nel grafico (nella stessa etichetta dell'equazione). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Rappresenta la voce della leggenda associata a questa linea di tendenza. Sola lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


Ottiene o imposta il tipo della linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Restituisce:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


Ottiene o imposta il tipo della linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


Specifică il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie a cui è associata. Nei grafici a dispersione e non-dispersione, il valore deve essere qualsiasi valore non negativo. Lettura/scrittura double.

**Restituisce:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


Specifică il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie a cui è associata. Nei grafici a dispersione e non-dispersione, il valore deve essere qualsiasi valore non negativo. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```


Specifică il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie a cui è associata. Nei grafici a dispersione e non-dispersione, il valore deve essere qualsiasi valore non negativo. Lettura/scrittura double.

**Restituisce:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


Specifică il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie a cui è associata. Nei grafici a dispersione e non-dispersione, il valore deve essere qualsiasi valore non negativo. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


Specifică il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Restituisce:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


Specifică il valore in cui la linea di tendenza deve attraversare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


Specifică che l'equazione della linea di tendenza è visualizzata nel grafico (nella stessa etichetta del valore R-squared). Lettura/scrittura boolean.

**Restituisce:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


Specifică che l'equazione della linea di tendenza è visualizzata nel grafico (nella stessa etichetta del valore R-squared). Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


Specifică l'ordine della linea di tendenza polinomiale. È ignorato per gli altri tipi di linea di tendenza. Il valore deve trovarsi tra 2 e 6. Lettura/scrittura byte.

**Restituisce:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


Specifică l'ordine della linea di tendenza polinomiale. È ignorato per gli altri tipi di linea di tendenza. Il valore deve trovarsi tra 2 e 6. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


Specifică il periodo della linea di tendenza per una media mobile. È ignorato per le altre varianti della linea di tendenza. Il valore deve trovarsi tra 2 e 255. Lettura/scrittura byte.

**Restituisce:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


Specifică il periodo della linea di tendenza per una media mobile. È ignorato per le altre varianti della linea di tendenza. Il valore deve trovarsi tra 2 e 255. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


Specifică che il valore R-squared della linea di tendenza è visualizzato nel grafico (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Restituisce:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


Specifică che il valore R-squared della linea di tendenza è visualizzato nel grafico (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Rappresenta la voce della leggenda associata a questa linea di tendenza. Sola lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)