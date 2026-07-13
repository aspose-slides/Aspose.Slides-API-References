---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umožňuje vytvořit matematický skupinovací znak
type: docs
url: /cs/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Umožňuje vytvořit matematický skupinovací znak

--------------------

Pro kompatibilitu s COM
## Methods

| Metoda | Popis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Vytváří matematický skupinovací znak

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se má aplikovat skupinovací znak |
| character | char | skupinovací znak |
| position | int | pozice skupinovacího znaku |
| verticalJustification | int | vertikální zarovnání |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový prvek skupinovacího znaku
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Vytváří matematický skupinovací znak

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se má aplikovat skupinovací znak |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový prvek skupinovacího znaku