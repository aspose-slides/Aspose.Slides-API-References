---
title: MathBorderBoxFactory
second_title: Aspose.Slides Java API referenciája
description: Lehetővé teszi egy matematikai szegélydoboz létrehozását
type: docs
url: /hu/com.aspose.slides/mathborderboxfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Lehetővé teszi egy matematikai szegélydoboz létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Matematikai szegélydoboz létrehozása az elemre alkalmazva |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Matematikai szegélydoboz létrehozása az elemre alkalmazva |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Matematikai szegélydoboz létrehozása az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a szegélydobozra alkalmazandó matematikai elem |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új szegélydoboz elem
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Matematikai szegélydoboz létrehozása az elemre alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a szegélydobozra alkalmazandó matematikai elem |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal él elrejtése |
| hideRight | boolean | Jobb él elrejtése |
| strikethroughHorizontal | boolean | Vízszintes áthúzás a szegélydobozban |
| strikethroughVertical | boolean | Függőleges áthúzás a szegélydobozban |
| strikethroughBottomLeftToTopRight | boolean | Szegélydoboz áthúzás bal alsó-felső jobb felé |
| strikethroughTopLeftToBottomRight | boolean | Szegélydoboz áthúzás bal felső-jobb alsó felé |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új szegélydoboz elem