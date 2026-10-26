---
title: IFormatFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create formats via COM interface.
type: docs
url: /hu/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

Lehetővé teszi formátumok létrehozását COM interfészen keresztül.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | Létrehoz egy új [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Létrehoz egy új [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Létrehoz egy új [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```

Létrehoz egy új [IPortionFormat](../../com.aspose.slides/iportionformat).

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Új részformátum.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```

Létrehoz egy új [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Új bekezdésformátum.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```

Létrehoz egy új [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Új szövegkeret-formátum.