---
title: FormatFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi formátumok létrehozását COM interfészen keresztül.
type: docs
url: /hu/com.aspose.slides/formatfactory/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Lehetővé teszi formátumok létrehozását COM interfészen keresztül.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getInstance()](#getInstance--) | Formátum gyári statikus példány. |
| [createPortionFormat()](#createPortionFormat--) | Új [IPortionFormat](../../com.aspose.slides/iportionformat)-t hoz létre. |
| [createParagraphFormat()](#createParagraphFormat--) | Új [IParagraphFormat](../../com.aspose.slides/iparagraphformat)-t hoz létre. |
| [createTextFrameFormat()](#createTextFrameFormat--) | Új [ITextFrameFormat](../../com.aspose.slides/itextframeformat)-t hoz létre. |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Formátum gyári statikus példány. Csak olvasható [FormatFactory](../../com.aspose.slides/formatfactory).

**Visszatér:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Új [IPortionFormat](../../com.aspose.slides/iportionformat)-t hoz létre.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Új részlet formátum.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Új [IParagraphFormat](../../com.aspose.slides/iparagraphformat)-t hoz létre.

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Új bekezdés formátum.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Új [ITextFrameFormat](../../com.aspose.slides/itextframeformat)-t hoz létre.

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Új szövegkeret formátum.