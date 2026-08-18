---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math grouping character
type: docs
url: /es/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Permite crear un carácter de agrupación matemática

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Crea un carácter de agrupación matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el carácter de agrupación |
| character | char | carácter de agrupación |
| position | int | posición del carácter de agrupación |
| verticalJustification | int | justificación vertical |

**Devuelve:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nuevo elemento de carácter de agrupación
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Crea un carácter de agrupación matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el carácter de agrupación |

**Devuelve:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - nuevo elemento de carácter de agrupación