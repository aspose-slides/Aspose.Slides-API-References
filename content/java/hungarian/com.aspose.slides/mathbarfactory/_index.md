---
title: MathBarFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi egy matematikai vonal létrehozását
type: docs
url: /hu/com.aspose.slides/mathbarfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

Lehetővé teszi egy matematikai vonal létrehozását

--------------------

A COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Matematikai vonalat hoz létre az elemhez alkalmazva |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Matematikai vonalat hoz létre az elemhez alkalmazva |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```

### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```

Matematikai vonalat hoz létre az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a vonalat alkalmazandó matematikai elem |

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - új matematikai vonal elem
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```

Matematikai vonalat hoz létre az elemhez alkalmazva

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a vonalat alkalmazandó matematikai elem |
| position | int | A vonal pozíciója |

**Visszatér:**
[IMathBar](../../com.aspose.slides/imathbar) - új matematikai vonal elem