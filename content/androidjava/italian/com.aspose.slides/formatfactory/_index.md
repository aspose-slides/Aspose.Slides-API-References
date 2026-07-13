---
title: FormatFactory
second_title: Riferimento API Java per Aspose.Slides per Android
description: Consente di creare formati tramite interfaccia COM.
type: docs
url: /it/com.aspose.slides/formatfactory/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Consente di creare formati tramite interfaccia COM.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInstance()](#getInstance--) | Istanza statica della fabbrica di formati. |
| [createPortionFormat()](#createPortionFormat--) | Crea un nuovo [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Crea un nuovo [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Crea un nuovo [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Istanza statica della fabbrica di formati. Solo lettura [FormatFactory](../../com.aspose.slides/formatfactory).

**Restituisce:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Crea un nuovo [IPortionFormat](../../com.aspose.slides/iportionformat).

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nuovo formato di porzione.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Crea un nuovo [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Restituisce:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nuovo formato di paragrafo.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Crea un nuovo [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Restituisce:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nuovo formato di casella di testo.