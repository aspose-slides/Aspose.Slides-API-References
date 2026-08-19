---
title: DataLabel
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/datalabel/
---
**Eredita:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Rappresenta le etichette di una serie.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Crea una nuova istanza della classe DataLabel. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Restituisce il grafico genitore. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show*- (ShowValue, ...) sono falsi). |
| [hide()](#hide--) | Nascondi l'etichetta dati impostando tutti i flag Show*- (ShowValue, ...) allo stato false. |
| [getActualLabelText()](#getActualLabelText--) | Restituisce il testo effettivo dell'etichetta basato sulle impostazioni di DataLabelFormat o sul valore TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inizializza TextFrameForOverriding con il testo del parametro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Può contenere un testo formattato riccamente. |
| [getTextFormat()](#getTextFormat--) | Restituisce il formato del testo. |
| [getX()](#getX--) | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. |
| [setX(float value)](#setX-float-) | Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. |
| [getY()](#getY--) | Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. |
| [setY(float value)](#setY-float-) | Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. |
| [getWidth()](#getWidth--) | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. |
| [setWidth(float value)](#setWidth-float-) | Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. |
| [getHeight()](#getHeight--) | Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. |
| [setHeight(float value)](#setHeight-float-) | Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. |
| [getRight()](#getRight--) | Destra. |
| [getBottom()](#getBottom--) | Inferiore. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Restituisce il formato dell'etichetta dati. |
| [getValueFromCell()](#getValueFromCell--) | Ottiene o imposta la cella dati della cartella di lavoro. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Ottiene o imposta la cella dati della cartella di lavoro. |
| [getActualX()](#getActualX--) | Specifica la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualY()](#getActualY--) | Specifica la parte superiore reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualWidth()](#getActualWidth--) | Specifica la larghezza reale dell'elemento del grafico. |
| [getActualHeight()](#getActualHeight--) | Specifica l'altezza reale dell'elemento del grafico. |
| [getSlide()](#getSlide--) | Restituisce la diapositiva genitore di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Crea una nuova istanza della classe DataLabel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint genitore. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico genitore. Solo lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show*- (ShowValue, ...) sono falsi). Solo lettura  boolean .

**Restituisce:**
boolean

--------------------

Se l'etichetta dati è visibile è possibile nasconderla con il metodo Hide(). Se l'etichetta dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show*- (ShowValue, ...) allo stato true.

**Restituisce:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Nascondi l'etichetta dati impostando tutti i flag Show*- (ShowValue, ...) allo stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show*- (ShowValue, ...) allo stato true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Restituisce il testo effettivo dell'etichetta basato sulle impostazioni di DataLabelFormat o sul valore TextFrameForOverriding.Text.

**Restituisce:**
java.lang.String - L'oggetto java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inizializza TextFrameForOverriding con il testo del parametro "text". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo.

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

Può contenere un testo formattato riccamente. Se questa proprietà non è null, il valore di testo formattato sovrascrive il testo generato automaticamente dell'etichetta dati. Il testo generato automaticamente dell'etichetta dati è quello gestito dalle proprietà ShowSeriesName, ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat. Solo lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Restituisce il formato del testo. Solo lettura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. Lettura/scrittura  float .

**Restituisce:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Lettura/scrittura  float .

**Restituisce:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. Lettura/scrittura  float .

**Restituisce:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. Lettura/scrittura  float .

**Restituisce:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. Lettura/scrittura  float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Destra. Solo lettura  float .

**Restituisce:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Inferiore. Solo lettura  float .

**Restituisce:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Restituisce il formato dell'etichetta dati. Solo lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specifică la posizione x reale (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura  float .

**Restituisce:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specifică la parte superiore reale dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura  float .

**Restituisce:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specifică la larghezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura  float .

**Restituisce:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specifică l'altezza reale dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori reali. Solo lettura  float .

**Restituisce:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la diapositiva genitore di un FillFormat. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione genitore di un FillFormat. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)