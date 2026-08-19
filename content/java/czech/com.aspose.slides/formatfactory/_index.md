---
title: FormatFactory
second_title: Aspose.Slides pro referenci API jazyka Java
description: Umožňuje vytvářet formáty přes rozhraní COM.
type: docs
url: /cs/com.aspose.slides/formatfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Umožňuje vytvářet formáty přes rozhraní COM.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getInstance()](#getInstance--) | Statická instance továrny na formáty. |
| [createPortionFormat()](#createPortionFormat--) | Vytvoří nový [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Vytvoří nový [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Vytvoří nový [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```

### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```

Statická instance továrny na formáty. Pouze pro čtení [FormatFactory](../../com.aspose.slides/formatfactory).

**Vrací:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```

Vytvoří nový [IPortionFormat](../../com.aspose.slides/iportionformat).

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Nový formát úseku.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```

Vytvoří nový [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Nový formát odstavce.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```

Vytvoří nový [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Vrací:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Nový formát textového rámečku.