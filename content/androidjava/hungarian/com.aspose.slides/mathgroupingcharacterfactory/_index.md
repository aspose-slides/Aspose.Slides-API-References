---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Lehetővé teszi egy matematikai csoportosító karakter létrehozását
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

Lehetővé teszi egy matematikai csoportosító karakter létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Létrehozza a matematikai csoportosító karaktert |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Létrehozza a matematikai csoportosító karaktert |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |
| character | char | grouping character |
| position | int | position of grouping character |
| verticalJustification | int | vertical justification |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem