---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Representerar en hyperlänk.
type: docs
url: /sv/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Representerar en hyperlänk.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getActionType()](#getActionType--) | Returnerar typ av HyperLinkEx:s åtgärd. |
| [getExternalUrl()](#getExternalUrl--) | Anger den externa URL:en. Om den här egenskapen blir icke-null blir egenskapen TargetSlide null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representerar en hyperlänk som är inställd för den här delen utan hänsyn till det faktiska innehållet i delen. |
| [getTargetSlide()](#getTargetSlide--) | Om HyperlinkEx pekar på en specifik bild returneras den här bilden. |
| [getTargetFrame()](#getTargetFrame--) | Returnerar ramen inom förälderns HTML-ramuppsättning för målet för den överordnade hyperlänken när en sådan finns. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returnerar ramen inom förälderns HTML-ramuppsättning för målet för den överordnade hyperlänken när en sådan finns. |
| [getTooltip()](#getTooltip--) | Returnerar strängen som kan visas i ett användargränssnitt som associerad med den överordnade hyperlänken. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returnerar strängen som kan visas i ett användargränssnitt som associerad med den överordnade hyperlänken. |
| [getHistory()](#getHistory--) | Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. |
| [setHistory(boolean value)](#setHistory-boolean-) | Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. |
| [getHighlightClick()](#getHighlightClick--) | Avgör om hyperlänken ska markeras vid klick. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Avgör om hyperlänken ska markeras vid klick. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Avgör om ljudet ska stoppas vid hyperlänk-klick. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Avgör om ljudet ska stoppas vid hyperlänk-klick. |
| [getSound()](#getSound--) | Representerar den spelande ljudet för hyperlänken. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representerar den spelande ljudet för hyperlänken. |
| [getColorSource()](#getColorSource--) | Representerar källan för hyperlänksfärg – antingen stilar eller portionsformat. |
| [setColorSource(int value)](#setColorSource-int-) | Representerar källan för hyperlänksfärg – antingen stilar eller portionsformat. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Avgör om de två Hyperlink-instanserna är lika. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Returnerar typ av HyperLinkEx:s åtgärd. Skrivskyddad [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returnerar:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Anger den externa URL:en. Om den här egenskapen blir icke-null blir egenskapen TargetSlide null. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Representerar en hyperlänk som är inställd för den här delen utan hänsyn till det faktiska innehållet i delen.

--------------------

PowerPoint beter sig specifikt för länkar och deras motsvarande text i en del. Det tillåter att skapa text för hyperlänken i form av en giltig URL, som skiljer sig från den faktiska adressen för länken. I detta fall, när du visar länken i redigeringsfönstret, kommer den att ändras för att matcha textdelen. Den här egenskapen representerar hyperlänkens ursprungliga värde.

**Returnerar:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Om HyperlinkEx pekar på en specifik bild returneras den här bilden. Om egenskapen blir icke-null blir egenskapen ExternalUrl null. Skrivskyddad [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Returnerar ramen inom förälderns HTML-ramuppsättning för målet för den överordnade hyperlänken när en sådan finns. Läs/skriv String.

**Returnerar:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Returnerar ramen inom förälderns HTML-ramuppsättning för målet för den överordnade hyperlänken när en sådan finns. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Returnerar strängen som kan visas i ett användargränssnitt som associerad med den överordnade hyperlänken. Läs/skriv String.

**Returnerar:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Returnerar strängen som kan visas i ett användargränssnitt som associerad med den överordnade hyperlänken. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. Läs/skriv boolean.

**Returnerar:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den anropas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

Avgör om hyperlänken ska markeras vid klick. Läs/skriv boolean.

**Returnerar:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

Avgör om hyperlänken ska markeras vid klick. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

Avgör om ljudet ska stoppas vid hyperlänk-klick. Läs/skriv boolean.

**Returnerar:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Avgör om ljudet ska stoppas vid hyperlänk-klick. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Representerar den spelande ljudet för hyperlänken. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
> 
>      // Hämta den första formens hyperlänk
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahera hyperlänkens ljud i en byte-array
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
public abstract void setSound(IAudio value)
```

Representerar den spelande ljudet för hyperlänken. Läs/skriv [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Hämta den första formens hyperlänk
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extrahera hyperlänkens ljud i en byte-array
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
public abstract int getColorSource()
```

Representerar källan för hyperlänksfärg – antingen stilar eller portionsformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returnerar:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Representerar källan för hyperlänksfärg – antingen stilar eller portionsformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

Avgör om de två Hyperlink-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink att jämföra med den aktuella Hyperlink. |

**Returnerar:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.