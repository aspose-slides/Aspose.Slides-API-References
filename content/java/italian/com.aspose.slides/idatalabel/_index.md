---
title: IDataLabel
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le etichette di una serie.
type: docs
url: /it/com.aspose.slides/idatalabel/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Rappresenta le etichette di una serie.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isVisible()](#isVisible--) | False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show*- (ShowValue, ...) sono false). |
| [hide()](#hide--) | Nascondi l'etichetta dati impostando tutti i flag Show*- (ShowValue, ...) nello stato false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Restituisce il formato dell'etichetta dati. |
| [getValueFromCell()](#getValueFromCell--) | Ottiene o imposta la cella dati della cartella di lavoro. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Ottiene o imposta la cella dati della cartella di lavoro. |
| [getActualLabelText()](#getActualLabelText--) | Restituisce il testo effettivo dell'etichetta in base alle impostazioni di DataLabelFormat o al valore TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False indica che l'etichetta dati non è visibile (e quindi tutti i flag Show*- (ShowValue, ...) sono false). Boolean sola lettura.

--------------------

Se l'etichetta dati è visibile è possibile nasconderla con il metodo Hide(). Ma se l'etichetta dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show*- (ShowValue, ...) nello stato true.

**Restituisce:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Nascondi l'etichetta dati impostando tutti i flag Show*- (ShowValue, ...) nello stato false. IsVisible sarà false dopo questa operazione.

--------------------

Se l'etichetta dati non è visibile (IsVisible è false) è possibile renderla visibile impostando i flag Show*- (ShowValue, ...) nello stato true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Restituisce il formato dell'etichetta dati. Sola lettura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Restituisce:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Ottiene o imposta la cella dati della cartella di lavoro. Applicato se la proprietà IDataLabelFormat.ShowLabelValueFromCell è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Restituisce il testo effettivo dell'etichetta in base alle impostazioni di DataLabelFormat o al valore TextFrameForOverriding.Text.

**Restituisce:**
java.lang.String - Testo effettivo dell'etichetta String