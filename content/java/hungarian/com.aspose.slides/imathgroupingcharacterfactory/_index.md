---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi egy matematikai csoportosító karakter létrehozását
type: docs
url: /hu/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Lehetővé teszi egy matematikai csoportosító karakter létrehozását

--------------------

A COM kompatibilitáshoz
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Létrehoz egy matematikai csoportosító karaktert |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Létrehoz egy matematikai csoportosító karaktert |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Létrehoz egy matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a csoportosító karakter alkalmazásához |
| character | char | csoportosító karakter |
| position | int | csoportosító karakter pozíciója |
| verticalJustification | int | vertikális igazítás |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Létrehoz egy matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem a csoportosító karakter alkalmazásához |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem