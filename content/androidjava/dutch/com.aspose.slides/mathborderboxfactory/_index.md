---
title: MathBorderBoxFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een wiskundige randbox te maken
type: docs
url: /nl/com.aspose.slides/mathborderboxfactory/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Staat toe een wiskundige randbox te maken

--------------------

Voor COM-compatibiliteit
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Maak een wiskundige randbox door deze toe te passen op het element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om de randbox toe te passen |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randbox element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Maak een wiskundige randbox door deze toe te passen op het element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om de randbox toe te passen |
| hideTop | boolean | Verberg bovenrand |
| hideBottom | boolean | Verberg onderrand |
| hideLeft | boolean | Verberg linkerrand |
| hideRight | boolean | Verberg rechterrand |
| strikethroughHorizontal | boolean | Randbox doorhalen horizontaal |
| strikethroughVertical | boolean | Randbox doorhalen verticaal |
| strikethroughBottomLeftToTopRight | boolean | Randbox doorhalen onder-links naar boven-rechts |
| strikethroughTopLeftToBottomRight | boolean | Randbox doorhalen boven-links naar onder-rechts |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randbox element