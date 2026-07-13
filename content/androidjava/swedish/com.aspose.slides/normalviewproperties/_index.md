---
title: NormalViewProperties
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar egenskaper för normalvy.
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

Representerar egenskaper för normal vy. Den normala vyn består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett botteninnehållsområde.

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
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Anger huruvida applikationen ska visa ikoner vid visning av dispositionsinnehåll i någon av innehållsområdena i normal vy-läge. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Anger huruvida applikationen ska visa ikoner vid visning av dispositionsinnehåll i någon av innehållsområdena i normal vy-läge. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Anger huruvida den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Anger huruvida den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [getVerticalBarState()](#getVerticalBarState--) | Anger vilket tillstånd den vertikala delarbalken ska visas i. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Anger vilket tillstånd den vertikala delarbalken ska visas i. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Anger vilket tillstånd den horisontella delarbalken ska visas i. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Anger vilket tillstånd den horisontella delarbalken ska visas i. |
| [getPreferSingleView()](#getPreferSingleView--) | Anger huruvida användaren föredrar att se ett enskilt innehållsområde i hela fönstret istället för standardnormalvyn med tre innehållsområden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Anger huruvida användaren föredrar att se ett enskilt innehållsområde i hela fönstret istället för standardnormalvyn med tre innehållsområden. |
| [getRestoredLeft()](#getRestoredLeft--) | Detta element anger storleken på sidoinnehållsområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). |
| [getRestoredTop()](#getRestoredTop--) | Detta element anger storleken på det övre bildområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Anger huruvida applikationen ska visa ikoner vid visning av dispositionsinnehåll i någon av innehållsområdena i normal vy-läge. Läs/skriv boolesk.

**Returnerar:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Anger huruvida applikationen ska visa ikoner vid visning av dispositionsinnehåll i någon av innehållsområdena i normal vy-läge. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Anger huruvida den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolesk.

**Returnerar:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Anger huruvida den vertikala delaren ska fästa i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolesk.

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

Anger huruvida användaren föredrar att se ett enskilt innehållsområde i hela fönstret istället för standardnormalvyn med tre innehållsområden. Om aktiverad kan applikationen välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolesk.

**Returnerar:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Anger huruvida användaren föredrar att se ett enskilt innehållsområde i hela fönstret istället för standardnormalvyn med tre innehållsområden. Om aktiverad kan applikationen välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Detta element anger storleken på sidoinnehållsområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Detta element anger storleken på det övre bildområdet i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)