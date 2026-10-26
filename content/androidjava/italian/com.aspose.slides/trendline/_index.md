---
title: Trendline
second_title: Riferimento API Java di Aspose.Slides per Android
description: La classe rappresenta la linea di tendenza di una serie di grafico
type: docs
url: /it/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

La classe rappresenta la linea di tendenza di una serie di grafico
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String. |
| [getTrendlineType()](#getTrendlineType--) | Ottiene o imposta il tipo della linea di tendenza. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Ottiene o imposta il tipo della linea di tendenza. |
| [getFormat()](#getFormat--) | Rappresenta il formato della linea di tendenza. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Rappresenta il formato della linea di tendenza. |
| [getBackward()](#getBackward--) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. |
| [setBackward(double value)](#setBackward-double-) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. |
| [getForward()](#getForward--) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. |
| [setForward(double value)](#setForward-double-) | Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. |
| [getIntercept()](#getIntercept--) | Specifica il valore in cui la linea di tendenza deve incrociare l'asse y. |
| [setIntercept(double value)](#setIntercept-double-) | Specifica il valore in cui la linea di tendenza deve incrociare l'asse y. |
| [getDisplayEquation()](#getDisplayEquation--) | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). |
| [getOrder()](#getOrder--) | Specifica l'ordine della linea di tendenza polinomiale. |
| [setOrder(byte value)](#setOrder-byte-) | Specifica l'ordine della linea di tendenza polinomiale. |
| [getPeriod()](#getPeriod--) | Specifica il periodo della linea di tendenza per una media mobile. |
| [setPeriod(byte value)](#setPeriod-byte-) | Specifica il periodo della linea di tendenza per una media mobile. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Specifica che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Specifica che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Rappresenta la voce della legenda relativa a questa linea di tendenza Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inizializza TextFrameForOverriding con il testo nel parametro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Può contenere un testo formattato riccamente. |
| [getTextFormat()](#getTextFormat--) | Restituisce il formato del testo. |
| [getChart()](#getChart--) | Restituisce il grafico padre. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva padre di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di un FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```


Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```


Ottiene o imposta il nome della linea di tendenza. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```


Ottiene o imposta il tipo della linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype).

**Restituisce:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```


Ottiene o imposta il tipo della linea di tendenza. Lettura/scrittura [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Rappresenta il formato della linea di tendenza. Lettura/scrittura [IFormat](../../com.aspose.slides/iformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```


Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Restituisce:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```


Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende prima dei dati per la serie in analisi. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```


Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Restituisce:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```


Specifica il numero di categorie (o unità in un grafico a dispersione) che la linea di tendenza si estende dopo i dati per la serie in analisi. Su grafici a dispersione e non a dispersione, il valore deve essere non negativo. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```


Specifica il valore in cui la linea di tendenza deve incrociare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Restituisce:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```


Specifica il valore in cui la linea di tendenza deve incrociare l'asse y. Questa proprietà è supportata solo quando il tipo di linea di tendenza è exp, linear o poly. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```


Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). Lettura/scrittura boolean.

**Restituisce:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```


Specifica che l'equazione della linea di tendenza è visualizzata sul grafico (nella stessa etichetta del Rsquaredvalue). Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```


Specifică l'ordine della linea di tendenza polinomiale. Viene ignorata per gli altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Lettura/scrittura byte.

**Restituisce:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```


Specifică l'ordine della linea di tendenza polinomiale. Viene ignorata per gli altri tipi di linea di tendenza. Il valore deve essere compreso tra 2 e 6. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```


Specifică il periodo della linea di tendenza per una media mobile. Viene ignorata per le altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Lettura/scrittura byte.

**Restituisce:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```


Specifică il periodo della linea di tendenza per una media mobile. Viene ignorata per le altre varianti di linea di tendenza. Il valore deve essere compreso tra 2 e 255. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```


Specifică che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Restituisce:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```


Specifică che il valore R-squared della linea di tendenza è visualizzato sul grafico (nella stessa etichetta dell'equazione). Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Rappresenta la voce della legenda relativa a questa linea di tendenza Solo lettura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Restituisce:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


Inizializza TextFrameForOverriding con il testo nel parametro "text". Se TextFrameForOverriding è già inizializzato, modifica semplicemente il suo testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo per un nuovo TextFrameForOverriding. |

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


Può contenere un testo formattato riccamente. Se questa proprietà non è nulla, allora questo valore di testo formattato sovrascrive il testo auto-generato dell’etichetta dei dati. Il testo auto-generato dell’etichetta dei dati è quello gestito dalle proprietà ShowSeriesName, ShowValue, … e formattato con la proprietà TextFormatManager.TextFormat. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Restituisce il formato del testo. Solo lettura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Restituisce il grafico padre. Solo lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Restituisce la diapositiva padre di un FillFormat. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Restituisce la presentazione padre di un FillFormat. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)