---
title: FormatFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa format via COM-gränssnitt.
type: docs
url: /sv/com.aspose.slides/formatfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Tillåter att skapa format via COM-gränssnitt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInstance()](#getInstance--) | Statisk instans av formatfabriken. |
| [createPortionFormat()](#createPortionFormat--) | Skapar ny [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Skapar ny [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Skapar ny [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Statisk instans av formatfabriken. Skrivskyddad [FormatFactory](../../com.aspose.slides/formatfactory).

**Returnerar:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Skapar ny [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returnerar:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Ny portionsformat.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Skapar ny [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returnerar:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nytt styckeformat.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Skapar ny [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Returnerar:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nytt textramformat.