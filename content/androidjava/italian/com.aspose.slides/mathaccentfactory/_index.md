---
title: MathAccentFactory
second_title: Aspose.Slides per Android tramite Java API Reference
description: Consente di creare un accento matematico
type: docs
url: /it/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

Consente di creare un accento matematico

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crea un accento matematico applicato a un elemento matematico specificato |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare l'accento |

**Restituisce:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuovo accento matematico
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


Crea un accento matematico applicato a un elemento matematico specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare l'accento |
| accentCharacter | char | carattere di accento |

**Restituisce:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuovo accento matematico