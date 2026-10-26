---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Umožňuje vytvořit matematický seskupovací znak
type: docs
url: /cs/com.aspose.slides/mathgroupingcharacterfactory/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Umožňuje vytvořit matematický seskupovací znak

--------------------

Pro kompatibilitu s COM
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Vytváří matematický seskupovací znak |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Vytváří matematický seskupovací znak |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Vytváří matematický seskupovací znak

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje seskupovací znak |
| character | char | seskupovací znak |
| position | int | pozice seskupovacího znaku |
| verticalJustification | int | vertikální zarovnání |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový element seskupovacího znaku
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Vytváří matematický seskupovací znak

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje seskupovací znak |

**Návratová hodnota:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový element seskupovacího znaku