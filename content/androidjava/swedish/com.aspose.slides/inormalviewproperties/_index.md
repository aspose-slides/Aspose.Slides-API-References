---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /sv/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Representerar egenskaper för normal vy. Den normala vyn består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett botteninnehållsområde.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normalt visningsläge. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normalt visningsläge. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Anger om den vertikala delaren ska fästa i ett minimerat läge när sidområdet är tillräckligt litet. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Anger om den vertikala delaren ska fästa i ett minimerat läge när sidområdet är tillräckligt litet. |
| [getVerticalBarState()](#getVerticalBarState--) | Anger i vilket tillstånd den vertikala delarbalken ska visas. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Anger i vilket tillstånd den vertikala delarbalken ska visas. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Anger i vilket tillstånd den horisontella delarbalken ska visas. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Anger i vilket tillstånd den horisontella delarbalken ska visas. |
| [getPreferSingleView()](#getPreferSingleView--) | Anger om användaren föredrar att se ett enkelt innehållsområde i helfönster istället för den standardnormala vyn med tre innehållsområden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Anger om användaren föredrar att se ett enkelt innehållsområde i helfönster istället för den standardnormala vyn med tre innehållsområden. |
| [getRestoredLeft()](#getRestoredLeft--) | Detta element anger storleken på sidoinnehållsområdet i den normala vyn när området har en variabel återställd storlek (varken minimerad eller maximerad). |
| [getRestoredTop()](#getRestoredTop--) | Detta element anger storleken på det övre bildområdet i den normala vyn när området har en variabel återställd storlek (varken minimerad eller maximerad). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normalt visningsläge. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normalt visningsläge. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Anger om den vertikala delaren ska fästa i ett minimerat läge när sidområdet är tillräckligt litet. Läs/skriv boolean.

**Returnerar:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Anger om den vertikala delaren ska fästa i ett minimerat läge när sidområdet är tillräckligt litet. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Anger i vilket tillstånd den vertikala delarbalken ska visas. En vertikal delarbalk separerar bilden från sidoinnehållsområdet.

**Returnerar:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Anger i vilket tillstånd den vertikala delarbalken ska visas. En vertikal delarbalk separerar bilden från sidoinnehållsområdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Anger i vilket tillstånd den horisontella delarbalken ska visas. En horisontell delarbalk separerar bilden från innehållsområdet under bilden.

**Returnerar:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Anger i vilket tillstånd den horisontella delarbalken ska visas. En horisontell delarbalk separerar bilden från innehållsområdet under bilden.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Anger om användaren föredrar att se ett enkelt innehållsområde i helfönster istället för den standardnormala vyn med tre innehållsområden. Om aktiverad kan programmet välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolean.

**Returnerar:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Anger om användaren föredrar att se ett enkelt innehållsområde i helfönster istället för den standardnormala vyn med tre innehållsområden. Om aktiverad kan programmet välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Detta element anger storleken på sidoinnehållsområdet i den normala vyn när området har en variabel återställd storlek (varken minimerad eller maximerad). Endast läs [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Detta element anger storleken på det övre bildområdet i den normala vyn när området har en variabel återställd storlek (varken minimerad eller maximerad). Endast läs [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)