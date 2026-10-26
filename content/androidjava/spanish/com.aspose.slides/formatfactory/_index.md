---
title: FormatFactory
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Permite crear formatos a través de la interfaz COM.
type: docs
url: /es/com.aspose.slides/formatfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Permite crear formatos a través de la interfaz COM.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInstance()](#getInstance--) | Instancia estática de la fábrica de formatos. |
| [createPortionFormat()](#createPortionFormat--) | Crea un nuevo [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Crea un nuevo [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Crea un nuevo [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Instancia estática de la fábrica de formatos. Solo lectura [FormatFactory](../../com.aspose.slides/formatfactory).

**Devuelve:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Crea un nuevo [IPortionFormat](../../com.aspose.slides/iportionformat).

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nuevo formato de porción.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

Crea un nuevo [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Devuelve:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nuevo formato de párrafo.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

Crea un nuevo [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Devuelve:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nuevo formato de marco de texto.