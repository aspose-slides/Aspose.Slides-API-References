---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
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
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crea un acento matemático aplicable a un elemento matemático especificado con el valor predeterminado del carácter de acento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crea un acento matemático aplicable a un elemento matemático especificado |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


Crea un acento matemático aplicable a un elemento matemático especificado con el valor predeterminado del carácter de acento

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que se aplica el acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Crea un acento matemático aplicable a un elemento matemático especificado

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que se aplica el acento |
| accentCharacter | char | carácter de acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático