---
title: Hyperlink
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een hyperlink voor.
type: docs
url: /nl/com.aspose.slides/hyperlink/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Stelt een hyperlink voor.
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Maakt een instantie van een hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Maakt een instantie van een hyperlink die naar een specifieke dia wijst. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Retourneert een speciale "do nothing" hyperlink. |
| [getMedia()](#getMedia--) | Retourneert een speciale "play mediafile" hyperlink. |
| [getNextSlide()](#getNextSlide--) | Retourneert een hyperlink naar de volgende dia. |
| [getPreviousSlide()](#getPreviousSlide--) | Retourneert een hyperlink naar de vorige dia. |
| [getFirstSlide()](#getFirstSlide--) | Retourneert een hyperlink naar de eerste dia van de presentatie. |
| [getLastSlide()](#getLastSlide--) | Retourneert een hyperlink naar de laatste dia van de presentatie. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Retourneert een hyperlink naar de laatst bekeken dia. |
| [getEndShow()](#getEndShow--) | Retourneert een hyperlink die de show beëindigt. |
| [getActionType()](#getActionType--) | Retourneert het type van de Hyperlink-actie. |
| [getExternalUrl()](#getExternalUrl--) | Specificeert de externe URL. |
| [getTargetSlide()](#getTargetSlide--) | Als de Hyperlink naar een specifieke dia verwijst, retourneert deze dia. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte. |
| [getTargetFrame()](#getTargetFrame--) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink indien aanwezig. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink indien aanwezig. |
| [getTooltip()](#getTooltip--) | Retourneert de string die in een gebruikersinterface kan worden weergegeven als gekoppeld aan de bovenliggende hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Retourneert de string die in een gebruikersinterface kan worden weergegeven als gekoppeld aan de bovenliggende hyperlink. |
| [getHistory()](#getHistory--) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. |
| [getHighlightClick()](#getHighlightClick--) | Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. |
| [getSound()](#getSound--) | Stelt het afspelende geluid van de hyperlink voor. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Stelt het afspelende geluid van de hyperlink voor. |
| [getColorSource()](#getColorSource--) | Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-indeling. |
| [setColorSource(int value)](#setColorSource-int-) | Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-indeling. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bepaalt of de twee Hyperlink-instanties gelijk zijn. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Test twee hyperlinks op gelijkheid. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Test twee hyperlinks op ongelijkheid. |
| [hashCode()](#hashCode--) | Dient als een hash-functie voor een specifiek type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Maakt een instantie van een hyperlink.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | java.lang.String | Hyperlink-URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Maakt een instantie van een hyperlink die naar een specifieke dia wijst. Opmerking: de gemaakte hyperlink moet worden toegewezen aan een object uit dezelfde presentatie, anders wordt de link opgeslagen als NoAction.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Doeldia. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Maakt een instantie van een hyperlink met een andere hyperlink als bron, waarbij secundaire eigenschappen worden overschreven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Bronhyperlink |
| targetFrame | java.lang.String | Doelframe |
| tooltip | java.lang.String | Tooltip-tekst |
| history | boolean | Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. |
| stopSoundsOnClick | boolean | Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. |
| highlightClick | boolean | Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Retourneert een speciale "do nothing" hyperlink. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Retourneert een speciale "play mediafile" hyperlink. Wordt gebruikt in AudioFrame en VideoFrame. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Retourneert een hyperlink naar de volgende dia. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Retourneert een hyperlink naar de vorige dia. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Retourneert een hyperlink naar de eerste dia van de presentatie. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Retourneert een hyperlink naar de laatste dia van de presentatie. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Retourneert een hyperlink naar de laatst bekeken dia. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Retourneert een hyperlink die de show beëindigt. Alleen-lezen [Hyperlink](../../com.aspose.slides/hyperlink).

**Retourneert:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Retourneert het type van de Hyperlink-actie. Alleen-lezen [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Retourneert:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Specificeert de externe URL. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Als de Hyperlink naar een specifieke dia verwijst, retourneert deze dia. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Stelt een hyperlink voor die is ingesteld voor dit gedeelte, ongeacht de feitelijke inhoud van het gedeelte.

--------------------

PowerPoint gedraagt zich specifiek voor links en de bijbehorende tekst in een gedeelte. Het maakt het mogelijk om tekst voor de hyperlink te creëren in de vorm van een geldige URL, verschillend van het echte adres van de link. In dit geval wordt de link in het bewerkingsvenster aangepast om overeen te komen met de tekst. Deze eigenschap stelt de oorspronkelijke waarde van de hyperlink voor.

**Retourneert:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink indien aanwezig. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Retourneert het frame binnen de bovenliggende HTML-frameset voor het doel van de bovenliggende hyperlink indien aanwezig. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Retourneert de string die in een gebruikersinterface kan worden weergegeven als gekoppeld aan de bovenliggende hyperlink. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Retourneert de string die in een gebruikersinterface kan worden weergegeven als gekoppeld aan de bovenliggende hyperlink. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Bepaalt of het doel van de bovenliggende hyperlink moet worden toegevoegd aan een lijst van bekeken hyperlinks wanneer deze wordt aangeroepen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Bepaalt of de hyperlink moet worden gemarkeerd bij klikken. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Bepaalt of het geluid moet worden gestopt bij klikken op de hyperlink. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de hyperlink van de eerste vorm op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraheer het hyperlinkgeluid in een byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retourneert:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Stelt het afspelende geluid van de hyperlink voor. Lezen/Schrijven [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Haal de hyperlink van de eerste vorm op
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extraheer het hyperlinkgeluid in een byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-indeling. Lezen/Schrijven [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Retourneert:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Stelt de bron van de hyperlinkkleur voor - ofwel stijlen of gedeelte-indeling. Lezen/Schrijven [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bepaalt of de twee Hyperlink-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | De Hyperlink waarmee de huidige Hyperlink wordt vergeleken. |

**Retourneert:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Bepaalt of de twee Hyperlink-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | De Hyperlink waarmee de huidige Hyperlink wordt vergeleken. |

**Retourneert:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Test twee hyperlinks op gelijkheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Eerste hyperlink die getest wordt. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Tweede hyperlink die getest wordt. |

**Retourneert:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Test twee hyperlinks op ongelijkheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Eerste hyperlink die getest wordt. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Tweede hyperlink die getest wordt. |

**Retourneert:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als een hash-functie voor een specifiek type, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hash-tabel.

**Retourneert:**
int - Hash-code voor een URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject