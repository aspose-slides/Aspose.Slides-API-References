---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Stelt toe een wiskundig randvak te maken
type: docs
url: /nl/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Staat toe een wiskundig randvak te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Maak een wiskundig randvak door het toe te passen op het element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Maak een wiskundig randvak door het toe te passen op het element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


Maak een wiskundig randvak door het toe te passen op het element

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om randvak toe te passen |

**Retourwaarde:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randvak element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Maak een wiskundig randvak door het toe te passen op het element

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | wiskundig element om randvak toe te passen |
| hideTop | boolean | Verberg bovenrand |
| hideBottom | boolean | Verberg onderrand |
| hideLeft | boolean | Verberg linkerrand |
| hideRight | boolean | Verberg rechterrand |
| strikethroughHorizontal | boolean | Horizontale doorstrepen van randvak |
| strikethroughVertical | boolean | Verticale doorstrepen van randvak |
| strikethroughBottomLeftToTopRight | boolean | Diagonale doorstrepen van linksonder naar rechtsboven |
| strikethroughTopLeftToBottomRight | boolean | Diagonale doorstrepen van linksboven naar rechtsonder |

**Retourwaarde:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nieuw randvak element