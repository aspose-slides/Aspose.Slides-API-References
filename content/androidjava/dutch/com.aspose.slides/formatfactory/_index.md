---
title: FormatFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe om opmaak via COM-interface te maken.
type: docs
url: /nl/com.aspose.slides/formatfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Staat toe om opmaak via COM-interface te maken.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | Statische instantie van formatfactory. |
| [createPortionFormat()](#createPortionFormat--) | Maakt een nieuwe [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Maakt een nieuwe [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Maakt een nieuwe [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Statische instantie van formatfactory. Alleen-lezen [FormatFactory](../../com.aspose.slides/formatfactory).

**Retourneert:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Maakt een nieuwe [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retourneert:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nieuw portionformaat.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Maakt een nieuwe [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retourneert:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nieuw alinea-formaat.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Maakt een nieuwe [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retourneert:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nieuw tekstframe-formaat.