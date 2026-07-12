---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides para Android via Java API Reference
description: Permite criar um caractere de agrupamento matemático
type: docs
url: /pt/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Permite criar um caractere de agrupamento matemático

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Cria um caractere de agrupamento matemático |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Cria um caractere de agrupamento matemático |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Cria um caractere de agrupamento matemático

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o caractere de agrupamento |
| character | char | caractere de agrupamento |
| position | int | posição do caractere de agrupamento |
| verticalJustification | int | justificação vertical |

**Retorno:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - novo elemento de caractere de agrupamento
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Cria um caractere de agrupamento matemático

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o caractere de agrupamento |

**Retorno:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - novo elemento de caractere de agrupamento