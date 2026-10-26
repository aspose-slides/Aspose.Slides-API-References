---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Stelt de eigenschappen van de normale weergave voor.
type: docs
url: /nl/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Stelt de eigenschappen van de normale weergave voor. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zijgebied en een ondergebied.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Geeft aan of de applicatie pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de inhoudsgebieden van de normale weergavemodus. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Geeft aan of de applicatie pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de inhoudsgebieden van de normale weergavemodus. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. |
| [getVerticalBarState()](#getVerticalBarState--) | Geeft de staat aan waarin de verticale splitterbalk moet worden weergegeven. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Geeft de staat aan waarin de verticale splitterbalk moet worden weergegeven. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Geeft de staat aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Geeft de staat aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [getPreferSingleView()](#getPreferSingleView--) | Geeft aan of de gebruiker de voorkeur geeft aan een enkel inhoudsgebied over het volledige venster in plaats van de standaard normale weergave met drie inhoudsgebieden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Geeft aan of de gebruiker de voorkeur geeft aan een enkel inhoudsgebied over het volledige venster in plaats van de standaard normale weergave met drie inhoudsgebieden. |
| [getRestoredLeft()](#getRestoredLeft--) | Dit element specificeert de grootte van het zij-inhoudsgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). |
| [getRestoredTop()](#getRestoredTop--) | Dit element specificeert de grootte van het bovenste dia-gebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```


Geeft aan of de applicatie pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de inhoudsgebieden van de normale weergavemodus. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```


Geeft aan of de applicatie pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de inhoudsgebieden van de normale weergavemodus. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```


Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```


Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```


Geeft de staat aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zij-inhoudsgebied.

**Retourneert:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```


Geeft de staat aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zij-inhoudsgebied.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```


Geeft de staat aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het inhoudsgebied onder de dia.

**Retourneert:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```


Geeft de staat aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het inhoudsgebied onder de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```


Geeft aan of de gebruiker de voorkeur geeft aan een enkel inhoudsgebied over het volledige venster in plaats van de standaard normale weergave met drie inhoudsgebieden. Indien ingeschakeld kan de applicatie kiezen om een van de inhoudsgebieden in het volledige venster weer te geven. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```


Geeft aan of de gebruiker de voorkeur geeft aan een enkel inhoudsgebied over het volledige venster in plaats van de standaard normale weergave met drie inhoudsgebieden. Indien ingeschakeld kan de applicatie kiezen om een van de inhoudsgebieden in het volledige venster weer te geven. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```


Dit element specificeert de grootte van het zij-inhoudsgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retourneert:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```


Dit element specificeert de grootte van het bovenste dia-gebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retourneert:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)