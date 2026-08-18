---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi egy math border box létrehozását
type: docs
url: /hu/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Lehetővé teszi egy math border box létrehozását

--------------------

COM kompatibilitásért
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Math border box létrehozása az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math elem a border box alkalmazásához |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új border box elem
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Math border box létrehozása az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math elem a border box alkalmazásához |
| hideTop | boolean | Felső él elrejtése |
| hideBottom | boolean | Alsó él elrejtése |
| hideLeft | boolean | Bal él elrejtése |
| hideRight | boolean | Jobb él elrejtése |
| strikethroughHorizontal | boolean | Border Box vízszintes áthúzása |
| strikethroughVertical | boolean | Border Box függőleges áthúzása |
| strikethroughBottomLeftToTopRight | boolean | Border Box áthúzása bal alsó sarokból jobb felső sarokba |
| strikethroughTopLeftToBottomRight | boolean | Border Box áthúzása bal felső sarokból jobb alsó sarokba |

**Visszatérési érték:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - új border box elem