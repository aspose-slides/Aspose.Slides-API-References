---
title: ILegend
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le proprietà della legenda dei grafici.
type: docs
url: /it/com.aspose.slides/ilegend/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Rappresenta le proprietà della legenda del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getEntries()](#getEntries--) | Gets legend entries. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina se altri elementi del grafico devono poter sovrapporsi alla legenda. Lettura/scrittura boolean.

**Restituisce:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina se altri elementi del grafico devono poter sovrapporsi alla legenda. Lettura/scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Specifica la posizione della legenda su un grafico. I valori non NaN delle proprietà X, Y, Width, Heigt sovrascrivono l'effetto di questa proprietà. Lettura/scrittura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Specifica la posizione della legenda su un grafico. I valori non NaN delle proprietà X, Y, Width, Heigt sovrascrivono l'effetto di questa proprietà. Lettura/scrittura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Restituisce il formato di una legenda. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Ottiene le voci della legenda. Solo lettura [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Restituisce:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)