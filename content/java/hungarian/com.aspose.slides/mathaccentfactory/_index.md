---
title: MathAccentFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi egy matematikai akcentus létrehozását
type: docs
url: /hu/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Lehetővé teszi egy matematikai akcentus létrehozását

--------------------

COM kompatibilitáshoz
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Methods

| Metódus | Leírás |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Matematikai akcentust hoz létre egy megadott matematikai elemre, az alapértelmezett akcentus karakter értékkel |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Matematikai akcentust hoz létre egy megadott matematikai elemre |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Matematikai akcentust hoz létre egy megadott matematikai elemre, az alapértelmezett akcentus karakter értékkel

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az akcentust alkalmazzák |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Matematikai akcentust hoz létre egy megadott matematikai elemre

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre az akcentust alkalmazzák |
| accentCharacter | char | akcentus karakter |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - új matematikai akcentus