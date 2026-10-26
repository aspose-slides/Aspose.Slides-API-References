---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: Permite crear un acento matemático
type: docs
url: /es/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Permite crear un acento matemático

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crea un acento matemático aplicado a un elemento matemático especificado con el valor predeterminado del carácter de acento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crea un acento matemático aplicado a un elemento matemático especificado |
### createMathAccent(IMMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Crea un acento matemático aplicado a un elemento matemático especificado con el valor predeterminado del carácter de acento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático
### createMathAccent(IMMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMMathElement element, char accentCharacter)
```


Crea un acento matemático aplicado a un elemento matemático especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el acento |
| accentCharacter | char | carácter de acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático