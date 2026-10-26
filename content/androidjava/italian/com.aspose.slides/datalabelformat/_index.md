---
title: DataLabelFormat
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
url: /it/com.aspose.slides/datalabelformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Rappresenta le opzioni di formattazione per DataLabel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Lettura/scrittura boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Lettura/scrittura boolean. |
| [getNumberFormat()](#getNumberFormat--) | Rappresenta la stringa di formato per l'oggetto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Rappresenta la stringa di formato per l'oggetto DataLabels. |
| [getFormat()](#getFormat--) | Rappresenta il formato dell'etichetta dati. |
| [getPosition()](#getPosition--) | Rappresenta la posizione dell'etichetta dati. |
| [setPosition(int value)](#setPosition-int-) | Rappresenta la posizione dell'etichetta dati. |
| [getShowLegendKey()](#getShowLegendKey--) | Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. |
| [getShowValue()](#getShowValue--) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [getShowCategoryName()](#getShowCategoryName--) | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. |
| [getShowSeriesName()](#getShowSeriesName--) | Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. |
| [getShowPercentage()](#getShowPercentage--) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina se l'etichetta dati di un grafico specificato sarà visualizzata come callout dati o come etichetta dati. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina se l'etichetta dati di un grafico specificato sarà visualizzata come callout dati o come etichetta dati. |
| [getSeparator()](#getSeparator--) | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. |
| [getTextFormat()](#getTextFormat--) | Restituisce il formato testo del grafico. |
| [getChart()](#getChart--) | Restituisce il grafico. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Sola lettura long.

**Restituisce:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà IsNumberFormatLinkedToSource per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà IsNumberFormatLinkedToSource per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" causa che tutti DataLabels.get_Item(i).isNumberFormatLinkedToSource() siano uguali a val).

**Restituisce:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà IsNumberFormatLinkedToSource per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà IsNumberFormatLinkedToSource per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" causa che tutti DataLabels.get_Item(i).isNumberFormatLinkedToSource() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Rappresenta la stringa di formato per l'oggetto DataLabels. Lettura/scrittura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta DataLabelCollection. Quando questa proprietà viene impostata con un valore, lo stesso valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causa che tutti DataLabels.get_Item(i).getNumberFormat() siano uguali a val).

**Restituisce:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Rappresenta la stringa di formato per l'oggetto DataLabels. Lettura/scrittura String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta DataLabelCollection. Quando questa proprietà viene impostata con un valore, lo stesso valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causa che tutti DataLabels.get_Item(i).getNumberFormat() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Rappresenta il formato dell'etichetta dati. Sola lettura [IFormat](../../com.aspose.slides/iformat).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà rappresenta il formato predefinito per le nuove etichette dati nella raccolta DataLabelCollection.

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella raccolta DataLabelCollection. Rappresenta la posizione per gli oggetti DataLabel. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Position per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setPosition(val);" causa che tutti DataLabels.get_Item(i).getPosition() siano uguali a val).

**Restituisce:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella raccolta DataLabelCollection. Rappresenta la posizione per gli oggetti DataLabel. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Position per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setPosition(val);" causa che tutti DataLabels.get_Item(i).getPosition() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. True se la chiave della leggenda dell'etichetta dati è visibile. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLegendKey per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" causa che tutti DataLabels.get_Item(i).getShowLegendKey() siano uguali a val).

**Restituisce:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Rappresenta il comportamento di visualizzazione della chiave della leggenda dell'etichetta dati di un grafico specificato. True se la chiave della leggenda dell'etichetta dati è visibile. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLegendKey per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" causa che tutti DataLabels.get_Item(i).getShowLegendKey() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowValue per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" causa che tutti DataLabels.get_Item(i).getShowValue() siano uguali a val).

**Restituisce:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowValue per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" causa che tutti DataLabels.get_Item(i).getShowValue() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True visualizza il nome della categoria per le etichette dati su un grafico. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowCategoryName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" causa che tutti DataLabels.get_Item(i).getShowCategoryName() siano uguali a val).

**Restituisce:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True visualizza il nome della categoria per le etichette dati su un grafico. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowCategoryName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" causa che tutti DataLabels.get_Item(i).getShowCategoryName() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True mostra il nome della serie. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowSeriesName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" causa che tutti DataLabels.get_Item(i).getShowSeriesName() siano uguali a val).

**Restituisce:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True mostra il nome della serie. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowSeriesName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" causa che tutti DataLabels.get_Item(i).getShowSeriesName() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowPercentage per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowPercentage per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" causa che tutti DataLabels.get_Item(i).getShowPercentage() siano uguali a val).

**Restituisce:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowPercentage per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowPercentage per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" causa che tutti DataLabels.get_Item(i).getShowPercentage() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della bolla. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowBubbleSize per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" causa che tutti DataLabels.get_Item(i).getShowBubbleSize() siano uguali a val).

**Restituisce:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della bolla. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowBubbleSize per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" causa che tutti DataLabels.get_Item(i).getShowBubbleSize() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False le nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLeaderLines per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" causa che tutti DataLabels.get_Item(i).getShowLeaderLines() siano uguali a val).

**Restituisce:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False le nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLeaderLines per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" causa che tutti DataLabels.get_Item(i).getShowLeaderLines() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLabelValueFromCell per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" causa che tutti DataLabels.get_Item(i).getShowLabelValueFromCell() siano uguali a val).

**Restituisce:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. True visualizza il valore della cella. False lo nasconde. Lettura/scrittura boolean.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLabelValueFromCell per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" causa che tutti DataLabels.get_Item(i).getShowLabelValueFromCell() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Determina se l'etichetta dati di un grafico specificato sarà visualizzata come callout dati o come etichetta dati.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" causa che tutti DataLabels.get_Item(i).getShowLabelAsDataCallout() siano uguali a val).

**Restituisce:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Determina se l'etichetta dati di un grafico specificato sarà visualizzata come callout dati o come etichetta dati.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" causa che tutti DataLabels.get_Item(i).getShowLabelAsDataCallout() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Lettura/scrittura String.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Separator per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" causa che tutti DataLabels.get_Item(i).getSeparator() siano uguali a val).

**Restituisce:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. Lettura/scrittura String.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore nella proprietà Separator per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" causa che tutti DataLabels.get_Item(i).getSeparator() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Restituisce il formato testo del grafico. Sola lettura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Restituisce:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Restituisce il grafico. Sola lettura [IChart](../../com.aspose.slides/ichart).

**Restituisce:**
[IChart](../../com.aspose.slides/ichart)