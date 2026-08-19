---
title: MathBorderBoxFactory
second_title: Aspose.Slides voor Java API Referentie
description: Staat toe een wiskundige randbox te maken
type: docs
url: /nl/com.aspose.slides/mathborderboxfactory/
---
**Erfenis:**
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

| Constructor | Beschrijving |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Maak een wiskundige randbox door deze op het element toe te passen |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Maak een wiskundige randbox door deze op het element toe te passen |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Maak een wiskundige randbox door deze op het element toe te passen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om randbox toe te passen |

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randbox element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Maak een wiskundige randbox door deze op het element toe te passen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om randbox toe te passen |
| hideTop | boolean | Verberg bovenrand |
| hideBottom | boolean | Verberg onderrand |
| hideLeft | boolean | Verberg linkerrand |
| hideRight | boolean | Verberg rechterrand |
| strikethroughHorizontal | boolean | Randbox doorhalen horizontaal |
| strikethroughVertical | boolean | Randbox doorhalen verticaal |
| strikethroughBottomLeftToTopRight | boolean | Randbox doorhalen links-onder naar rechts-boven |
| strikethroughTopLeftToBottomRight | boolean | Randbox doorhalen links-boven naar rechts-onder |

**Retour:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randbox element