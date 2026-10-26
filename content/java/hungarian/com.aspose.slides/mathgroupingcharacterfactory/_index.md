---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides Java API referenciája
description: Lehetővé teszi a matematikai csoportosító karakter létrehozását
type: docs
url: /hu/com.aspose.slides/mathgroupingcharacterfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Lehetővé teszi matematikai csoportosító karakter létrehozását

--------------------

COM kompatibilitás miatt
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Létrehozza a matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a csoportosító karaktert alkalmazandó matematikai elem |
| character | char | csoportosító karakter |
| position | int | csoportosító karakter pozíciója |
| verticalJustification | int | vertikális igazítás |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Létrehozza a matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | a csoportosító karaktert alkalmazandó matematikai elem |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem