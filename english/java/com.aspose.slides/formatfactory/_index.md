---
title: FormatFactory
second_title: Aspose.Sildes for Java API Reference
description: p
 Allows to create formats via COM interface.
type: docs
weight: 215
url: /java/com.aspose.slides/formatfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Allows to create formats via COM interface.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Format factory static instance. |
| [createPortionFormat()](#createPortionFormat--) | Creates new [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Creates new [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Creates new [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Format factory static instance. Read-only [FormatFactory](../../com.aspose.slides/formatfactory).

**Returns:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Creates new [IPortionFormat](../../com.aspose.slides/iportionformat).

**Returns:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - New portion format.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Creates new [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - New paragraph format.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Creates new [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Returns:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - New text frame format.
