---
title: Hyperlink
second_title: Aspose.Slides för Java API-referens
description: Representerar en hyperlänk.
type: docs
url: /sv/com.aspose.slides/hyperlink/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Representerar en hyperlänk.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Skapar en instans av en hyperlänk. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Skapar en instans av en hyperlänk som pekar på en specifik bild. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Skapar en instans av en hyperlänk med en annan hyperlänk som källa och åsidosätter sekundära egenskaper. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Returnerar en speciell "do nothing"-hyperlänk. |
| [getMedia()](#getMedia--) | Returnerar en speciell "play mediafile"-hyperlänk. |
| [getNextSlide()](#getNextSlide--) | Returnerar en hyperlänk till nästa bild. |
| [getPreviousSlide()](#getPreviousSlide--) | Returnerar en hyperlänk till föregående bild. |
| [getFirstSlide()](#getFirstSlide--) | Returnerar en hyperlänk till den första bilden i presentationen. |
| [getLastSlide()](#getLastSlide--) | Returnerar en hyperlänk till den sista bilden i presentationen. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Returnerar en hyperlänk till den senast visade bilden. |
| [getEndShow()](#getEndShow--) | Returnerar en hyperlänk som avslutar föreställningen. |
| [getActionType()](#getActionType--) | Returnerar typen av Hyperlink's åtgärd. |
| [getExternalUrl()](#getExternalUrl--) | Anger den externa URL:en. |
| [getTargetSlide()](#getTargetSlide--) | Om Hyperlink pekar på en specifik bild returneras den bilden. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representerar en hyperlänk som är inställd för den här delen utan hänsyn till den faktiska delen. |
| [getTargetFrame()](#getTargetFrame--) | Returnerar ramen inom den överordnade HTML-frameseten för målet när en sådan finns. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returnerar ramen inom den överordnade HTML-frameseten för målet när en sådan finns. |
| [getTooltip()](#getTooltip--) | Returnerar strängen som kan visas i ett användargränssnitt som är associerad med den överordnade hyperlänken. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returnerar strängen som kan visas i ett användargränssnitt som är associerad med den överordnade hyperlänken. |
| [getHistory()](#getHistory--) | Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. |
| [setHistory(boolean value)](#setHistory-boolean-) | Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. |
| [getHighlightClick()](#getHighlightClick--) | Bestämmer om hyperlänken ska markeras vid klick. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Bestämmer om hyperlänken ska markeras vid klick. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Bestämmer om ljudet ska stoppas vid hyperlänksklick. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Bestämmer om ljudet ska stoppas vid hyperlänksklick. |
| [getSound()](#getSound--) | Representerar det uppspelade ljudet för hyperlänken. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representerar det uppspelade ljudet för hyperlänken. |
| [getColorSource()](#getColorSource--) | Representerar källan till hyperlänkens färg – antingen stil eller delformat. |
| [setColorSource(int value)](#setColorSource-int-) | Representerar källan till hyperlänkens färg – antingen stil eller delformat. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om de två Hyperlink-instanserna är lika. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Bestämmer om de två Hyperlink-instanserna är lika. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testar två hyperlänkar för likhet. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Testar två hyperlänkar för olikhet. |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hashtabell. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Skapar en instans av en hyperlänk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | java.lang.String | Hyperlänkens URL. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Skapar en instans av en hyperlänk som pekar på en specifik bild. Obs: den skapade hyperlänken bör tilldelas ett objekt från samma presentation, annars sparas länken som NoAction.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Målbild. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Skapar en instans av en hyperlänk med en annan hyperlänk som källa och åsidosätter sekundära egenskaper.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Källhyperlänk |
| targetFrame | java.lang.String | Målrama |
| tooltip | java.lang.String | Verktygstippstext |
| history | boolean | Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. |
| stopSoundsOnClick | boolean | Bestämmer om ljudet ska stoppas vid hyperlänksklick. |
| highlightClick | boolean | Bestämmer om hyperlänken ska markeras vid klick. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Returnerar en speciell "do nothing"-hyperlänk. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Returnerar en speciell "play mediafile"-hyperlänk. Används i AudioFrame och VideoFrame. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Returnerar en hyperlänk till nästa bild. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Returnerar en hyperlänk till föregående bild. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Returnerar en hyperlänk till den första bilden i presentationen. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Returnerar en hyperlänk till den sista bilden i presentationen. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Returnerar en hyperlänk till den senast visade bilden. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Returnerar en hyperlänk som avslutar föreställningen. Skrivskyddad [Hyperlink](../../com.aspose.slides/hyperlink).

**Returnerar:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

Returnerar typen av Hyperlink's åtgärd. Skrivskyddad [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returnerar:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Anger den externa URL:en. Skrivskyddad String.

**Returnerar:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Om Hyperlink pekar på en specifik bild returneras den bilden. Skrivskyddad [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Representerar en hyperlänk som är inställd för den här delen utan hänsyn till den faktiska delen.

PowerPoint beter sig specifikt för länkar och deras motsvarande text i en del. Det tillåter att skapa text för hyperlänken i form av en giltig URL, skild från lånets verkliga adress. I detta fall, när du visar länken i redigeringsfönstret, kommer den att ändras för att matcha textdelen. Denna egenskap representerar hyperlänkens ursprungliga värde.

**Returnerar:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Returnerar ramen inom den överordnade HTML-frameseten för målet när en sådan finns. Läs/skriv String.

**Returnerar:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Returnerar ramen inom den överordnade HTML-frameseten för målet när en sådan finns. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Returnerar strängen som kan visas i ett användargränssnitt som är associerad med den överordnade hyperlänken. Läs/skriv String.

**Returnerar:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Returnerar strängen som kan visas i ett användargränssnitt som är associerad med den överordnade hyperlänken. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. Läs/skriv boolean.

**Returnerar:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Bestämmer om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Bestämmer om hyperlänken ska markeras vid klick. Läs/skriv boolean.

**Returnerar:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Bestämmer om hyperlänken ska markeras vid klick. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Bestämmer om ljudet ska stoppas vid hyperlänksklick. Läs/skriv boolean.

**Returnerar:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Bestämmer om ljudet ska stoppas vid hyperlänksklick. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Representerar det uppspelade ljudet för hyperlänken. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämta hyperlänken för den första formen
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahera hyperlänkens ljud i byte-array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Representerar det uppspelade ljudet för hyperlänken. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämta hyperlänken för den första formen
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahera hyperlänkens ljud i byte-array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Representerar källan till hyperlänkens färg – antingen stil eller delformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returnerar:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Representerar källan till hyperlänkens färg – antingen stil eller delformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestämmer om de två Hyperlink-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlinken att jämföra med den aktuella Hyperlinken. |

**Returnerar:**
boolean - **true** om den angivna Hyperlinken är lika med den aktuella Hyperlinken; annars **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Bestämmer om de två Hyperlink-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlinken att jämföra med den aktuella Hyperlinken. |

**Returnerar:**
boolean - **true** om den angivna Hyperlinken är lika med den aktuella Hyperlinken; annars **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Testar två hyperlänkar för likhet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Första hyperlänken som ska testas. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Andra hyperlänken som ska testas. |

**Returnerar:**
boolean - **true** om hyperlänkarna är lika.

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Testar två hyperlänkar för olikhet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Första hyperlänken som ska testas. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Andra hyperlänken som ska testas. |

**Returnerar:**
boolean - **false** om hyperlänkarna är lika.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ, lämplig för användning i hash-algoritmer och datastrukturer som en hashtabell.

**Returnerar:**
int - Hash-kod för en URL.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject