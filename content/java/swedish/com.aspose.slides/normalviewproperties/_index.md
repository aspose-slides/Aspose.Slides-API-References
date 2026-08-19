---
title: NormalViewProperties
second_title: Aspose.Slides för Java API-referens
description: Representerar normalvy-egenskaper.
type: docs
url: /sv/com.aspose.slides/normalviewproperties/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Representerar normalvy-egenskaper. Normalvyn består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett botteninnehållsområde.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instansiera ett presentationsobjekt som representerar en presentationsfil
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Anger om applikationen ska visa ikoner när den visar dispositionsinnehåll i något av innehållsområdena i normalvy-läget. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Anger om applikationen ska visa ikoner när den visar dispositionsinnehåll i något av innehållsområdena i normalvy-läget. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Anger om den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Anger om den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [getVerticalBarState()](#getVerticalBarState--) | Anger vilket tillstånd den vertikala delarbalken ska visas i. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Anger vilket tillstånd den vertikala delarbalken ska visas i. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Anger vilket tillstånd den horisontella delarbalken ska visas i. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Anger vilket tillstånd den horisontella delarbalken ska visas i. |
| [getPreferSingleView()](#getPreferSingleView--) | Anger om användaren föredrar att se ett helfönster enskilt innehållsområde i stället för standardnormalvyn med tre innehållsområden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Anger om användaren föredrar att se ett helfönster enskilt innehållsområde i stället för standardnormalvyn med tre innehållsområden. |
| [getRestoredLeft()](#getRestoredLeft--) | Detta element specificerar storleken på sidoinnehållsområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maksimerad). |
| [getRestoredTop()](#getRestoredTop--) | Detta element specificerar storleken på det övre bildområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maksimerad). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Anger om applikationen ska visa ikoner när den visar dispositionsinnehåll i något av innehållsområdena i normalvy-läget. Läs/skriv boolesk.

**Returnerar:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Anger om applikationen ska visa ikoner när den visar dispositionsinnehåll i något av innehållsområdena i normalvy-läget. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Anger om den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolesk.

**Returnerar:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Anger om den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Anger vilket tillstånd den vertikala delarbalken ska visas i. En vertikal delarbalk separerar bilden från sidoinnehållsområdet.

**Returnerar:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Anger vilket tillstånd den vertikala delarbalken ska visas i. En vertikal delarbalk separerar bilden från sidoinnehållsområdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Anger vilket tillstånd den horisontella delarbalken ska visas i. En horisontell delarbalk separerar bilden från innehållsområdet under bilden.

**Returnerar:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Anger vilket tillstånd den horisontella delarbalken ska visas i. En horisontell delarbalk separerar bilden från innehållsområdet under bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Anger om användaren föredrar att se ett helfönster enskilt innehållsområde i stället för standardnormalvyn med tre innehållsområden. Om aktiverad kan applikationen välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolesk.

**Returnerar:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Anger om användaren föredrar att se ett helfönster enskilt innehållsområde i stället för standardnormalvyn med tre innehållsområden. Om aktiverad kan applikationen välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Detta element specificerar storleken på sidoinnehållsområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maksimerad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Detta element specificerar storleken på det övre bildområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maksimerad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)