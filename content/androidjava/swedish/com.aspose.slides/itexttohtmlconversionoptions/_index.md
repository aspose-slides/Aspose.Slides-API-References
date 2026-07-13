---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Alternativ för att extrahera HTML från Pptx-texten.
type: docs
url: /sv/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Alternativ för att extrahera HTML från Pptx-texten.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returnerar eller sätter värde som indikerar om Clipboard-rubriker ska läggas till. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returnerar eller sätter värde som indikerar om Clipboard-rubriker ska läggas till. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returnerar eller sätter ärvande djup för textegenskaper. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returnerar eller sätter ärvande djup för textegenskaper. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returnerar eller sätter ett återuppringningsobjekt som styr hur externt objekt kommer att lagras. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returnerar eller sätter ett återuppringningsobjekt som styr hur externt objekt kommer att lagras. |
| [getEncodingName()](#getEncodingName--) | Returnerar eller sätter HTML-kodningsnamn. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returnerar eller sätter HTML-kodningsnamn. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Returnerar eller sätter värde som indikerar om Clipboard-rubriker ska läggas till. Läs/skriv boolean.

**Returnerar:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Returnerar eller sätter värde som indikerar om Clipboard-rubriker ska läggas till. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Returnerar eller sätter ärvande djup för textegenskaper. Läs/skriv [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Returnerar:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Returnerar eller sätter ärvande djup för textegenskaper. Läs/skriv [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Returnerar eller sätter ett återuppringningsobjekt som styr hur externt objekt kommer att lagras. Läs/skriv [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returnerar:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Returnerar eller sätter ett återuppringningsobjekt som styr hur externt objekt kommer att lagras. Läs/skriv [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Returnerar eller sätter HTML-kodningsnamn. Detta värde kommer att sparas i den genererade HTML-filen, men det är upp till anroparen att säkerställa att filen sparas i denna kodning. Läs/skriv String.

**Returnerar:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Returnerar eller sätter HTML-kodningsnamn. Detta värde kommer att sparas i den genererade HTML-filen, men det är upp till anroparen att säkerställa att filen sparas i denna kodning. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |