---
title: IDataLabelFormat
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le opzioni di formattazione per DataLabel.
type: docs
url: /it/com.aspose.slides/idatalabelformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Rappresenta le opzioni di formattazione per DataLabel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Booleano di lettura/scrittura. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Booleano di lettura/scrittura. |
| [getNumberFormat()](#getNumberFormat--) | Rappresenta la stringa di formato per l'oggetto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Rappresenta la stringa di formato per l'oggetto DataLabels. |
| [getFormat()](#getFormat--) | Rappresenta il formato dell'etichetta dati. |
| [getPosition()](#getPosition--) | Rappresenta la posizione dell'etichetta dati. |
| [setPosition(int value)](#setPosition-int-) | Rappresenta la posizione dell'etichetta dati. |
| [getShowLegendKey()](#getShowLegendKey--) | Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. |
| [getShowValue()](#getShowValue--) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [getShowCategoryName()](#getShowCategoryName--) | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. |
| [getShowSeriesName()](#getShowSeriesName--) | Restituisce o imposta un Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Restituisce o imposta un Booleano per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. |
| [getShowPercentage()](#getShowPercentage--) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina se l'etichetta dati di un grafico specificato sarà visualizzata come richiamo dati o come etichetta dati. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina se l'etichetta dati di un grafico specificato sarà visualizzata come richiamo dati o come etichetta dati. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Rappresenta il comportamento di visualizzazione del valore della cella dell'etichetta dati di un grafico specificato. |
| [getSeparator()](#getSeparator--) | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Imposta o restituisce un Variant che rappresenta il separatore usato per le etichette dati su un grafico. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà IsNumberFormatLinkedToSource per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà IsNumberFormatLinkedToSource di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" causa che tutti DataLabels.get_Item(i).isNumberFormatLinkedToSource() siano uguali a val).

**Restituisce:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà IsNumberFormatLinkedToSource per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà IsNumberFormatLinkedToSource di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" causa che tutti DataLabels.get_Item(i).isNumberFormatLinkedToSource() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Rappresenta la stringa di formato per l'oggetto DataLabels. Stringa di lettura/scrittura.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta DataLabelCollection. Quando questa proprietà viene impostata con un valore, tale valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" fa sì che tutti DataLabels.get_Item(i).getNumberFormat() siano uguali a val).

**Restituisce:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Rappresenta la stringa di formato per l'oggetto DataLabels. Stringa di lettura/scrittura.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà NumberFormat per le nuove etichette dati nella raccolta DataLabelCollection. Quando questa proprietà viene impostata con un valore, tale valore viene impostato anche per la proprietà NumberFormat di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" fa sì che tutti DataLabels.get_Item(i).getNumberFormat() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Rappresenta il formato dell'etichetta dati. Solo lettura [IFormat](../../com.aspose.slides/iformat).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà rappresenta il formato predefinito per le nuove etichette dati nella raccolta DataLabelCollection.

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella raccolta DataLabelCollection. Rappresenta la posizione per gli oggetti DataLabel. Impostare questa proprietà con un valore la imposta anche per la proprietà Position di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" fa sì che tutti DataLabels.get_Item(i).getPosition() siano uguali a val).

**Restituisce:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Rappresenta la posizione dell'etichetta dati. Lettura/scrittura [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Position per le nuove etichette dati nella raccolta DataLabelCollection. Rappresenta la posizione per gli oggetti DataLabel. Impostare questa proprietà con un valore la imposta anche per la proprietà Position di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" fa sì che tutti DataLabels.get_Item(i).getPosition() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. True se la chiave legenda dell'etichetta dati è visibile. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà ShowLegendKey di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" causa che tutti DataLabels.get_Item(i).getShowLegendKey() siano uguali a val).

**Restituisce:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Rappresenta il comportamento di visualizzazione della chiave legenda dell'etichetta dati di un grafico specificato. True se la chiave legenda dell'etichetta dati è visibile. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLegendKey per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà ShowLegendKey di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" causa che tutti DataLabels.get_Item(i).getShowLegendKey() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà ShowValue di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" causa che tutti DataLabels.get_Item(i).getShowValue() siano uguali a val).

**Restituisce:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False per nasconderlo. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowValue per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà ShowValue di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" causa che tutti DataLabels.get_Item(i).getShowValue() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nasconderlo. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore la imposta anche per la proprietà ShowCategoryName di tutte le etichette dati nella raccolta DataLabelCollection (ad es. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" causa che tutti DataLabels.get_Item(i).getShowCategoryName() siano uguali a val).

**Restituisce:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Rappresenta il comportamento di visualizzazione del nome della categoria dell'etichetta dati di un grafico specificato. True per visualizzare il nome della categoria per le etichette dati su un grafico. False per nasconderlo. Booleano di lettura/scrittura.

--------------------
Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowCategoryName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowCategoryName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" causa che tutti DataLabels.get_Item(i).getShowCategoryName() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nasconderlo. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowSeriesName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" causa che tutti DataLabels.get_Item(i).getShowSeriesName() siano uguali a val).

**Restituisce:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Restituisce o imposta un Boolean per indicare il comportamento di visualizzazione del nome della serie per le etichette dati su un grafico. True per mostrare il nome della serie. False per nasconderlo. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowSeriesName per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowSeriesName per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" causa che tutti DataLabels.get_Item(i).getShowSeriesName() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowPercentage per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowPercentage per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" causa che tutti DataLabels.get_Item(i).getShowPercentage() siano uguali a val).

**Restituisce:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore percentuale dell'etichetta dati di un grafico specificato. True visualizza il valore percentuale. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowPercentage per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowPercentage per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" causa che tutti DataLabels.get_Item(i).getShowPercentage() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowBubbleSize per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" causa che tutti DataLabels.get_Item(i).getShowBubbleSize() siano uguali a val).

**Restituisce:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore della dimensione della bolla dell'etichetta dati di un grafico specificato. True visualizza il valore della dimensione della bolla. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowBubbleSize per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowBubbleSize per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" causa che tutti DataLabels.get_Item(i).getShowBubbleSize() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False le nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLeaderLines per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" causa che tutti DataLabels.get_Item(i).getShowLeaderLines() siano uguali a val).

**Restituisce:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Rappresenta il comportamento di visualizzazione delle linee guida dell'etichetta dati di un grafico specificato. True visualizza le linee guida. False le nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLeaderLines per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLeaderLines per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" causa che tutti DataLabels.get_Item(i).getShowLeaderLines() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Determina se l'etichetta dati di un grafico specificato verrà visualizzata come callout dati o come etichetta dati.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" causa che tutti DataLabels.get_Item(i).getShowLabelAsDataCallout() siano uguali a val).

**Restituisce:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Determina se l'etichetta dati di un grafico specificato verrà visualizzata come callout dati o come etichetta dati.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelAsDataCallout per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLabelAsDataCallout per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" causa che tutti DataLabels.get_Item(i).getShowLabelAsDataCallout() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Rappresenta il comportamento di visualizzazione del valore di cella dell'etichetta dati di un grafico specificato. True visualizza il valore di cella. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLabelValueFromCell per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" causa che tutti DataLabels.get_Item(i).getShowLabelValueFromCell() siano uguali a val).

**Restituisce:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Rappresenta il comportamento di visualizzazione del valore di cella dell'etichetta dati di un grafico specificato. True visualizza il valore di cella. False lo nasconde. Booleano di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà ShowLabelValueFromCell per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà ShowLabelValueFromCell per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" causa che tutti DataLabels.get_Item(i).getShowLabelValueFromCell() siano uguali a val).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Imposta o restituisce un Variant che rappresenta il separatore utilizzato per le etichette dati su un grafico. Stringa di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà Separator per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" causa che tutti DataLabels.get_Item(i).getSeparator() siano uguali a val).

**Restituisce:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Imposta o restituisce un Variant che rappresenta il separatore utilizzato per le etichette dati su un grafico. Stringa di lettura/scrittura.

--------------------

Se il genitore di questo oggetto DataLabelFormat è una raccolta DataLabelCollection di etichette dati, questa proprietà ottiene o imposta il valore predefinito della proprietà Separator per le nuove etichette dati nella raccolta DataLabelCollection. Impostare questa proprietà con un valore imposta anche questo valore alla proprietà Separator per tutte le etichette dati nella raccolta DataLabelCollection (ad esempio "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" causa che tutti DataLabels.get_Item(i).getSeparator() siano uguali a val).
**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |