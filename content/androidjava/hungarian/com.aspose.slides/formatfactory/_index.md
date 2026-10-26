---
title: FormatFactory
second_title: Aspose.Slides for Android a Java API referencia szerint
description: Lehetővé teszi formátumok létrehozását COM interfészen keresztül.
type: docs
url: /hu/com.aspose.slides/formatfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
| [getInstance()](#getInstance--) | Formátumgyári statikus példány. |
| [createPortionFormat()](#createPortionFormat--) | Új [IPortionFormat](../../com.aspose.slides/iportionformat) létrehozása. |
| [createParagraphFormat()](#createParagraphFormat--) | Új [IParagraphFormat](../../com.aspose.slides/iparagraphformat) létrehozása. |
| [createTextFrameFormat()](#createTextFrameFormat--) | Új [ITextFrameFormat](../../com.aspose.slides/itextframeformat) létrehozása. |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Formátumgyári statikus példány. Csak olvasható [FormatFactory](../../com.aspose.slides/formatfactory).

**Visszatér:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Új [IPortionFormat](../../com.aspose.slides/iportionformat) létrehozása.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Új szakaszformátum.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

Új [IParagraphFormat](../../com.aspose.slides/iparagraphformat) létrehozása.

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Új bekezdésformátum.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

Új [ITextFrameFormat](../../com.aspose.slides/itextframeformat) létrehozása.

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Új szövegkeret formátum.