---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a hyperlink.
type: docs
url: /sv/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Representerar en hyperlänk.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getActionType()](#getActionType--) | Returnerar typen av HyperLinkEx:s åtgärd. |
| [getExternalUrl()](#getExternalUrl--) | Anger den externa URL:en. Om den här egenskapen blir icke-null blir egenskapen TargetSlide null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Representerar en hyperlänk som är inställd för den här delen utan att ta hänsyn till delens faktiska innehåll. |
| [getTargetSlide()](#getTargetSlide--) | Om HyperlinkEx pekar på en specifik bild returneras den bilden. |
| [getTargetFrame()](#getTargetFrame--) | Returnerar ramen inom förälderns HTML-ramverk för målet för den överordnade hyperlänken när en sådan finns. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returnerar ramen inom förälderns HTML-ramverk för målet för den överordnade hyperlänken när en sådan finns. |
| [getTooltip()](#getTooltip--) | Returnerar strängen som kan visas i ett användargränssnitt i samband med den överordnade hyperlänken. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returnerar strängen som kan visas i ett användargränssnitt i samband med den överordnade hyperlänken. |
| [getHistory()](#getHistory--) | Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den aktiveras. |
| [setHistory(boolean value)](#setHistory-boolean-) | Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den aktiveras. |
| [getHighlightClick()](#getHighlightClick--) | Avgör om hyperlänken ska markeras vid klick. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Avgör om hyperlänken ska markeras vid klick. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Avgör om ljudet ska stoppas vid hyperlänkens klick. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Avgör om ljudet ska stoppas vid hyperlänkens klick. |
| [getSound()](#getSound--) | Representerar det uppspelade ljudet för hyperlänken. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Representerar det uppspelade ljudet för hyperlänken. |
| [getColorSource()](#getColorSource--) | Representerar källan för hyperlänkens färg – antingen stilar eller delformat. |
| [setColorSource(int value)](#setColorSource-int-) | Representerar källan för hyperlänkens färg – antingen stilar eller delformat. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Avgör om de två Hyperlink-instanserna är lika. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Returnerar typen av HyperLinkEx:s åtgärd. Endast läsning [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Returnerar:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Anger den externa URL:en. Om den här egenskapen blir icke-null blir egenskapen TargetSlide null. Endast läsning String.

**Returnerar:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Representerar en hyperlänk som är inställd för den här delen utan att ta hänsyn till delens faktiska innehåll.

PowerPoint hanterar länkar och deras motsvarande text i en del på ett speciellt sätt. Det tillåter att skapa text för hyperlänken i form av en giltig URL, skild från länken's egentliga adress. I det här fallet, när du visar länken i redigeringsfönstret, kommer den att ändras så att den matchar textdelen. Denna egenskap representerar hyperlänkens ursprungliga värde.

**Returnerar:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Om HyperlinkEx pekar på en specifik bild returneras den bilden. Om egenskapen blir icke-null blir egenskapen ExternalUrl null. Endast läsning [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Returnerar ramen inom förälderns HTML-ramverk för målet för den överordnade hyperlänken när en sådan finns. Läs/skriv String.

**Returnerar:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Returnerar ramen inom förälderns HTML-ramverk för målet för den överordnade hyperlänken när en sådan finns. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Returnerar strängen som kan visas i ett användargränssnitt i samband med den överordnade hyperlänken. Läs/skriv String.

**Returnerar:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Returnerar strängen som kan visas i ett användargränssnitt i samband med den överordnade hyperlänken. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den aktiveras. Läs/skriv boolean.

**Returnerar:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Avgör om målet för den överordnade hyperlänken ska läggas till i en lista över visade hyperlänkar när den aktiveras. Läs/skriv boolean.

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


Avgör om ljudet ska stoppas vid hyperlänkens klick. Läs/skriv boolean.

**Returnerar:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Avgör om ljudet ska stoppas vid hyperlänkens klick. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
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
public abstract void setSound(IAudio value)
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
public abstract int getColorSource()
```


Representerar källan för hyperlänkens färg – antingen stilar eller delformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returnerar:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Representerar källan för hyperlänkens färg – antingen stilar eller delformat. Läs/skriv [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlinken att jämföra med den aktuella Hyperlinken. |

**Returnerar:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.