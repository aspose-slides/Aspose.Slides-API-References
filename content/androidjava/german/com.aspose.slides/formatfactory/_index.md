---
title: FormatFactory
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Ermöglicht das Erstellen von Formaten über die COM-Schnittstelle.
type: docs
url: /de/com.aspose.slides/formatfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Ermöglicht das Erstellen von Formaten über die COM-Schnittstelle.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInstance()](#getInstance--) | Statische Instanz der Formatfabrik. |
| [createPortionFormat()](#createPortionFormat--) | Erstellt ein neues [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Erstellt ein neues [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Erstellt ein neues [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Statische Instanz der Formatfabrik. Nur lesbar [FormatFactory](../../com.aspose.slides/formatfactory).

**Rückgabe:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Erstellt ein neues [IPortionFormat](../../com.aspose.slides/iportionformat).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Neuer Portion-Format.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Erstellt ein neues [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Rückgabe:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Neuer Absatz-Format.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Erstellt ein neues [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Rückgabe:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Neuer Textfeld-Format.