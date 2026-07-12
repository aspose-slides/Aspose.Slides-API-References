---
title: MathBorderBoxFactory
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Lehetővé teszi egy matematikai keretdoboz létrehozását
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

Lehetővé teszi matematikai keretdoboz létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Matematikai keretdoboz létrehozása az elemhez alkalmazva |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Matematikai keretdoboz létrehozása az elemhez alkalmazva |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Matematikai keretdoboz létrehozása az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a keretdoboz alkalmazásához |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új keretdoboz elem
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Matematikai keretdoboz létrehozása az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a keretdoboz alkalmazásához |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal él elrejtése |
| hideRight | boolean | Jobb él elrejtése |
| strikethroughHorizontal | boolean | Vízszintes áthúzás a keretdobozban |
| strikethroughVertical | boolean | Függőleges áthúzás a keretdobozban |
| strikethroughBottomLeftToTopRight | boolean | Áthúzás bal alsó saroktól jobb felső sarokig a keretdobozban |
| strikethroughTopLeftToBottomRight | boolean | Áthúzás bal felső saroktól jobb alsó sarokig a keretdobozban |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új keretdoboz elem