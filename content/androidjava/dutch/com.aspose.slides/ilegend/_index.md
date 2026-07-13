---
title: ILegend
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de eigenschappen van de grafieklegende voor.
type: docs
url: /nl/com.aspose.slides/ilegend/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Stelt de eigenschappen van de grafieklegende voor.
## Methoden

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bepaalt of andere grafiekelementen de legende mogen overlappen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bepaalt of andere grafiekelementen de legende mogen overlappen. |
| [getPosition()](#getPosition--) | Bepaalt de positie van de legende op een grafiek. |
| [setPosition(int value)](#setPosition-int-) | Bepaalt de positie van de legende op een grafiek. |
| [getFormat()](#getFormat--) | Retourneert het formaat van een legende. |
| [getEntries()](#getEntries--) | Haalt legendavermeldingen op. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bepaalt of andere grafiekelementen de legende mogen overlappen. Lezen/schrijven boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bepaalt of andere grafiekelementen de legende mogen overlappen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Bepaalt de positie van de legende op een grafiek. Niet-NaN waarden van X, Y, Width, Heigt-eigenschappen hebben voorrang op het effect van deze eigenschap. Lezen/schrijven [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Bepaalt de positie van de legende op een grafiek. Niet-NaN waarden van X, Y, Width, Heigt-eigenschappen hebben voorrang op het effect van deze eigenschap. Lezen/schrijven [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retourneert het formaat van een legende. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Haalt legendavermeldingen op. Alleen-lezen [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returns:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)