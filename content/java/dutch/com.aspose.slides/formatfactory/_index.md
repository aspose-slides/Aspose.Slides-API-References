---
title: FormatFactory
second_title: Aspose.Slides voor Java API-referentie
description: Staat toe om formats te maken via COM-interface.
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

Staat toe om formats te maken via COM-interface.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInstance()](#getInstance--) | Format factory static instance. |
| [createPortionFormat()](#createPortionFormat--) | Maakt nieuw [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Maakt nieuw [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Maakt nieuw [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Format factory static instance. Alleen-lezen [FormatFactory](../../com.aspose.slides/formatfactory).

**Retour:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Maakt nieuw [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retour:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nieuw portion-formaat.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Maakt nieuw [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retour:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nieuw alinea-formaat.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Maakt nieuw [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retour:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nieuw tekstframe-formaat.