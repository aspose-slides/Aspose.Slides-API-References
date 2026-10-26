---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Alternativ för att extrahera HTML från Pptx-texten.
type: docs
url: /sv/com.aspose.slides/texttohtmlconversionoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Alternativ för att extrahera HTML från Pptx-texten.

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returnerar eller anger värde som indikerar om Clipboard-rubriker ska läggas till. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returnerar eller anger värde som indikerar om Clipboard-rubriker ska läggas till. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returnerar eller anger ärftligt djup för textegenskaper. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returnerar eller anger ärftligt djup för textegenskaper. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returnerar eller anger ett callback-objekt som styr hur ett externt objekt ska lagras. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returnerar eller anger ett callback-objekt som styr hur ett externt objekt ska lagras. |
| [getEncodingName()](#getEncodingName--) | Returnerar eller anger HTML-kodningsnamn. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returnerar eller anger HTML-kodningsnamn. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Returnerar eller anger värde som indikerar om Clipboard-rubriker ska läggas till. Läs/skriva boolean.

**Returnerar:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Returnerar eller anger värde som indikerar om Clipboard-rubriker ska läggas till. Läs/skriva boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Returnerar eller anger ärftligt djup för textegenskaper. Läs/skriva [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Returnerar:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Returnerar eller anger ärftligt djup för textegenskaper. Läs/skriva [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Returnerar eller anger ett callback-objekt som styr hur ett externt objekt ska lagras. Läs/skriva [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returnerar:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Returnerar eller anger ett callback-objekt som styr hur ett externt objekt ska lagras. Läs/skriva [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Returnerar eller anger HTML-kodningsnamn. Detta värde kommer att sparas i den genererade HTML-filen, men det är upp till anroparen att säkerställa att filen sparas i denna kodning. Läs/skriva String.

**Returnerar:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Returnerar eller anger HTML-kodningsnamn. Detta värde kommer att sparas i den genererade HTML-filen, men det är upp till anroparen att säkerställa att filen sparas i denna kodning. Läs/skriva String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |