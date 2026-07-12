---
title: MathAccentFactory
second_title: Aspose.Slides para Android a través de la Referencia de API Java
description: Permite crear un acento matemático
type: docs
url: /es/com.aspose.slides/mathaccentfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Permite crear un acento matemático

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crea un acento matemático aplicándolo a un elemento matemático especificado con el valor predeterminado del carácter de acento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crea un acento matemático aplicándolo a un elemento matemático especificado |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Crea un acento matemático aplicándolo a un elemento matemático especificado con el valor predeterminado del carácter de acento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Crea un acento matemático aplicándolo a un elemento matemático especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el acento |
| accentCharacter | char | carácter de acento |

**Devuelve:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuevo acento matemático