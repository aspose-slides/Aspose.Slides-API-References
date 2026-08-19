---
title: IChartTitle
second_title: Aspose.Slides voor Java API Referentie
description: Stelt de eigenschappen van de diagramtitel voor.
type: docs
url: /nl/com.aspose.slides/icharttitle/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Stelt de eigenschappen van de diagramtitel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bepaalt of andere diagramonderdelen de titel mogen overlappen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bepaalt of andere diagramonderdelen de titel mogen overlappen. |
| [getFormat()](#getFormat--) | Retourneert de opvul-, lijn- en effectstijlen van een titel. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bepaalt of andere diagramonderdelen de titel mogen overlappen. Lees/schrijf boolean.

**Retourneert:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bepaalt of andere diagramonderdelen de titel mogen overlappen. Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retourneert de opvul-, lijn- en effectstijlen van een titel. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retourneert:**
[IFormat](../../com.aspose.slides/iformat)