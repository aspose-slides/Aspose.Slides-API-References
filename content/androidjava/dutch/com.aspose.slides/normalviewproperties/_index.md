---
title: NormalViewProperties
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt normale weergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/normalviewproperties/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Vertegenwoordigt normale weergave-eigenschappen. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zijinhoudsgebied en een onderste inhoudsgebied.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Maak een presentatie-object aan dat een presentatie-bestand vertegenwoordigt
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

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Geeft aan of de toepassing pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de contentgebieden van de normale weergavemodus. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Geeft aan of de toepassing pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de contentgebieden van de normale weergavemodus. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. |
| [getVerticalBarState()](#getVerticalBarState--) | Geeft de toestand aan waarin de verticale splitterbalk moet worden weergegeven. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Geeft de toestand aan waarin de verticale splitterbalk moet worden weergegeven. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Geeft de toestand aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Geeft de toestand aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [getPreferSingleView()](#getPreferSingleView--) | Geeft aan of de gebruiker de voorkeur geeft aan een enkel contentgebied over het volledige scherm in plaats van de standaard normale weergave met drie contentgebieden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Geeft aan of de gebruiker de voorkeur geeft aan een enkel contentgebied over het volledige scherm in plaats van de standaard normale weergave met drie contentgebieden. |
| [getRestoredLeft()](#getRestoredLeft--) | Dit element specificeert de afmetingen van het zijcontentgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). |
| [getRestoredTop()](#getRestoredTop--) | Dit element specificeert de afmetingen van het bovenste schuifgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Geeft aan of de toepassing pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de contentgebieden van de normale weergavemodus. Lezen/Schrijven boolean.

**Retour:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Geeft aan of de toepassing pictogrammen moet tonen bij het weergeven van outline-inhoud in een van de contentgebieden van de normale weergavemodus. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. Lezen/Schrijven boolean.

**Retour:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Geeft aan of de verticale splitter moet vastklikken in een geminimaliseerde toestand wanneer het zijgebied voldoende klein is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Geeft de toestand aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zijcontentgebied.

**Retour:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Geeft de toestand aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zijcontentgebied.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Geeft de toestand aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het contentgebied onder de dia.

**Retour:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Geeft de toestand aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het contentgebied onder de dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Geeft aan of de gebruiker de voorkeur geeft aan een enkel contentgebied over het volledige scherm in plaats van de standaard normale weergave met drie contentgebieden. Indien ingeschakeld, kan de toepassing kiezen om een van de contentgebieden over het volledige venster weer te geven. Lezen/Schrijven boolean.

**Retour:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Geeft aan of de gebruiker de voorkeur geeft aan een enkel contentgebied over het volledige scherm in plaats van de standaard normale weergave met drie contentgebieden. Indien ingeschakeld, kan de toepassing kiezen om een van de contentgebieden over het volledige venster weer te geven. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Dit element specificeert de afmetingen van het zijcontentgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). Alleen-lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Dit element specificeert de afmetingen van het bovenste schuifgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (noch geminimaliseerd, noch gemaximaliseerd). Alleen-lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)