---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Represents normal view properties.
type: docs
url: /sv/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Representerar egenskaper för normalvy. Normalvyn består av tre innehållsområden: själva bilden, ett sidoinnehållsområde och ett innehållsområde längst ner.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normal visningsläge. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normal visningsläge. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Anger om den vertikala delaren ska fästas i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Anger om den vertikala delaren ska fästas i ett minimerat tillstånd när sidoregionen är tillräckligt liten. |
| [getVerticalBarState()](#getVerticalBarState--) | Anger i vilket tillstånd den vertikala delarbalken ska visas. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Anger i vilket tillstånd den vertikala delarbalken ska visas. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Anger i vilket tillstånd den horisontella delarbalken ska visas. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Anger i vilket tillstånd den horisontella delarbalken ska visas. |
| [getPreferSingleView()](#getPreferSingleView--) | Anger om användaren föredrar att se ett enkel-innehållsområde som täcker hela fönstret i stället för den standardnormala vyn med tre innehållsområden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Anger om användaren föredrar att se ett enkel-innehållsområde som täcker hela fönstret i stället för den standardnormala vyn med tre innehållsområden. |
| [getRestoredLeft()](#getRestoredLeft--) | Detta element specificerar storleken på sidoinnehållsområdet i normal vyn när regionen har en variabel återställd storlek (varken minimerad eller maximiserad). |
| [getRestoredTop()](#getRestoredTop--) | Detta element specificerar storleken på det övre bildområdet i normal vyn när regionen har en variabel återställd storlek (varken minimerad eller maximiserad). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```


Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normal visningsläge. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```


Anger om programmet ska visa ikoner när outline-innehåll visas i någon av innehållsområdena i normal visningsläge. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```


Anger om den vertikala delaren ska fästas i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolean.

**Returnerar:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```


Anger om den vertikala delaren ska fästas i ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs/skriv boolean.

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


Anger om användaren föredrar att se ett enkel-innehållsområde som täcker hela fönstret i stället för den standardnormala vyn med tre innehållsområden. Om aktiverat kan programmet välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolean.

**Returnerar:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```


Anger om användaren föredrar att se ett enkel-innehållsområde som täcker hela fönstret i stället för den standardnormala vyn med tre innehållsområden. Om aktiverat kan programmet välja att visa ett av innehållsområdena i hela fönstret. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```


Detta element specificerar storleken på sidoinnehållsområdet i normal vyn när regionen har en variabel återställd storlek (varken minimerad eller maximiserad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```


Detta element specificerar storleken på det övre bildområdet i normal vyn när regionen har en variabel återställd storlek (varken minimerad eller maximiserad). Endast läsning [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returnerar:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)