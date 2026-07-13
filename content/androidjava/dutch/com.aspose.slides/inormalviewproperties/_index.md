---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt de eigenschappen van de normale weergave voor.
type: docs
url: /nl/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Stelt de eigenschappen van de normale weergave voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Geeft aan of de toepassing pictogrammen moet weergeven bij het weergeven van omtrekinhoud in een van de contentregio's van de normale weergavemodus. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Geeft aan of de toepassing pictogrammen moet weergeven bij het weergeven van omtrekinhoud in een van de contentregio's van de normale weergavemodus. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Geeft aan of de verticale splitter naar een geminimaliseerde toestand moet gaan wanneer de zijregion voldoende klein is. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Geeft aan of de verticale splitter naar een geminimaliseerde toestand moet gaan wanneer de zijregion voldoende klein is. |
| [getVerticalBarState()](#getVerticalBarState--) | Geeft de toestand aan waarin de verticale splitstreep moet worden weergegeven. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Geeft de toestand aan waarin de verticale splitstreep moet worden weergegeven. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Geeft de toestand aan waarin de horizontale splitstreep moet worden weergegeven. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Geeft de toestand aan waarin de horizontale splitstreep moet worden weergegeven. |
| [getPreferSingleView()](#getPreferSingleView--) | Geeft aan of de gebruiker de voorkeur geeft aan een volledig-venster enkel-contentregio boven de standaard normale weergave met drie contentregio's. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Geeft aan of de gebruiker de voorkeur geeft aan een volledig-venster enkel-contentregio boven de standaard normale weergave met drie contentregio's. |
| [getRestoredLeft()](#getRestoredLeft--) | Dit element specificeert de grootte van de zijcontentregio van de normale weergave, wanneer de regio een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). |
| [getRestoredTop()](#getRestoredTop--) | Dit element specificeert de grootte van de bovenste diaregio van de normale weergave, wanneer de regio een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Geeft aan of de toepassing pictogrammen moet weergeven bij het weergeven van omtrekinhoud in een van de contentregio's van de normale weergavemodus. Lezen/schrijven boolean.

**Retour:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Geeft aan of de toepassing pictogrammen moet weergeven bij het weergeven van omtrekinhoud in een van de contentregio's van de normale weergavemodus. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Geeft aan of de verticale splitter naar een geminimaliseerde toestand moet gaan wanneer de zijregion voldoende klein is. Lezen/schrijven boolean.

**Retour:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Geeft aan of de verticale splitter naar een geminimaliseerde toestand moet gaan wanneer de zijregion voldoende klein is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Geeft de toestand aan waarin de verticale splitstreep moet worden weergegeven. Een verticale splitstreep scheidt de dia van de zijcontentregio.

**Retour:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Geeft de toestand aan waarin de verticale splitstreep moet worden weergegeven. Een verticale splitstreep scheidt de dia van de zijcontentregio.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Geeft de toestand aan waarin de horizontale splitstreep moet worden weergegeven. Een horizontale splitstreep scheidt de dia van de contentregio onder de dia.

**Retour:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Geeft de toestand aan waarin de horizontale splitstreep moet worden weergegeven. Een horizontale splitstreep scheidt de dia van de contentregio onder de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Geeft aan of de gebruiker de voorkeur geeft aan een volledig-venster enkel-contentregio boven de standaard normale weergave met drie contentregio's. Indien ingeschakeld, kan de toepassing kiezen om een van de contentregio's in het volledige venster weer te geven. Lezen/schrijven boolean.

**Retour:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Geeft aan of de gebruiker de voorkeur geeft aan een volledig-venster enkel-contentregio boven de standaard normale weergave met drie contentregio's. Indien ingeschakeld, kan de toepassing kiezen om een van de contentregio's in het volledige venster weer te geven. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Dit element specificeert de grootte van de zijcontentregio van de normale weergave, wanneer de regio een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Dit element specificeert de grootte van de bovenste diaregio van de normale weergave, wanneer de regio een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)