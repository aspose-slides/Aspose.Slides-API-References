---
title: ILegend
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le proprietà della leggenda dei grafici.
type: docs
url: /it/com.aspose.slides/ilegend/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Rappresenta le proprietà della leggenda del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina se altri elementi del grafico devono poter sovrapporsi alla leggenda. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se altri elementi del grafico devono poter sovrapporsi alla leggenda. |
| [getPosition()](#getPosition--) | Specifica la posizione della leggenda su un grafico. |
| [setPosition(int value)](#setPosition-int-) | Specifica la posizione della leggenda su un grafico. |
| [getFormat()](#getFormat--) | Restituisce il formato di una leggenda. |
| [getEntries()](#getEntries--) | Ottiene le voci della leggenda. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina se altri elementi del grafico devono poter sovrapporsi alla leggenda. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina se altri elementi del grafico devono poter sovrapporsi alla leggenda. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Specifica la posizione della leggenda su un grafico. I valori non NaN delle proprietà X, Y, Width, Heigt sovrascrivono l'effetto di questa proprietà. Lettura/scrittura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Specifica la posizione della leggenda su un grafico. I valori non NaN delle proprietà X, Y, Width, Heigt sovrascrivono l'effetto di questa proprietà. Lettura/scrittura [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Restituisce il formato di una leggenda. Solo lettura [IFormat](../../com.aspose.slides/iformat).

**Restituisce:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Ottiene le voci della leggenda. Solo lettura [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Restituisce:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)