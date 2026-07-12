---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Permite criar um acento matemático
type: docs
url: /pt/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Permite criar um acento matemático

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Cria um acento matemático aplicado a um elemento matemático especificado com o valor padrão do caractere de acento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Cria um acento matemático aplicado a um elemento matemático especificado |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

Cria um acento matemático aplicado a um elemento matemático especificado com o valor padrão do caractere de acento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o acento |

**Retorna:**
[IMathAccent](../../com.aspose.slides/imathaccent) - novo acento matemático
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Cria um acento matemático aplicado a um elemento matemático especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o acento |
| accentCharacter | char | caractere de acento |

**Retorna:**
[IMathAccent](../../com.aspose.slides/imathaccent) - novo acento matemático