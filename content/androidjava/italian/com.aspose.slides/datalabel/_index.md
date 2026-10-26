---
title: DataLabel
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/datalabel/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
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
| [getChart()](#getChart--) | Restituisce il grafico padre. |
| [isVisible()](#isVisible--) | False indica che l'etichetta dei dati non è visibile (e quindi tutti i flag Show\*-flags (ShowValue, ...) sono false). |
| [hide()](#hide--) | Nasconde l'etichetta dei dati impostando tutti i flag Show\*-flags (ShowValue, ...) su false. |
| [getActualLabelText()](#getActualLabelText--) | Restituisce il testo effettivo dell'etichetta in base alle impostazioni di DataLabelFormat o al valore TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inizializza TextFrameForOverriding con il testo nel parametro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Può contenere un testo formattato in modo complesso. |
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
| [getDataLabelFormat()](#getDataLabelFormat--) | Restituisce il formato dell'etichetta dei dati. |
| [getValueFromCell()](#getValueFromCell--) | Ottiene o imposta la cella dati del workbook. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Ottiene o imposta la cella dati del workbook. |
| [getActualX()](#getActualX--) | Specifica la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualY()](#getActualY--) | Specifica la parte superiore effettiva dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualWidth()](#getActualWidth--) | Specifica la larghezza effettiva dell'elemento del grafico. |
| [getActualHeight()](#getActualHeight--) | Specifica l'altezza effettiva dell'elemento del grafico. |
| [getSlide()](#getSlide--) | Restituisce la slide padre di un FillFormat. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di un FillFormat. |

### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Crea una nuova istanza della classe DataLabel.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ChartDataPoint padre. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico padre. Sola lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False indica che l'etichetta dei dati non è visibile (e quindi tutti i flag Show\*-flags (ShowValue, ...) sono false). Sola lettura boolean .

--------------------

Se l'etichetta dei dati è visibile, è possibile nasconderla con il metodo Hide(). Ma se l'etichetta dei dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show\*-flags (ShowValue, ...) allo stato true.

**Restituisce:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Nasconde l'etichetta dei dati impostando tutti i flag Show\*-flags (ShowValue, ...) su false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dei dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show\*-flags (ShowValue, ...) allo stato true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Restituisce il testo effettivo dell'etichetta in base alle impostazioni di DataLabelFormat o al valore TextFrameForOverriding.Text.

**Restituisce:**
java.lang.String - L'oggetto java.lang.String.

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inizializza TextFrameForOverriding con il testo nel parametro "text". Se TextFrameForOverriding è già inizializzato, cambia semplicemente il suo testo.

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

Può contenere un testo formattato in modo complesso. Se questa proprietà non è null, questo valore di testo formattato sovrascrive il testo generato automaticamente dell'etichetta dei dati. Il testo generato automaticamente dell'etichetta dei dati è quello gestito dalle proprietà ShowSeriesName, ShowValue, ... e formattato con la proprietà TextFormatManager.TextFormat. Sola lettura [ITextFrame](../../com.aspose.slides/itextframe).

**Restituisce:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Restituisce il formato del testo. Sola lettura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getX() {#getX--}
```
public final float getX()
```

Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. Lettura/scrittura float .

**Restituisce:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Restituisce o imposta la coordinata x di un titolo come frazione della larghezza del grafico. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Lettura/scrittura float .

**Restituisce:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Restituisce o imposta la coordinata y di un titolo come frazione dell'altezza del grafico. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. Lettura/scrittura float .

**Restituisce:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Restituisce o imposta la larghezza di un titolo come frazione della larghezza del grafico. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. Lettura/scrittura float .

**Restituisce:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Restituisce o imposta l'altezza di un titolo come frazione dell'altezza del grafico. Lettura/scrittura float .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Destra. Sola lettura float .

**Restituisce:**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

Inferiore. Sola lettura float .

**Restituisce:**
float

### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Restituisce il formato dell'etichetta dei dati. Sola lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Ottiene o imposta la cella dati del workbook. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Ottiene o imposta la cella dati del workbook. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Specifica la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura float .

**Restituisce:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Specifica la parte superiore effettiva dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura float .

**Restituisce:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Specifica la larghezza effettiva dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura float .

**Restituisce:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Specifica l'altezza effettiva dell'elemento del grafico. Chiamare il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Lettura float .

**Restituisce:**
float

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la slide padre di un FillFormat. Sola lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di un FillFormat. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)