---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy matematikai csoportosító karakter létrehozását
type: docs
url: /hu/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Lehetővé teszi egy matematikai csoportosító karakter létrehozását

--------------------

COM kompatibilitáshoz
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Létrehozza a matematikai csoportosító karaktert |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Létrehozza a matematikai csoportosító karaktert |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Létrehozza a matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |
| character | char | csoportosító karakter |
| position | int | a csoportosító karakter pozíciója |
| verticalJustification | int | vertikális igazítás |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Létrehozza a matematikai csoportosító karaktert

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |

**Visszatérési érték:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - új csoportosító karakter elem