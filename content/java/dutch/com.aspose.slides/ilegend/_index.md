---
title: ILegend
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de legenda-eigenschappen van grafieken voor.
type: docs
url: /nl/com.aspose.slides/ilegend/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Stelt de legenda-eigenschappen van de grafiek voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bepaalt of andere grafiekelementen de legenda mogen overlappen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bepaalt of andere grafiekelementen de legenda mogen overlappen. |
| [getPosition()](#getPosition--) | Specificeert de positie van de legenda op een grafiek. |
| [setPosition(int value)](#setPosition-int-) | Specificeert de positie van de legenda op een grafiek. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een legenda. |
| [getEntries()](#getEntries--) | Haalt legenda-items op. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bepaalt of andere grafiekelementen de legenda mogen overlappen. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bepaalt of andere grafiekelementen de legenda mogen overlappen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Specificeert de positie van de legenda op een grafiek. Niet-NaN waarden van X, Y, Width, Heigt eigenschapen overschrijven effect van deze eigenschap. Lezen/schrijven [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Retourneert:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Specificeert de positie van de legenda op een grafiek. Niet-NaN waarden van X, Y, Width, Heigt eigenschapen overschrijven effect van deze eigenschap. Lezen/schrijven [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retourneert het formaat van een legenda. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Haalt legenda-items op. Alleen-lezen [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Retourneert:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)