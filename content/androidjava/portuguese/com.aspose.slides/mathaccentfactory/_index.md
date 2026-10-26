---
title: MathAccentFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar um acento matemático
type: docs
url: /pt/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Permite criar um acento matemático

--------------------

Para compatibilidade COM
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Cria um acento matemático aplicado a um elemento matemático especificado com o valor padrão do caractere de acento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Cria um acento matemático aplicado a um elemento matemático especificado |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
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
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Cria um acento matemático aplicado a um elemento matemático especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar o acento |
| accentCharacter | char | caractere de acento |

**Retorna:**
[IMathAccent](../../com.aspose.slides/imathaccent) - novo acento matemático