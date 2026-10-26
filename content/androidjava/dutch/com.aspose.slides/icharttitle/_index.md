---
title: IChartTitle
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de eigenschappen van de grafiektitel voor.
type: docs
url: /nl/com.aspose.slides/icharttitle/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Stelt de eigenschappen van de grafiektitel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOverlay()](#getOverlay--) | Bepaalt of andere grafiekelementen de titel mogen overlappen. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Bepaalt of andere grafiekelementen de titel mogen overlappen. |
| [getFormat()](#getFormat--) | Retourneert de vul-, lijn- en effectstijlen van een titel. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Bepaalt of andere grafiekelementen de titel mogen overlappen. Lezen/schrijven boolean.

**Retour:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Bepaalt of andere grafiekelementen de titel mogen overlappen. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Retourneert de vul-, lijn- en effectstijlen van een titel. Alleen-lezen [IFormat](../../com.aspose.slides/iformat).

**Retour:**
[IFormat](../../com.aspose.slides/iformat)