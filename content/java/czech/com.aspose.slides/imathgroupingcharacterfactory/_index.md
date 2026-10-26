---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Umožňuje vytvořit matematický znak pro seskupování
type: docs
url: /cs/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Umožňuje vytvořit matematický znak pro seskupování

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Vytváří matematický znak pro seskupování |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Vytváří matematický znak pro seskupování |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Vytváří matematický znak pro seskupování

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický element, na který se použije znak pro seskupování |
| character | char | znak pro seskupování |
| position | int | pozice znaku pro seskupování |
| verticalJustification | int | vertikální zarovnání |

**Vrací:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový element seskupovacího znaku
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Vytváří matematický znak pro seskupování

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický element, na který se použije znak pro seskupování |

**Vrací:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nový element seskupovacího znaku