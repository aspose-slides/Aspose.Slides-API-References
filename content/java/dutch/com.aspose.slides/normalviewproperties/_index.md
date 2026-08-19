---
title: NormalViewProperties
second_title: Aspose.Slides voor Java API-referentie
description: Representeert normale weergave-eigenschappen.
type: docs
url: /nl/com.aspose.slides/normalviewproperties/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Representeert normale weergave-eigenschappen. De normale weergave bestaat uit drie inhoudsgebieden: de dia zelf, een zij-inhoudsgebied en een onder-inhoudsgebied.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instantieer een presentatie-object dat een presentatie-bestand vertegenwoordigt
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
## Methoden

| Method | Description |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Geeft aan of de applicatie pictogrammen moet weergeven bij het tonen van omtrekinhoud in een van de inhoudsgebieden van de normale weergavemodus. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Geeft aan of de applicatie pictogrammen moet weergeven bij het tonen van omtrekinhoud in een van de inhoudsgebieden van de normale weergavemodus. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Geeft aan of de verticale splitter moet vastklampen aan een geminimaliseerde status wanneer het zijgebied voldoende klein is. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Geeft aan of de verticale splitter moet vastklampen aan een geminimaliseerde status wanneer het zijgebied voldoende klein is. |
| [getVerticalBarState()](#getVerticalBarState--) | Geeft de status aan waarin de verticale splitterbalk moet worden weergegeven. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Geeft de status aan waarin de verticale splitterbalk moet worden weergegeven. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Geeft de status aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Geeft de status aan waarin de horizontale splitterbalk moet worden weergegeven. |
| [getPreferSingleView()](#getPreferSingleView--) | Geeft aan of de gebruiker een enkel-inhoudsgebied in een volledig venster verkiest boven de standaard normale weergave met drie inhoudsgebieden. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Geeft aan of de gebruiker een enkel-inhoudsgebied in een volledig venster verkiest boven de standaard normale weergave met drie inhoudsgebieden. |
| [getRestoredLeft()](#getRestoredLeft--) | Dit element specificeert de grootte van het zij-inhoudsgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). |
| [getRestoredTop()](#getRestoredTop--) | Dit element specificeert de grootte van het bovenste dia-gebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Geeft aan of de applicatie pictogrammen moet weergeven bij het tonen van omtrekinhoud in een van de inhoudsgebieden van de normale weergavemodus. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Geeft aan of de applicatie pictogrammen moet weergeven bij het tonen van omtrekinhoud in een van de inhoudsgebieden van de normale weergavemodus. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Geeft aan of de verticale splitter moet vastklampen aan een geminimaliseerde status wanneer het zijgebied voldoende klein is. Lezen/schrijven boolean.

**Retour:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Geeft aan of de verticale splitter moet vastklampen aan een geminimaliseerde status wanneer het zijgebied voldoende klein is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Geeft de status aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zij-inhoudsgebied.

**Retour:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Geeft de status aan waarin de verticale splitterbalk moet worden weergegeven. Een verticale splitterbalk scheidt de dia van het zij-inhoudsgebied.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Geeft de status aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het inhoudsgebied onder de dia.

**Retour:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Geeft de status aan waarin de horizontale splitterbalk moet worden weergegeven. Een horizontale splitterbalk scheidt de dia van het inhoudsgebied onder de dia.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Geeft aan of de gebruiker een enkel-inhoudsgebied in een volledig venster verkiest boven de standaard normale weergave met drie inhoudsgebieden. Indien ingeschakeld, kan de applicatie een van de inhoudsgebieden in het volledige venster weergeven. Lezen/schrijven boolean.

**Retour:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Geeft aan of de gebruiker een enkel-inhoudsgebied in een volledig venster verkiest boven de standaard normale weergave met drie inhoudsgebieden. Indien ingeschakeld, kan de applicatie een van de inhoudsgebieden in het volledige venster weergeven. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Dit element specificeert de grootte van het zij-inhoudsgebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Dit element specificeert de grootte van het bovenste dia-gebied van de normale weergave, wanneer het gebied een variabele herstelde grootte heeft (niet geminimaliseerd of gemaximaliseerd). Alleen lezen [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retour:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)