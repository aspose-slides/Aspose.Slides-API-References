---
title: IMathAccentFactory
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Consente di creare un accento matematico
type: docs
url: /it/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

Consente di creare un accento matematico

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Crea un accento matematico applicato a un elemento matematico specificato con il valore predefinito del carattere di accento |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Crea un accento matematico applicato a un elemento matematico specificato |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
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
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

Crea un accento matematico applicato a un elemento matematico specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare l'accento |
| accentCharacter | char | carattere di accento |

**Restituisce:**
[IMathAccent](../../com.aspose.slides/imathaccent) - nuovo accento matematico