---
title: IFormatFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi formátumok létrehozását COM interfészen keresztül.
type: docs
url: /hu/com.aspose.slides/iformatfactory/
---```
public interface IFormatFactory
```

Lehetővé teszi formátumok létrehozását COM interfészen keresztül.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createPortionFormat()](#createPortionFormat--) | Creates new [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Creates new [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Creates new [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### createPortionFormat() {#createPortionFormat--}
```
public abstract IPortionFormat createPortionFormat()
```


Új [IPortionFormat](../../com.aspose.slides/iportionformat)-t hoz létre.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Új részformátum.
### createParagraphFormat() {#createParagraphFormat--}
```
public abstract IParagraphFormat createParagraphFormat()
```


Új [IParagraphFormat](../../com.aspose.slides/iparagraphformat)-t hoz létre.

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Új bekezdés formátum.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public abstract ITextFrameFormat createTextFrameFormat()
```


Új [ITextFrameFormat](../../com.aspose.slides/itextframeformat)-t hoz létre.

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Új szövegkeret formátum.