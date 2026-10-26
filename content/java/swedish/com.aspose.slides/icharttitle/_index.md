---
title: IChartTitle
second_title: Aspose.Slides för Java API-referens
description: Representerar egenskaper för diagramtitel.
type: docs
url: /sv/com.aspose.slides/icharttitle/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Representerar egenskaper för diagramtitel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOverlay()](#getOverlay--) | Avgör om andra diagramelement ska tillåtas överlappa titeln. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Avgör om andra diagramelement ska tillåtas överlappa titeln. |
| [getFormat()](#getFormat--) | Returnerar fyllnings-, linje- och effektstilar för en titel. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Avgör om andra diagramelement ska tillåtas överlappa titeln. Läs/skriv boolean.

**Returnerar:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Avgör om andra diagramelement ska tillåtas överlappa titeln. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Returnerar fyllnings-, linje- och effektstilar för en titel. Skrivskyddad [IFormat](../../com.aspose.slides/iformat).

**Returnerar:**
[IFormat](../../com.aspose.slides/iformat)